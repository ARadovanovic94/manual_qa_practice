# Login Test Cases

**Application:** Practice Test Automation  
**Page:** https://practicetestautomation.com/practice-test-login/  
**Test type:** Manual functional testing

## Test data

Valid username: `student`  
Valid password: `Password123`

---

### TC-LOGIN-001 — Successful login with valid credentials

**Preconditions:** Login page is available.

**Steps:**

1. Open the login page.
2. Enter `student` in the Username field.
3. Enter `Password123` in the Password field.
4. Click Submit.

**Expected result:**

- User is redirected to the logged-in page.
- The page confirms successful login.
- Log out button is displayed.

**Actual result:**

- Login was successful.
- User was redirected to the logged-in page.
- Successful login text and Log out button were displayed.

**Status:** Pass  
**Automation:** Implemented in `selenium-tests`

---

### TC-LOGIN-002 — Login with invalid username

**Preconditions:** Login page is available.

**Steps:**

1. Open the login page.
2. Enter `incorrectUser` in the Username field.
3. Enter `Password123` in the Password field.
4. Click Submit.

**Expected result:**

- Login is rejected.
- Error message `Your username is invalid!` is displayed.

**Actual result:**

- Login was rejected.
- Error message `Your username is invalid!` was displayed.

**Status:** Pass  
**Automation:** Implemented in `selenium-tests`

---

### TC-LOGIN-003 — Login with invalid password

**Preconditions:** Login page is available.

**Steps:**

1. Open the login page.
2. Enter `student` in the Username field.
3. Enter `incorrectPassword` in the Password field.
4. Click Submit.

**Expected result:**

- Login is rejected.
- Error message `Your password is invalid!` is displayed.

**Actual result:**

- Login was rejected.
- Error message `Your password is invalid!` was displayed.

**Status:** Pass  
**Automation:** Implemented in `selenium-tests`
