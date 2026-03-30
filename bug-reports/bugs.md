# Bug Reports

## Bug 1: Login button not working

- Steps:
  1. Open login page
  2. Enter valid email and password
  3. Click login button

- Actual result:
  Nothing happens

- Expected result:
  User should be logged in

- Severity: High
- Priority: High

  ## Bug 2: Login with empty fields

- Steps:
  1. Open login page
  2. Leave email empty
  3. Leave password empty
  4. Click login button

- Actual result:
  User can submit form without data

- Expected result:
  Validation error should appear

- Severity: Medium
- Priority: Medium

  ## Bug 3: Invalid email format accepted
- Steps:
  1. Open login page
  2. Enter invalid email (e.g., "abc123")
  3. Enter valid password
  4. Click login
- Actual result:
  User can submit form
- Expected result:
  Email validation error should appear
- Severity: Medium
- Priority: Medium

## Bug 4: Password visible in field
- Steps:
  1. Open login page
  2. Enter password
- Actual result:
  Password is visible as plain text
- Expected result:
  Password should be masked
- Severity: High
- Priority: High

## Bug 5: Page crashes on multiple login clicks
- Steps:
  1. Open login page
  2. Enter valid email and password
  3. Click login button rapidly 5 times
- Actual result:
  Page freezes or crashes
- Expected result:
  Only one login attempt processed
- Severity: High
- Priority: Medium

## Bug 6: Forgot password link not working
- Steps:
  1. Open login page
  2. Click "Forgot password" link
- Actual result:
  Nothing happens
- Expected result:
  User should be redirected to password reset page
- Severity: Medium
- Priority: Medium

## Bug 7: Login error message disappears too fast
- Steps:
  1. Enter invalid email or password
  2. Click login
- Actual result:
  Error message disappears after 1 second
- Expected result:
  Error message should remain visible until user closes it
- Severity: Low
- Priority: Low
