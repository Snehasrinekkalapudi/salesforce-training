Salesforce Summer Program – Day 9

1. Component Communication

Lightning Web Components communicate with each other to share data and update the UI dynamically.

Types of Communication

Parent to Child

Data is passed using public properties ("@api").

Example:
Parent component sends student details to child component.

Child to Parent

Communication happens using custom events.

Example:
Child component sends attendance update event to parent component.

Component to Salesforce Data

LWC retrieves and updates Salesforce records using Apex and Lightning Data Service.

This communication creates reactive and interactive applications.

---

2. Dashboard Design

Student Dashboard

Components

- Header Component
- Student Profile Component
- Attendance Component
- Course List Component
- Notifications Component

Communication

- Attendance component sends updates to dashboard.
- Notifications component receives alerts from backend.
- Course component displays enrolled courses dynamically.

---

Faculty Dashboard

Components

- Faculty Profile Component
- Course Management Component
- Student Attendance Component
- Notifications Component

Communication

- Course component updates student lists.
- Attendance component sends attendance records to backend.
- Notification component displays important updates.

---

Admin Dashboard

Components

- Student Management Component
- Faculty Management Component
- Reports Component
- System Notifications Component

Communication

- Management components send updates to database.
- Reports component retrieves analytics data.
- Notification component receives system alerts.

---

3. Data Flow Explanation

Student Registration Process

UI

Student enters registration details in the registration form.

↓

Validation

Frontend checks required fields and correct input format.

↓

Flow

Salesforce Flow sends confirmation message and performs simple automation.

↓

Apex

Apex Trigger checks business rules such as duplicate registration and seat availability.

↓

Database

Validated student information is stored in Salesforce database.

↓

Notification

System sends registration confirmation email and updates dashboards.

This complete flow shows how frontend, backend, automation, and database work together.

---

4. Aura vs LWC

Aura| LWC
Older Salesforce framework| Modern Salesforce framework
Slower performance| Faster performance
Complex architecture| Simple and lightweight
Uses Aura framework| Uses modern web standards
Less efficient| More reusable and scalable

Why Salesforce Moved to LWC

Salesforce moved to LWC because it:

- Improves application performance
- Uses standard JavaScript
- Supports reusable components
- Simplifies development
- Provides better user experience

LWC is faster, cleaner, and easier to maintain than Aura and Visualforce.

---

5. Reflection

Enterprise applications need modular architecture because large systems contain many features and users.

Modular architecture helps:

- Reuse components
- Reduce duplicate code
- Improve maintainability
- Simplify debugging
- Increase scalability
- Support team collaboration

Breaking applications into small reusable components makes development more organized and efficient.
