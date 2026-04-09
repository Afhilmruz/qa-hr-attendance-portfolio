# Test Plan – HR & Attendance Management System

## 1. Introduction
This Test Plan describes the testing strategy, scope, resources, and schedule for testing the **Web-based HR & Attendance Management System**.  
The purpose of this document is to ensure that the core functionalities of the system meet the expected requirements and are ready for use.

---

## 2. Objective
The objective of this testing is to:
- Verify that critical HR & attendance features function correctly
- Identify defects early and document them clearly
- Ensure system stability before release
- Demonstrate QA best practices through structured testing

---

## 3. Scope of Testing

### 3.1 In-Scope
The following features will be tested:
- Login (Admin & Employee)
- Attendance Check-in
- Attendance Check-out
- Attendance History
- Basic input validation (empty fields, invalid input)

### 3.2 Out-of-Scope
The following features are excluded from this testing:
- Payroll and salary calculation
- Performance appraisal
- Integration with attendance hardware (fingerprint, face recognition)
- Production environment testing

---

## 4. Test Types
The following testing types will be performed:
- Functional Testing
- Smoke Testing
- Regression Testing

---

## 5. Test Environment
- Application Type: Web Application
- Browser: Google Chrome
- Environment: HR / Attendance Demo Web Application

---

## 6. Test Tools
- Manual Testing
- Selenium WebDriver (Java) – Automation Testing
- Postman – API Testing
- Git & GitHub – Version control and documentation

---

## 7. Entry Criteria
Testing will begin when:
- The application is accessible via web browser
- Login functionality is available
- Test environment is stable

---

## 8. Exit Criteria
Testing will be completed when:
- All in-scope test cases have been executed
- Critical and high-severity defects are identified and documented
- Test results are reviewed

---

## 9. Deliverables
The following deliverables will be produced:
- Test Plan document
- Manual test cases (Google Spreadsheet)
- Bug reports
- Automation test scripts
- API test collection

---

## 10. Assumptions & Risks

### Assumptions
- The demo application represents a real HR & attendance system
- Test data is static and reusable

### Risks
- Limited access to real production-like data
- Demo system behavior may differ from real enterprise systems
