# API Testing Portfolio

This section demonstrates my understanding and practical approach to API testing using Swagger, including request/response validation, HTTP status code verification, positive and negative testing, and business logic validation.

## 🔌 API Testing Areas

* Request validation
* Response validation
* HTTP status code validation
* Positive API testing
* Negative API testing
* Mandatory field validation
* Invalid input validation
* Business logic validation
* Response data verification
* Error message validation

## 🧪 Sample API Test Scenarios

| Test Case ID | Test Scenario                                  | Expected Result                                         |
| ------------ | ---------------------------------------------- | ------------------------------------------------------- |
| API_TC_001   | Send request with valid data                   | API should return a successful response                 |
| API_TC_002   | Send request with missing mandatory field      | API should return appropriate validation error          |
| API_TC_003   | Send request with invalid data                 | API should reject the request with an appropriate error |
| API_TC_004   | Verify HTTP status code for successful request | Correct success status code should be returned          |
| API_TC_005   | Verify HTTP status code for invalid request    | Appropriate client error status code should be returned |
| API_TC_006   | Verify response body structure                 | Response should contain expected fields and data        |
| API_TC_007   | Verify response for non-existing record        | API should return an appropriate response               |
| API_TC_008   | Verify data after successful API operation     | Backend data should be updated correctly                |

## 🔍 Request & Response Validation

During API testing, I validate:

### Request

* HTTP method
* Request parameters
* Request body
* Required fields
* Valid and invalid input values

### Response

* HTTP status code
* Response body
* Response fields
* Data accuracy
* Error messages
* Business rules

## 🛠️ Tool Used

**Swagger** — Used for sending API requests, validating responses, and testing different positive and negative scenarios.

## 📋 QA Approach

**Understand API Requirement → Identify Scenarios → Send Request → Validate Response → Verify Status Code → Validate Business Logic → Verify Backend Data**
