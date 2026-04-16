Bug ID: BR-001
Test Case ID: TC-LG-002

Title: System allows login with incorrect password

Severity: High
Priority: High

Environment: Web Application

Precondition:
User account exists

Steps to Reproduce:
1. Open Login page
2. Enter valid username
3. Enter incorrect password
4. Click "Login" button

Test Data:
Valid username, invalid password

Expected Result:
System should deny login and display error message

Actual Result:
User is able to login successfully using incorrect password

---

Bug ID: BR-002
Test Case ID: TC-LG-004

Title: Required field validation is not displayed when login fields are empty

Severity: Medium
Priority: High

Environment: Web Application

Precondition:
Login page is accessible

Steps to Reproduce:
1. Open Login page
2. Leave username field empty
3. Leave password field empty
4. Click "Login" button

Test Data:
Empty username and password fields

Expected Result:
System should display required field validation messages

Actual Result:
No validation message is displayed

---

Bug ID: BR-003
Test Case ID: TC-LG-006

Title: System allows login with incorrect case-sensitive password

Severity: High
Priority: High

Environment: Web Application

Precondition:
User account exists

Steps to Reproduce:
1. Open Login page
2. Enter valid username
3. Enter password with incorrect letter case
4. Click "Login" button

Test Data:
Valid username, incorrect case password

Expected Result:
Login should fail and display error message

Actual Result:
User is able to login successfully

---

Bug ID: BR-004
Test Case ID: TC-AT-005

Title: System allows check-out without prior check-in

Severity: High
Priority: High

Environment: Web Application (HR Attendance System)

Precondition:
User has not checked in

Steps to Reproduce:
1. Open Attendance page
2. Click "Check Out" button

Test Data:
Valid user session

Expected Result:
System should block check-out and display warning message

Actual Result:
System allows check-out without check-in

---

Bug ID: BR-005
Test Case ID: TC-AT-007

Title: Attendance history displays incorrect or incomplete data

Severity: Medium
Priority: Medium

Environment: Web Application (HR Attendance System)

Precondition:
User has existing attendance records

Steps to Reproduce:
1. Open Attendance History page
2. Observe displayed records

Test Data:
Existing attendance records

Expected Result:
System should display accurate and complete attendance history

Actual Result:
Displayed attendance data is incorrect or missing entries
