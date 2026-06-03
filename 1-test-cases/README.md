# Test Cases

## Feature: Login Page

Description: Testing login functionality of demo website.

Tested on: https://demoqa.com/login
Browser: Chrome
OS: Windows 10

### Test Case 1: Successful login
- Steps:
  1. Open https://demoqa.com/login
  2. Enter valid username: `testuser`
  3. Enter valid password: `Test@123`
  4. Click login button
- Expected result:
  User is redirected to the profile page

### Test Case 2: Login with invalid password
- Steps:
  1. Open https://demoqa.com/login
  2. Enter valid username: `testuser`
  3. Enter invalid password: `wrongpass`
  4. Click login button
- Expected result:
  Error message “Invalid username or password” is displayed

### Test Case 3: Login with empty fields
- Steps:
  1. Open https://demoqa.com/login
  2. Leave username empty
  3. Leave password empty
  4. Click login button
- Expected result:
  Validation error is displayed for both fields
 ### Test Case 4: Invalid username format
- Steps:
  1. Open https://demoqa.com/login
  2. Enter invalid username: `123!@#`
  3. Enter valid password: `Test@123`
  4. Click login button
- Expected result:
  Error message “Invalid username format” is displayed

### Test Case 5: Password field is masked
- Steps:
  1. Open https://demoqa.com/login
  2. Enter any password
- Expected result:
  Password is displayed as dots or asterisks
