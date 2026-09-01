# Bug Reports

This section demonstrates my approach to identifying, documenting, and tracking software defects with clear reproduction steps, expected results, actual results, severity, and priority.

## 🐞 Sample Bug Report

### BUG-LOGIN-001 — Login button remains disabled after entering valid credentials

| Field                  | Details                                                                                                         |
| ---------------------- | --------------------------------------------------------------------------------------------------------------- |
| **Bug ID**             | BUG-LOGIN-001                                                                                                   |
| **Module**             | Login                                                                                                           |
| **Title**              | Login button remains disabled after entering valid credentials                                                  |
| **Severity**           | High                                                                                                            |
| **Priority**           | High                                                                                                            |
| **Environment**        | Web Application                                                                                                 |
| **Precondition**       | User is on the Login page                                                                                       |
| **Steps to Reproduce** | 1. Open the Login page<br>2. Enter a valid username<br>3. Enter a valid password<br>4. Observe the Login button |
| **Expected Result**    | Login button should be enabled and the user should be able to log in successfully                               |
| **Actual Result**      | Login button remains disabled even after valid credentials are entered                                          |
| **Status**             | Open                                                                                                            |

### 📌 Testing Approach

While reporting defects, I ensure that:

* Steps to reproduce are clear and easy to follow
* Expected and actual results are clearly documented
* Severity and priority are assigned appropriately
* Required test data and environment details are mentioned
* Defects are tracked through their complete lifecycle
* Fixed defects are retested
* Regression testing is performed when required

