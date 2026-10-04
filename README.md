# Manual QA Practice

This repository contains my manual testing practice and test documentation.

The current test cases are based on the Practice Test Automation website, which I also use in my Selenium practice project.

## Application under test

Practice Test Automation  
https://practicetestautomation.com/

## Current scope

The project currently covers:

- Login functionality
- Positive and negative login scenarios
- Dynamic elements
- Editing and saving input values
- Basic synchronization-related scenarios

## Repository structure

```text
test-cases/
    login-test-cases.md
    exceptions-test-cases.md

bug-reports/
    README.md
```

## Testing approach

For each feature I try to:

1. Understand the expected behavior.
2. Identify positive, negative and relevant edge cases.
3. Define clear test steps and expected results.
4. Execute the test manually.
5. Record the actual result and test status.
6. Report a defect only when unexpected behavior can be reproduced.

## Manual and automation testing

Some of the scenarios documented here are also used in my Selenium WebDriver practice project:

https://github.com/ARadovanovic94/selenium-tests

The goal is to practice the testing flow from a manual scenario to automation where automation makes sense.
