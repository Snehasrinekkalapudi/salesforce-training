Salesforce Summer Program – Day 10

1. System Overview

The College Management System is a mini Salesforce project that integrates CRM concepts, automation, Apex, SOQL, Triggers, and Lightning Web Components.

The system helps manage:

- Students
- Faculty
- Courses
- Departments
- Attendance
- Registrations

The project demonstrates how frontend, backend, database, and automation work together in enterprise applications.

---

2. CRM Concepts

Student

Stores student details such as:

- Name
- Email
- Attendance
- Registered courses

Faculty

Stores faculty information and assigned courses.

Course

Stores course details such as:

- Course name
- Seat limit
- Faculty assignment

Department

Stores department information and related courses.

CRM helps organize and manage all academic records efficiently.

---

3. Data Model

Objects Used

- Student__c
- Faculty__c
- Course__c
- Department__c

Relationships

- Student → Course
- Course → Faculty
- Course → Department

Important Fields

- Student Email
- Attendance Percentage
- Seat Limit
- Remaining Seats

The data model connects all records logically inside the system.

---

4. Validation Rules

Validation rules help maintain correct and secure data.

Examples

Email Mandatory

Student registration cannot happen without email.

Seat Limit Validation

Students cannot register if course seats are full.

Attendance Validation

Attendance percentage cannot exceed 100%.

Validation rules prevent incorrect data entry.

---

5. Formula Fields

Formula fields automatically calculate values.

Examples

Remaining Seats

Seat Limit - Registered Students

Attendance Percentage

(Classes Attended / Total Classes) × 100

Formula fields reduce manual calculations.

---

6. Flow Automation

Flows automate business processes without coding.

Examples

Registration Confirmation

After student registration, confirmation email is sent automatically.

Attendance Warning

Students with attendance below 75% receive warning notifications.

Course Update Notification

Faculty receive alerts when courses become full.

Flows improve automation and efficiency.

---

7. Apex Logic

Apex is used for advanced backend logic.

Examples

Eligibility Calculation

Checks whether a student is eligible for a course.

Bulk Operations

Processes multiple student registrations efficiently.

Complex Validations

Handles advanced business rules.

Apex provides flexibility for enterprise-level logic.

---

8. UI Screens

Student Dashboard

Displays:

- Student profile
- Registered courses
- Attendance
- Notifications

Faculty Dashboard

Displays:

- Assigned courses
- Student attendance
- Alerts

Registration Screen

Allows students to register for courses.

LWC components create modern and reusable user interfaces.

---

9. Complete Data Flow

Student clicks Register →

LWC registration screen collects input →

Validation Rules check email and seat availability →

Flow sends confirmation message →

Apex Trigger updates course seat count →

Database stores registration record →

Notification is sent to faculty and student →

Dashboard updates automatically.

This flow shows how UI, backend logic, automation, and database work together.

---

10. Scaling Thinking

If 50,000 students use the system, problems may occur such as:

Performance Issues

Large data volume may slow queries and UI.

Data Consistency Problems

Simultaneous registrations may create duplicate or incorrect data.

Notification Delays

Bulk notifications may take time to process.

Security Risks

Unauthorized users may try to access sensitive information.

Enterprise systems require optimization, security, and scalable architecture to handle large users.

---

11. Reflection

After learning Salesforce, I realized that enterprise software systems are built using many connected layers such as:

- Frontend UI
- Backend logic
- Database
- Automation
- Security
- Events

Modern enterprise systems are not just about coding. They require:

- Structured architecture
- Reliable automation
- Data management
- Scalability
- Team collaboration

Salesforce combines all these concepts into one integrated platform for building large business applications.
