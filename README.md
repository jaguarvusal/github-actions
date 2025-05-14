# GitHub Actions CI/CD Setup  
**Live Demo: N/A (CI/CD Pipeline)**

This project sets up a Continuous Integration and Continuous Deployment (CI/CD) pipeline using GitHub Actions for automated testing and deployment. The pipeline runs component tests with Cypress when a Pull Request (PR) is made to the `develop` branch and automatically deploys the application to Render when changes are merged from `develop` to the `main` branch. The project includes two separate GitHub Actions YAML files: one for testing and one for deployment.  
<img width="1430" alt="CI/CD Pipeline Screenshot" src="https://github.com/user-attachments/assets/ci-cd-pipeline-image" />

---

## License  
This project is licensed under the MIT License.

---

## Table of Contents  
- [Features](#features)  
- [Installation](#installation)  
- [Technologies Used](#technologies-used)  
- [License](#license)  

---

## Features  

### GitHub Actions for Testing:  
- **Cypress Component Testing**: 
  - Runs automated component tests using Cypress.
  - Executes when a Pull Request is made to the `develop` branch.
  - Ensures that all components are working as expected before merging changes.

### GitHub Actions for Deployment:  
- **Automated Deployment to Render**: 
  - Deploys the app to Render when changes are merged from `develop` to `main`.
  - Ensures a smooth, continuous deployment process.

---

## Installation  

### Clone the repository:
git clone https://github.com/your-username/github-actions-cicd.git

### Navigate into the project directory:
cd github-actions-cicd

### Install dependencies:
npm install

### Set up Render deployment token:
### Obtain your deployment token from Render and add it to your deploy.yml file as your-deploy-token-here.

## Technologies Used:
- GitHub Actions (CI/CD)
- Cypress (Testing)
- Render (Deployment Platform)

## License:
### This project is licensed under the MIT License.
