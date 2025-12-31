# DevSecOps CI Pipeline with Jenkins for Node.js

This repository demonstrates a DevSecOps-oriented CI pipeline built with Jenkins for a Node.js application. The project focuses on integrating security and quality checks early in the development lifecycle (shift-left security).

The pipeline validates code changes by installing dependencies, running automated tests, enforcing code quality standards, and preparing the application for secure containerization and deployment. Security tooling is incrementally integrated to ensure vulnerabilities are detected before reaching production.

## Key Concepts Covered
- Continuous Integration with Jenkins
- Node.js build and test automation
- DevSecOps principles and shift-left security
- Pipeline failure on quality or test violations
- Foundation for SAST, dependency scanning, and container security

## Tech Stack
- Jenkins
- Node.js
- GitHub
- Docker (planned)
- SonarQube, OWASP tools, Trivy (planned)
