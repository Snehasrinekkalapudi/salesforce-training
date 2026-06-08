Salesforce Summer Program – Day 6

1. What is SOQL?

SOQL (Salesforce Object Query Language) is used to retrieve and query data from Salesforce objects.
It is similar to SQL but specially designed for Salesforce databases.

SOQL helps developers:

- Fetch records
- Filter data
- Retrieve related object data
- Display useful business information

Example:

SELECT Name FROM Student__c

---

2. What is an Apex Trigger?

An Apex Trigger is a piece of Apex code that runs automatically when data changes occur in Salesforce.

Triggers can execute during events like:

- Insert
- Update
- Delete

Triggers are mainly used to automate business processes and maintain data consistency.

Example:
After a student registers, a welcome email can be sent automatically.

---

3. Flow vs Trigger

Flow| Trigger
No-code automation tool| Code-based automation
Easy to create and manage| Requires Apex programming
Best for simple tasks| Best for complex business logic
Faster development| More flexibility and control

When to Use

- Use Flow for simple notifications or updates.
- Use Trigger for validations, calculations, or integrations.

---

4. Before vs After Trigger

Before Trigger| After Trigger
Runs before saving records| Runs after saving records
Used for validation and updating fields| Used for notifications and related actions
Faster for modifying values| Useful for post-save operations

Example

- Before Trigger → Validate attendance percentage
- After Trigger → Send email notification

---

5. Trigger Use Cases

1. Student Registration

Event: After Insert
Action: Send welcome email to student.

2. Course Full

Event: After Update
Action: Notify faculty that seats are full.

3. Low Attendance

Event: After Update
Action: Send warning to students below 75% attendance.

4. Fee Payment

Event: After Update
Action: Update student fee status automatically.

5. Exam Results

Event: After Insert
Action: Notify students about published results.

---

6. Query Examples

- Find all students enrolled in Course A.
- Find all courses handled by Faculty X.
- Find students whose attendance is below 75%.
- Find students who have not paid fees.
- Find courses with available seats.

These queries help retrieve important academic and management information quickly.

---

7. Reflection

Enterprise systems need event-driven behavior because they handle large amounts of data and users continuously.

Automatic reactions to events help systems:

- Reduce manual work
- Improve speed and efficiency
- Maintain accurate records
- Send instant notifications
- Automate business processes

Event-driven systems make organizations more reliable, scalable, and efficient.
