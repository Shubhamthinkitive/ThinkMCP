# QA Test Scenarios for Login Feature

## Functional Test Cases

### 1. Valid Login
- **Description**: Verify that a user can successfully login with valid credentials
- **Test Steps**:
  1. Navigate to login page
  2. Enter valid username/email
  3. Enter valid password
  4. Click on Login button
- **Expected Result**: User should be successfully logged in and redirected to dashboard

### 2. Invalid Login 
- **Description**: Verify system behavior with invalid credentials
- **Test Steps**:
  1. Navigate to login page
  2. Enter invalid username/email
  3. Enter invalid password
  4. Click on Login button
- **Expected Result**: Appropriate error message should be displayed

### 3. Password Reset
- **Description**: Verify password reset functionality
- **Test Steps**:
  1. Navigate to login page
  2. Click on "Forgot Password" link
  3. Enter registered email
  4. Click on Submit button
- **Expected Result**: Password reset email should be sent to user's email

## Non-Functional Test Cases

### 1. Security Testing
- Verify protection against SQL injection
- Test for brute force attack prevention
- Ensure passwords are not stored in plain text

### 2. Performance Testing
- Measure login response time under normal load
- Test login functionality under heavy load

### 3. Usability Testing
- Verify login form is accessible
- Test login functionality on different browsers
- Test login functionality on different devices