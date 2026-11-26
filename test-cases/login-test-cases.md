# Login Module — Test Cases

## 1. Module Information

**Application:** SauceDemo

**Module:** Login

**Testing Type:** Functional Testing

**Priority:** High

**Test Environment:** Google Chrome

## 2. Test Cases

### TC-LOGIN-001: Login with valid credentials

**Priority:** High

**Preconditions:**
- Login page is opened.
- Valid user credentials are available.

**Test Data:**
- Username: standard_user
- Password: secret_sauce

**Steps:**
1. Enter a valid username.
2. Enter a valid password.
3. Click the Login button.

**Expected Result:**
The user is successfully authenticated and redirected to the Products page.

**Execution Status:** PASS (Executed)

---

### TC-LOGIN-002: Login with invalid username

**Priority:** High

**Test Data:**
- Username: invalid_user
- Password: secret_sauce

**Steps:**
1. Enter an invalid username.
2. Enter a valid password.
3. Click Login.

**Expected Result:**
The application displays an authentication error message.

**Execution Status:** PASS (Executed)

---

### TC-LOGIN-003: Login with invalid password

**Priority:** High

**Test Data:**
- Username: standard_user
- Password: wrong_password

**Steps:**
1. Enter a valid username.
2. Enter an invalid password.
3. Click Login.

**Expected Result:**
The application displays an authentication error message.

**Execution Status:** PASS (Executed)

---

### TC-LOGIN-004: Login with empty username

**Priority:** High

**Steps:**
1. Leave the username field empty.
2. Enter a password.
3. Click Login.

**Expected Result:**
The application displays a validation message indicating that the username is required.

**Execution Status:** PASS (Executed)

---

### TC-LOGIN-005: Login with empty password

**Priority:** High

**Steps:**
1. Enter a valid username.
2. Leave the password field empty.
3. Click Login.

**Expected Result:**
The application displays a validation message indicating that the password is required.

**Execution Status:** PASS (Executed)

---

### TC-LOGIN-006: Login with both fields empty

**Priority:** High

**Steps:**
1. Leave both fields empty.
2. Click Login.

**Expected Result:**
The application displays a validation message indicating that the username and password are required.

**Execution Status:** PASS (Executed)

---

### TC-LOGIN-007: Login with leading spaces in username

**Priority:** Medium

**Steps:**
1. Enter a username with leading spaces.
2. Enter a valid password.
3. Click Login.

**Expected Result:**
The application rejects the authentication attempt if the username contains leading spaces.

**Execution Status:** PASS (Executed)

---

### TC-LOGIN-008: Login with trailing spaces in username

**Priority:** Medium

**Steps:**
1. Enter a username with trailing spaces.
2. Enter a valid password.
3. Click Login.

**Expected Result:**
The application rejects the authentication attempt if the username contains trailing spaces.

**Execution Status:** PASS (Executed)

---

### TC-LOGIN-009: Login with non-existing user

**Priority:** High

**Steps:**
1. Enter a username that does not exist.
2. Enter any password.
3. Click Login.

**Expected Result:**
The application displays an authentication error message.

**Execution Status:** PASS (Executed)

---

### TC-LOGIN-010: Logout and login again

**Priority:** High

**Preconditions:**
- User is successfully logged in.

**Steps:**
1. Open the application menu.
2. Click Logout.
3. Verify that the Login page is displayed.
4. Enter valid credentials.
5. Click Login.

**Expected Result:**
The user is logged out successfully and can authenticate again using valid credentials.

**Execution Status:** PASS (Executed)

---

### TC-LOGIN-011: Verify password masking

**Priority:** Medium

**Steps:**
1. Enter a password in the Password field.
2. Observe how the password is displayed.

**Expected Result:**
The password is masked and is not displayed as plain text.

**Execution Status:** NOT EXECUTED

---

### TC-LOGIN-012: Verify login form UI

**Priority:** Low

**Steps:**
1. Open the Login page.
2. Inspect the Username field.
3. Inspect the Password field.
4. Inspect the Login button.

**Expected Result:**
All login form elements are displayed correctly and are properly aligned.

**Execution Status:** NOT EXECUTED

---

### TC-LOGIN-013: Verify error message behavior

**Priority:** Medium

**Steps:**
1. Enter invalid credentials.
2. Click Login.
3. Observe the error message.
4. Correct the credentials.
5. Try logging in again.

**Expected Result:**
The error message is displayed for invalid credentials and disappears or updates appropriately after a successful login attempt.

**Execution Status:** NOT EXECUTED

---

### TC-LOGIN-014: Verify login after page refresh

**Priority:** Medium

**Steps:**
1. Log in successfully.
2. Refresh the browser page.
3. Observe the application state.

**Expected Result:**
The application handles the refreshed page according to its session behavior without unexpected errors.

**Execution Status:** NOT EXECUTED

---

### TC-LOGIN-015: Verify navigation after logout

**Priority:** Medium

**Preconditions:**
- User is logged in.

**Steps:**
1. Log out.
2. Use the browser Back button.
3. Observe the displayed page.

**Expected Result:**
The application does not allow unauthorized access to protected functionality after logout.

**Execution Status:** NOT EXECUTED

## 3. Test Execution Summary

| Status | Count |
|---|---:|
| PASS | 10 |
| FAIL | 0 |
| NOT EXECUTED | 5 |
| Total | 15 |

**Note:** Execution statuses reflect the available testing observations. The remaining test cases require execution.
