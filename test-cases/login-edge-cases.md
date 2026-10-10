# Login - Additional Negative Test Cases

**Application:** Practice Test Automation  
**Page:** https://practicetestautomation.com/practice-test-login/  
**Test type:** Manual functional testing

## Objective

Verify how the login form handles empty and whitespace-only credentials.

These scenarios extend the existing login test coverage with additional negative input cases. All four tests were executed manually.

## Test data

Valid username: `student`  
Valid password: `Password123`  
Whitespace-only username: exactly three spaces ("   ")

---

### TC-LOGIN-004 — Empty username

**Preconditions:** Login page is available.

**Steps:**

1. Open the login page.
2. Leave the Username field empty.
3. Enter `Password123` in the Password field.
4. Click Submit.
5. Observe the result.

**Expected result:**

- Login is rejected.
- User remains unauthenticated.
- Successful login page is not displayed.

**Actual result:**

- Login was rejected.
- Error message "Your username is invalid!" was displayed.

**Status:** PASS

---

### TC-LOGIN-005 — Empty password

**Preconditions:** Login page is available.

**Steps:**

1. Open the login page.
2. Enter `student` in the Username field.
3. Leave the Password field empty.
4. Click Submit.
5. Observe the result.

**Expected result:**

- Login is rejected.
- User remains unauthenticated.
- Successful login page is not displayed.

**Actual result:**

- Login was rejected.
- Error message "Your password is invalid!" was displayed.

**Status:** PASS

---

### TC-LOGIN-006 — Both fields empty

**Preconditions:** Login page is available.

**Steps:**

1. Open the login page.
2. Leave the Username field empty.
3. Leave the Password field empty.
4. Click Submit.
5. Observe the result.

**Expected result:**

- Login is rejected.
- User remains unauthenticated.
- Successful login page is not displayed.

**Actual result:**

- Login was rejected.
- Error message "Your username is invalid!" was displayed.

**Status:** PASS

---

### TC-LOGIN-007 — Whitespace-only username

**Preconditions:** Login page is available.

**Steps:**

1. Open the login page.
2. Enter exactly three spaces ("   ") in the Username field.
3. Enter `Password123` in the Password field.
4. Click Submit.
5. Observe the result.

**Expected result:**

- Login is rejected.
- User remains unauthenticated.
- Successful login page is not displayed.

**Actual result:**

- Login was rejected.
- Error message "Your username is invalid!" was displayed.

**Status:** PASS

## Execution summary

- Test cases executed: 4
- Passed: 4
- Failed: 0
