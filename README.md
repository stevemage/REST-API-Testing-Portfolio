# REST API Testing Portfolio

A hands-on REST API testing project created to demonstrate fundamental manual and automated API testing skills using Postman.

## Project Overview

The project uses the public Postman Echo API to practice HTTP request validation, JSON response assertions, negative test scenarios, response time checks, and parameterized testing.

**API under test:** https://postman-echo.com

## Tools and Technologies

- Postman
- JavaScript
- Postman test scripts and Chai assertions
- JSON
- Git and GitHub

## Implemented Test Scenarios

| Test ID | Test Scenario | Description |
|---|---|---|
| API-001 | GET Request Validation | Validates HTTP status, query parameters, and response time |
| API-005 | Missing Parameter Validation | Verifies response behavior when an optional query parameter is omitted |
| API-008 | JSON Structure Validation | Validates JSON properties and their data types |
| API-009 | Parameterized GET Request | Uses Postman Collection Variables to validate responses with different input values |

Additional manual exercises covered empty query parameters and basic negative test scenarios.

## Automated Testing

Automated checks include:

- HTTP status code validation
- JSON property existence and expected values
- JSON data type validation
- Response time threshold checks
- Missing parameter validation
- Parameterized assertions using Collection Variables

## Test Execution

The tests were executed in Postman. A Collection Runner exercise using five iterations completed with 35 passed assertions and zero failures.

Parameterized testing was also verified using two different sets of query parameter values.

## Running the Tests

1. Open the project in a compatible Postman version supporting local collection files.
2. Open the `REST API Testing Portfolio` collection.
3. Verify that Collection Variables `device` and `mode` have string values.
4. Open an individual request and click **Send**.
5. Review the automated assertions in the Postman test results.

An internet connection is required to access the Postman Echo API.

## Notes

Postman Echo is a public request-response testing service. Its behavior is not equivalent to a production application with business validation rules.

Response time thresholds in this project are illustrative test criteria, not contractual service-level requirements.

## Author

QA testing portfolio project demonstrating practical REST API testing skills.