# 🛒 Demo E2E Automation Framework & API Testing

This repository contains an End-to-End (E2E) test automation framework for the SauceDemo e-commerce platform. 
It is designed following industry standards to ensure scalability, easy maintenance, and Continuous Integration (CI) readiness.

# 🛠️Tech Stack
* **Test Framework:** Cypress (UI & API Testing)
* **API Testing Tool:** Postman + Newman (CLI Runner)
* **Language:** JavaScript
* **Data Generation:** Faker.js (Dynamic data insertion)
* **Reporting:** Cypress Mochawesome Reporter & Postman HTML Reports
* **CI/CD:** GitHub Actions (Automated workflow on Push/PR)

# 🏗️ Architecture & Design Patterns
The project implements the best practices in QA Automation:

* **Page Object Model (POM):** Complete separation between page logic and test scripts.
* **API Testing & Postman Integration:**

-Functional testing of RESTful services using cy.request() for internal Cypress flows.
-Independent API validation suites using Postman collections for comprehensive endpoint verification.
* **-Newman Execution:** Automated collection runs within the CI pipeline for rapid feedback.
* **-Hybrid Testing Flow:** Leveraging API calls to set up or tear down test data, significantly reducing UI execution time.
* **-CI/CD Pipeline:** Fully integrated into GitHub Actions, executing UI (Cypress) and API (Newman) suites on every Pull Request.
