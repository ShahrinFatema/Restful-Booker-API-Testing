# RESTful Booker API Testing

## Project Overview
This project focuses on testing the RESTful Booker API using Postman to verify endpoint functionality, validate API responses, and ensure expected behavior across different HTTP methods. The testing covered authentication, CRUD operations, response validation, and automated assertions using JavaScript.
### Newman Test Execution Report
The API test collection was executed using Newman, and an HTML report was generated to visualize the test execution results.

**[View Newman HTML Test Report](YOUR-GITHUB-PAGES-REPORT-URL)**

## Testing Scope

### 1. Authentication Testing
- Generated authentication tokens using valid credentials.
- Verified authentication behavior with invalid credentials.
- Tested empty username and password fields.
- Tested requests with invalid JSON payloads.
- Validated authentication response messages and status codes.
- Checked error handling for invalid and incomplete requests.

### 2. CRUD Operations & Authorization Testing
- **Create (POST):** Created booking records and tested booking creation with expired and invalid authentication tokens.
- **Read (GET):** Retrieved booking details using valid booking IDs and tested requests with non-existing booking IDs to validate error handling.
- **Update (PUT):** Updated existing booking records and tested requests without providing an authentication token.
- **Partial Update (PATCH):** Modified specific booking fields and validated updated response data.
- **Delete (DELETE):** Tested booking deletion and verified the API response.

### Authorization & Negative Testing
- Tested requests with invalid and expired authentication tokens.
- Verified access control for protected endpoints.
- Tested update operations without an authentication token.
- Validated appropriate error responses for unauthorized requests.

### 3. Response Validation
- Validated HTTP status codes.
- Verified response body data against expected values.
- Checked error responses for negative scenarios.
- Used JavaScript assertions to validate API behavior.
- Stored response data in variables and reused it in subsequent requests.

## Tools & Technologies
| Tool / Technology | Purpose |
|---|---|
| Postman | API request execution and validation |
| JavaScript | Writing test scripts and assertions |
| REST API | HTTP methods and endpoint testing |
| Newman | API request execution and generate html report |

## Key Testing Activities
- Executed API requests using different HTTP methods.
- Validated positive and negative test scenarios.
- Implemented response assertions using Postman's test scripts.
- Managed environment and collection variables.
- Performed response data extraction and variable chaining.
- Verified authentication and error handling.

## Project Deliverables
- Postman Collection (JSON)
- API Test Scripts and Assertions
- Environment Configuration (sanitized)
- Newman Report (HTML)

## Project Outcome
Developed practical experience in REST API testing, authentication, CRUD operations, response validation, JavaScript assertions, and dynamic data handling using Postman.
---
**Project Type:** API Testing  
**Application Under Test:** RESTful Booker  
**Testing Tool:** Postman  
**Status:** Completed
