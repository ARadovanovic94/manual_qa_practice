# Manual QA Practice

This repository contains my manual testing practice and test documentation.

The test cases are based on the Practice Test Automation website, which I also use in my Selenium practice project.

## Application under test

Practice Test Automation  
https://practicetestautomation.com/

## Completed scope

The current manual testing scope covers:

- Positive and negative login scenarios
- Dynamic elements
- Editing and saving input values
- Instructions removed after a page update
- Delayed element loading

All test cases in the current scope have been executed and produced the expected result.

## Repository structure

```text
test-cases/
    login-test-cases.md
    exceptions-test-cases.md

test-execution/
    test-summary.md

bug-reports/
    README.md
```

## Testing approach

For each feature I:

1. Reviewed the expected behavior.
2. Identified the test scenarios.
3. Defined steps and expected results.
4. Executed the scenarios manually.
5. Recorded the actual result and status.
6. Checked whether any reproducible defect should be reported.

## Manual and automation testing

Some scenarios from this project are also implemented in my Selenium WebDriver practice repository:

https://github.com/ARadovanovic94/selenium-tests

This lets me practice the same functionality from both sides: manual test design and execution first, then automation for suitable repeatable scenarios.

## Result

- Test cases executed: 8
- Passed: 8
- Failed: 0
- Blocked: 0
- Defects found: 0

See `test-execution/test-summary.md` for the execution summary.
