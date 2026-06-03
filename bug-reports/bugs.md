# Bug Reports

## Bug 1: Login button not working
- Tested on: https://demoqa.com/login
- Steps:
  1. Open login page
  2. Enter valid username and password
  3. Click login button
- Actual result:
  Nothing happens
- Expected result:
  User should be redirected to profile page
- Severity: High
- Priority: High

## Bug 2: Login with empty fields
- Tested on: https://demoqa.com/login
- Steps:
  1. Open login page
  2. Leave username empty
  3. Leave password empty
  4. Click login
- Actual result:
  Form is submitted without validation
- Expected result:
  Validation errors for both fields
- Severity: Medium
- Priority: Medium

## Bug 3: Password visible in field
- Tested on: https://demoqa.com/login
- Steps:
  1. Open login page
  2. Enter password
- Actual result:
  Password is visible in plain text
- Expected result:
  Password should be masked
- Severity: High
- Priority: High
