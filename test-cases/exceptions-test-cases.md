# Dynamic Elements Test Cases

**Application:** Practice Test Automation  
**Page:** https://practicetestautomation.com/practice-test-exceptions/  
**Test type:** Manual functional testing

---

### TC-EXC-001 — Add a second input row

**Preconditions:** Exceptions page is available.

**Steps:**

1. Open the Exceptions page.
2. Click Add.
3. Wait for the second row to appear.

**Expected result:**

- Row 2 input field is displayed after the loading period.

**Actual result:**

- Row 2 appeared after the loading period and the input field was displayed.

**Status:** Pass  
**Automation:** Implemented in `selenium-tests`

---

### TC-EXC-002 — Enter and save a value in Row 2

**Preconditions:** Exceptions page is available.

**Steps:**

1. Open the page.
2. Click Add.
3. Wait for Row 2 to appear.
4. Enter `sushi` into the Row 2 input field.
5. Click Save for Row 2.

**Expected result:**

- The value is saved.
- Confirmation message `Row 2 was saved` is displayed.

**Actual result:**

- The value was accepted and saved.
- Confirmation message `Row 2 was saved` was displayed.

**Status:** Pass  
**Automation:** Implemented in `selenium-tests`

---

### TC-EXC-003 — Edit and save the value in Row 1

**Preconditions:** Exceptions page is available.

**Steps:**

1. Open the page.
2. Click Edit for Row 1.
3. Clear the existing value.
4. Enter `Sushi`.
5. Click Save.

**Expected result:**

- The input becomes editable.
- The new value is saved.
- Confirmation message `Row 1 was saved` is displayed.

**Actual result:**

- Row 1 became editable after clicking Edit.
- The new value was entered and saved.
- Confirmation message `Row 1 was saved` was displayed.

**Status:** Pass  
**Automation:** Scenario exists in `selenium-tests`; the current automated test needs cleanup because of a duplicate test name

---

### TC-EXC-004 — Instructions disappear after adding Row 2

**Preconditions:** Instructions are displayed when the page is opened.

**Steps:**

1. Open the page.
2. Confirm the instructions are initially present.
3. Click Add.
4. Wait for Row 2 to appear.

**Expected result:**

- The instructions are no longer displayed after Row 2 is added.

**Actual result:**

- The instructions were removed after Row 2 was added.

**Status:** Pass  
**Automation:** Implemented in `selenium-tests`

---

### TC-EXC-005 — Row 2 loading delay

**Preconditions:** Exceptions page is available.

**Steps:**

1. Open the page.
2. Click Add.
3. Observe the loading period before Row 2 becomes available.

**Expected result:**

- Row 2 does not appear immediately.
- Row 2 appears after the page loading delay.

**Actual result:**

- Row 2 was not immediately available.
- It appeared after the expected loading period.

**Status:** Pass  
**Automation:** The current timeout example in `selenium-tests` needs improvement to represent this scenario correctly
