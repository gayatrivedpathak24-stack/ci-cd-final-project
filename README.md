
# CI/CD Final Project

## Project Overview
This repository contains the application code, automated tests, and CI/CD pipeline configuration for the **Continuous Integration and Continuous Delivery** course final project.

## Features
* **Automated Linting & Testing:** Runs code quality checks and unit tests automatically on every push and pull request.
* **Containerization:** Builds a Docker image for the application service.
* **Continuous Deployment:** Automates deployment to the target cluster once all checks pass.

## Repository Structure
* `service/` - Core application source code
* `tests/` - Unit and integration test suites
* `.github/workflows/` - GitHub Actions CI/CD workflow definitions (or `.tekton/` if using Tekton)

## Getting Started
1. Clone the repository:
   ```bash
   git clone https://github.com<your-username>/<your-repo-name>.git
   ```
2. Navigate into the project directory and run the test suite locally before pushing changes.

