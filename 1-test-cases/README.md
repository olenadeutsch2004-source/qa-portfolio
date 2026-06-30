# Test Cases

## Feature: Login Page

Description: Testing login functionality of demo website.

Tested on: https://demoqa.com/login
Browser: Chrome
OS: Windows 10

### TC-01: Successful login
- Precondition:
  User is registered

- Steps:
  1. Open https://demoqa.com/login
  2. Enter valid username: testuser
  3. Enter valid password: Test@123
  4. Click login button

- Expected result:
  User is redirected to the profile page

- Actual result:
  User successfully logged in and redirected to profile page

- Priority: High

### TC-02: Login with invalid password

- Precondition:
  User is registered in the system

- Steps:
  1. Open https://demoqa.com/login
  2. Enter valid username: testuser
  3. Enter invalid password: wrongpass
  4. Click login button

- Expected result:
  Error message is displayed

- Actual result:
  Error message is displayed

- Priority: High

---

### TC-03: Login with empty fields

- Precondition:
  User is on login page

- Steps:
  1. Open https://demoqa.com/login
  2. Leave username field empty
  3. Leave password field empty
  4. Click login button

- Expected result:
  Validation error is displayed for required fields

- Actual result:
  Validation error is displayed

- Priority: High

---

### TC-04: Login with invalid username format

- Precondition:
  User is on login page

- Steps:
  1. Open https://demoqa.com/login
  2. Enter invalid username: 123!@#
  3. Enter valid password: Test@123
  4. Click login button

- Expected result:
  Error message is displayed

- Actual result:
  Error message is displayed

- Priority: Medium

---

### TC-05: Password field is masked

- Precondition:
  User is on login page

- Steps:
  1. Open https://demoqa.com/login
  2. Enter any password

- Expected result:
  Password is hidden (masked with dots or asterisks)

- Actual result:
  Password is masked

- Priority: Low
