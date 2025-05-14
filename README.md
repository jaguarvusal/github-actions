name: GitHub Actions CI/CD Setup  
description: |
  This project sets up a Continuous Integration and Continuous Deployment (CI/CD) pipeline using GitHub Actions for automated testing and deployment. The pipeline runs component tests with Cypress when a Pull Request (PR) is made to the `develop` branch and automatically deploys the application to Render when changes are merged from `develop` to the `main` branch. The project includes two separate GitHub Actions YAML files: one for testing and one for deployment.  


license: MIT License

---

table_of_contents:
  - Features
  - Installation
  - Technologies Used
  - License

---

features:
  - GitHub Actions for Testing:
      - Cypress Component Testing:
          - Runs automated component tests using Cypress.
          - Executes when a Pull Request is made to the `develop` branch.
          - Ensures that all components are working as expected before merging changes.
  - GitHub Actions for Deployment:
      - Automated Deployment to Render:
          - Deploys the app to Render when changes are merged from `develop` to `main`.
          - Ensures a smooth, continuous deployment process.

---

installation:
  - Clone the repository:
      command: |
        git clone https://github.com/your-username/github-actions-cicd.git
  - Navigate into the project directory:
      command: |
        cd github-actions-cicd
  - Install dependencies:
      command: |
        npm install
  - Set up Render deployment token:
      description: |
        Obtain your deployment token from Render and add it to your `deploy.yml` file as `your-deploy-token-here`.

---

technologies_used:
  - GitHub Actions (CI/CD)
  - Cypress (Testing)
  - Render (Deployment Platform)

---

license: MIT License
