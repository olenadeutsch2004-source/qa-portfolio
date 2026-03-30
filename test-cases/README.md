# Test Cases

## Feanure: Login Page

Deskription: Testing login functionality of web application.
Fields:
-Email
-Password
-Login button

### Test Case 1: Login with spaces in email
- Steps:
  1. Open login page
  2. Enter email with spaces before and after
  3. Enter valid password
  4. Click login
- Expected result:
  Email is trimmed or validation error is shown

### Test Case 2: Invalid password
- Steps:
  1. Enter valid username
  2. Enter invalid password
  3. Click login
- Expected result:
  Error message is displayed

  ### Test Case 3 – Empty fields

-Steps: 
1. Open login page
2. Leave email emty
3. Leave password empty
4. Click login
- Expected result:
  Validation error is schown
  
### Test Case 4 – Invalid email format

-Steps: 
1. Open login page
2. Enter invalid email (exsample: 123)
3. Clicck login

### Test Case 5 – Password field is mas

-Steps: 
1.Open login page
2. Enter password

-Expected result:
Password is displayed as dots or asterisks

### Test Case 6 – Search product

* Steps: Enter product name → Click search
* Expected Result: Relevant results displayed
