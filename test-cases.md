# Login Feature - Test Cases

## TC-LOGIN-001: Login with valid credentials
- **Objective:** Verify that a user can log in with valid credentials.
- **Precondition:** A registered user exists.
- **Test Steps:**
  1. Open the Login page.
  2. Enter a valid email.
  3. Enter a valid password.
  4. Click the Login button.
- **Expected Result:** The user logs in successfully and is redirected to the home page.
- **Actual Result:** To be tested.
- **Status:** Not Run

## TC-LOGIN-002: Login with an incorrect password
- **Objective:** Verify that login fails when the password is incorrect.
- **Precondition:** A registered user exists.
- **Test Steps:**
  1. Open the Login page.
  2. Enter a valid email.
  3. Enter an incorrect password.
  4. Click the Login button.
- **Expected Result:** Login is rejected and an appropriate error message is displayed.
- **Actual Result:** To be tested.
- **Status:** Not Run

## TC-LOGIN-003: Login with empty fields
- **Objective:** Verify validation when required fields are empty.
- **Test Steps:**
  1. Open the Login page.
  2. Leave the email and password fields empty.
  3. Click the Login button.
- **Expected Result:** The system prevents login and indicates the required fields.
- **Actual Result:** To be tested.
- **Status:** Not Run

 

## TC-LOGIN-005: Login with leading or trailing spaces in username

- **Objective:** Verify how the login form handles spaces around the username.
- **Preconditions:** A test account exists.
- **Steps:**
  1. Open the login page.
  2. Enter a valid username with leading or trailing spaces.
  3. Enter the correct password.
  4. Click Login.
- **Expected Result:** The application handles the username consistently with the documented requirements.
- **Status:** Not Run


 

## Test Execution Record

| Field | Details |
|---|---|
| Test Case ID | TC-LOGIN-002 |
| Test Objective | Verify error message for incorrect password |
| Test Environment | Not specified |
| Test Date | Not executed |
| Expected Result | The application displays the expected error message |
| Actual Result | Not executed |
| Status | Not Run |
| Evidence | Not available |
| Tester Notes | Pending execution in the actual test environment |
