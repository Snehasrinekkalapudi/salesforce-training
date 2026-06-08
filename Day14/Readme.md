Salesforce Summer Program – Day 14

1. Approval Workflow Examples

Enterprise systems use approval workflows to control important business operations.

---

Course Creation Approval

Workflow

Faculty creates a new course request →

Department Head reviews the course →

Admin gives final approval.

After Approval

- Course becomes active
- Students can register

After Rejection

- Course request is returned with comments

---

Faculty Leave Request

Workflow

Faculty submits leave request →

HOD reviews request →

HR approves final request.

After Approval

- Leave status updated
- Notification sent to faculty

After Rejection

- Faculty receives rejection reason

---

Student Scholarship Request

Workflow

Student submits scholarship form →

Faculty verifies eligibility →

Finance department approves payment.

After Approval

- Scholarship amount processed

After Rejection

- Student notified about rejection

---

Budget Approval

Workflow

Department submits budget request →

Finance manager reviews budget →

Admin provides final approval.

After Approval

- Budget allocated

After Rejection

- Request returned for correction

---

2. Branching Flow Logic

Attendance Monitoring Flow

Decision Point 1

If attendance < 75%

Action

Send warning email to student.

---

Decision Point 2

If attendance < 60%

Action

Send notification to parents.

---

Decision Point 3

If attendance < 50%

Action

Escalate issue to admin and faculty advisor.

---

Flow Logic Explanation

Decision Elements

Check attendance percentage conditions.

Branches

Different paths execute based on attendance level.

Actions Triggered

- Emails
- Notifications
- Escalations
- Dashboard updates

Branching logic helps automate different business responses based on conditions.

---

3. Governance Explanation

Enterprise systems cannot allow everyone to directly change important records because it creates serious risks.

Security Risks

Unauthorized users may access sensitive data.

Misuse

Users may intentionally or accidentally modify records incorrectly.

Wrong Approvals

Critical actions may happen without proper authorization.

Business Risk

Incorrect updates can affect finance, student records, and operations.

Governance ensures that only authorized people can perform important actions.

Approval workflows improve control, accountability, and security.

---

4. Reflection

Enterprises require controlled workflows because large organizations handle sensitive data and important business operations daily.

Controlled workflows help:

- Maintain security
- Prevent mistakes
- Ensure proper approvals
- Improve accountability
- Maintain reliable business processes

Without controlled workflows, enterprise systems may face:

- Data inconsistency
- Unauthorized actions
- Financial loss
- Operational failures

Salesforce automation and approval systems help organizations operate in a safe, structured, and scalable way.
