# API-TESTING-WITH-POSTMAN

COMPANY: CODTECH IT SOLUTIONS

NAME: PRAVEENKUMAR B

INTERN ID: CT04DG3191

DOMAIN: SOFTWARE TESTING

DURATION: 4 WEEKS

MENTOR: NEELA SANTOSH

DESCRIPTION : This project focuses on performing API testing using Postman, a widely-used tool for testing, documenting, and monitoring RESTful APIs. The primary goal is to validate core functionalities of a web application's backend APIs, specifically targeting critical operations such as user authentication and data retrieval. Ensuring that these APIs function as intended is essential for both the security and usability of the application.

This project uses Postman to automate and streamline the API testing process. Postman offers an intuitive interface for constructing requests, sending them to target endpoints, and analyzing responses. It also provides advanced features like scripting, test automation, environment management, and collection runners, making it suitable for both manual and automated testing scenarios.

Objectives: To perform comprehensive testing of RESTful APIs using Postman.

To verify API functionalities related to user authentication, including login and token validation.

To test data retrieval endpoints to ensure accurate and consistent results.

To validate HTTP methods, status codes, headers, and response payloads.

To automate API tests and organize them into test collections for reuse and scalability.

Scope: The scope of this project includes functional testing of RESTful APIs exposed by a web application. Key areas of focus include authentication mechanisms (e.g., token-based login) and data retrieval operations (e.g., GET endpoints returning user data, product information, etc.). The testing will verify request-response behavior, authorization headers, and data consistency. Load testing, security testing, and performance optimization are outside the scope of this project.

Tools and Technologies Used: Postman: For API request creation, testing, automation, and report generation.

JavaScript: For scripting test assertions within Postman.

RESTful API Services: The backend endpoints under test, typically implemented in frameworks like Node.js, Spring Boot, or Django.

JSON: The standard data format for requests and responses.

Authentication Tokens: Such as JWT (JSON Web Token) or OAuth 2.0 tokens for secure access control.

Methodology: Requirement Analysis: Understand the API specification through documentation or Swagger/OpenAPI definitions.

Environment Setup: Configure variables for different environments (e.g., development, staging) in Postman for seamless switching.

Authentication Testing:

Send login requests with valid and invalid credentials.

Capture and validate authentication tokens.

Test token expiration and refresh scenarios (if applicable).

Data Retrieval Testing:

Use GET requests to fetch records from endpoints.

Validate response structure, data accuracy, and HTTP status codes.

Test filtering, sorting, and pagination parameters (if supported).

Assertions and Automation:

Write JavaScript-based assertions to validate response codes, headers, and payload values.

Organize requests into collections and use the Collection Runner for batch execution.

Reporting and Documentation:

Generate test reports using Newman (Postman's CLI tool) for integration with CI/CD pipelines.

Document test cases, test data, and results.

Deliverables: A complete Postman collection covering authentication and data retrieval tests.

Environment configurations and variables for flexible testing.

A test report detailing test outcomes, failed cases, and observations.

Documentation including the project objective, methodology, and summary of findings.

Expected Outcomes: By the end of the project, the APIs under test will be thoroughly validated for their intended functionality. The authentication mechanisms will be verified to prevent unauthorized access, and the data retrieval endpoints will be tested for correctness and consistency. Additionally, reusable and maintainable test collections will be created for future regression testing or integration with DevOps workflows.
