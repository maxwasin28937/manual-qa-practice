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


## TC-LOGIN-004: Login with empty password
- **Objective:** Verify that login is prevented when the password is empty.
- **Precondition:** A registered user exists.
- **Test Steps:**
  1. Open the Login page.
  2. Enter a registered email.
  3. Leave the password field empty.
  4. Click the Login button.
- **Expected Result:** Login is prevented and the appropriate validation message is displayed.
- **Actual Result:** To be tested.
- **Status:** Not Run
