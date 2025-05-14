# CI/CD Deployment Setup  
**GitHub Actions for Cypress Tests & Render Deployment**

This repository demonstrates a CI/CD pipeline using GitHub Actions to automate testing and deployment. Cypress component tests run automatically on every Pull Request to the `develop` branch. When changes are merged from `develop` to `main`, the application is automatically deployed to [Render]https://github-actions-3asc.onrender.com.

<img width="1426" alt="Screenshot 2025-05-14 at 12 18 46 PM" src="https://github.com/user-attachments/assets/1e92a4f8-f4ff-419f-b829-435b343ae12e" />


---

## License  
This project is licensed under the MIT License.

---

## Table of Contents  
- [Features](#features)  
- [Installation](#installation)  
- [Technologies Used](#technologies-used)  
- [CI/CD Configuration](#cicd-configuration)  
- [License](#license)  

---

## Features  

### GitHub Actions Test Workflow  
- Triggered on Pull Requests to the `develop` branch  
- Runs Cypress component tests  
- Ensures code quality and prevents breaking changes  

### GitHub Actions Deploy Workflow  
- Triggered when `develop` is merged into `main`  
- Deploys the latest code to Render automatically  
- Uses Render Deploy Hook with a secure API key  

---

## Installation  

**Clone the repository:**  
```bash
git clone https://github.com/your-username/your-repo-name.git
```

**Navigate into the project directory:**  
```bash
cd your-repo-name
```

**Install dependencies:**  
```bash
npm install
```

**Set environment variables:**  
Create a `.env` file in the root directory if required by your project.

---

## Technologies Used  

- GitHub Actions (CI/CD)  
- Cypress (Component Testing)  
- Render (Hosting & Deployment)  
- Node.js (Optional, depending on project)  

---

## CI/CD Configuration  

### ✅ Test Workflow  
Runs Cypress component tests on **Pull Requests to the `develop` branch**.

---

### 🚀 Deploy Workflow  
Deploys to Render **when `develop` is merged into `main`**.

> Add your Render Deploy hook to github repo secret.

---

## License  
This project is licensed under the MIT License.
