## Bug: Login button does not respond

Environment:

* URL: https://demoqa.com/login
* Browser: Chrome
* OS: Windows 10

Preconditions:

* User is registered
* User is on the login page

Test Data:

* Username: testuser
* Password: Test@123

Steps to Reproduce:

1. Open https://demoqa.com/login
2. Enter username: testuser
3. Enter password: Test@123
4. Click the "Login" button

Actual Result:

* No action occurs after clicking the button
* User is not logged in
* No error message is displayed

Expected Result:

* User should be successfully logged in
* User should be redirected to the profile page

Severity: Critical
Priority: High

## Bug 2: Login form is submitted with empty feilds

Environment:

URL: https://demoqa.com/login
Browser: Chrome
OS: Windows 10

Preconditions:

User is on the login page

Steps to Reproduce:

Open https://demoqa.com/login
Leave username field empty
Leave password field empty
Click the "Login" button

Actual Result:

Form is submitted without validation
No error messages are displayed

Expected Result:

Validation errors should be displayed for both fields
Form should not be submitted

Severity: High
Priority: High

## Bug 3: Password is visible in plain text

Environment:

* URL: https://demoqa.com/login
* Browser: Chrome
* OS: Windows 10

Preconditions:

* User is on the login page

Steps to Reproduce:

1. Open https://demoqa.com/login
2. Enter any value into the password field

Actual Result:

* Password is visible in plain text

Expected Result:

* Password should be masked (displayed as dots or asterisks)

Severity: High
Priority: High
