## Tested Application

Website: https://demoqa.com/login  
Type: Web application  
Testing type: Manual testing (functional, UI, validation)

## BUG-01: Login button does not respond

- Environment:
  - URL: https://demoqa.com/login
  - Browser: Chrome
  - OS: Windows 10

- Preconditions:
  - User is registered
  - User is on the login page

- Test Data:
  - Username: testuser
  - Password: Test@123

- Steps to Reproduce:
  1. Open https://demoqa.com/login
  2. Enter valid username
  3. Enter valid password
  4. Click the "Login" button

- Actual Result:
  - No action occurs after clicking the button
  - User is not logged in
  - No error message is displayed

- Expected Result:
  - User should be logged in successfully
  - User should be redirected to the profile page

- Severity: Critical
- Priority: High

- Notes:
  - Issue reproduced multiple times

---

## BUG-02: Login form is submitted with empty fields

- Environment:
  - URL: https://demoqa.com/login
  - Browser: Chrome
  - OS: Windows 10

- Preconditions:
  - User is on the login page

- Steps to Reproduce:
  1. Open https://demoqa.com/login
  2. Leave username field empty
  3. Leave password field empty
  4. Click the "Login" button

- Actual Result:
  - Form is submitted without validation
  - No error messages are displayed

- Expected Result:
  - Validation errors should be displayed for required fields
  - Form should not be submitted

- Severity: High
- Priority: High

---

## BUG-03: Password is visible in plain text

- Environment:
  - URL: https://demoqa.com/login
  - Browser: Chrome
  - OS: Windows 10

- Preconditions:
  - User is on the login page

- Steps to Reproduce:
  1. Open https://demoqa.com/login
  2. Enter any value into the password field

- Actual Result:
  - Password is displayed in plain text

- Expected Result:
  - Password should be masked (displayed as dots or asterisks)

- Severity: High
- Priority: High
