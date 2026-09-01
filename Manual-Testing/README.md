# Manual Testing Portfolio

This section contains examples of my manual testing approach, including test case design, functional testing, regression testing, negative testing, UI testing, and defect reporting.

## 🧪 Login Page Test Cases

### Objective

To verify that the login functionality works correctly for valid and invalid user inputs.

### Test Scenarios

| Test Case ID | Scenario                                         | Expected Result                                          |
| ------------ | ------------------------------------------------ | -------------------------------------------------------- |
| TC_LOGIN_001 | Login with valid username and password           | User should be logged in successfully                    |
| TC_LOGIN_002 | Login with invalid username and valid password   | Appropriate error message should be displayed            |
| TC_LOGIN_003 | Login with valid username and invalid password   | Appropriate error message should be displayed            |
| TC_LOGIN_004 | Login with invalid username and invalid password | Login should fail with an appropriate error message      |
| TC_LOGIN_005 | Login with blank username and password           | Required field validation should be displayed            |
| TC_LOGIN_006 | Login with blank username                        | Username validation should be displayed                  |
| TC_LOGIN_007 | Login with blank password                        | Password validation should be displayed                  |
| TC_LOGIN_008 | Verify password field masking                    | Password should be masked                                |
| TC_LOGIN_009 | Verify login button functionality                | Login button should work correctly                       |
| TC_LOGIN_010 | Verify login using Enter key                     | User should be able to submit the login form using Enter |

## 🔍 Testing Types Covered

* Functional Testing
* Positive Testing
* Negative Testing
* UI Testing
* Validation Testing
* Regression Testing

## 📌 QA Approach

For each feature, I focus on:

* Understanding the requirement
* Identifying positive and negative scenarios
* Designing clear and reusable test cases
* Validating expected vs. actual behavior
* Identifying and reporting defects
* Retesting fixes
* Performing regression testing where required
