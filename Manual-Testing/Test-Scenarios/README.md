# Test Scenarios

This section demonstrates my approach to identifying high-level test scenarios before designing detailed test cases.

## 🔐 Login Module

| Scenario ID  | Test Scenario                                        |
| ------------ | ---------------------------------------------------- |
| TS_LOGIN_001 | Verify login with valid credentials                  |
| TS_LOGIN_002 | Verify login with invalid username                   |
| TS_LOGIN_003 | Verify login with invalid password                   |
| TS_LOGIN_004 | Verify login with both invalid credentials           |
| TS_LOGIN_005 | Verify validation for blank username                 |
| TS_LOGIN_006 | Verify validation for blank password                 |
| TS_LOGIN_007 | Verify validation when both fields are blank         |
| TS_LOGIN_008 | Verify password masking                              |
| TS_LOGIN_009 | Verify login button behavior                         |
| TS_LOGIN_010 | Verify login using the Enter key                     |
| TS_LOGIN_011 | Verify behavior after multiple failed login attempts |
| TS_LOGIN_012 | Verify Forgot Password functionality                 |
| TS_LOGIN_013 | Verify login page UI elements                        |
| TS_LOGIN_014 | Verify login behavior after session timeout          |
| TS_LOGIN_015 | Verify login functionality across supported browsers |

## 🛒 E-Commerce Example

| Scenario ID | Test Scenario                                      |
| ----------- | -------------------------------------------------- |
| TS_CART_001 | Verify adding a product to the cart                |
| TS_CART_002 | Verify removing a product from the cart            |
| TS_CART_003 | Verify updating product quantity                   |
| TS_CART_004 | Verify cart total calculation                      |
| TS_CART_005 | Verify checkout with valid details                 |
| TS_CART_006 | Verify checkout with missing mandatory information |
| TS_CART_007 | Verify invalid payment details                     |
| TS_CART_008 | Verify order confirmation after successful payment |

## 📋 QA Approach

My general approach is:

**Requirement Analysis → Identify Scenarios → Design Test Cases → Execute Tests → Report Defects → Retest → Regression Testing**

Test scenarios are kept at a high level, while detailed test cases contain the specific steps, test data, expected results, and actual results.

