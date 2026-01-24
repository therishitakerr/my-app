# Sample React App – CI/CD Test Automation Demo

This repository demonstrates **automated UI testing using Playwright executed via CI/CD with GitHub Actions**.

On every push or pull request, a GitHub Actions workflow builds the React application and runs Playwright test scripts to validate the UI automatically.

---

## Purpose

- Demonstrate **end-to-end test automation**
- Integrate **Playwright tests** with a **React application**
- Showcase **CI/CD execution using GitHub Actions**

---

## Tech Stack

- React
- Playwright (Java)
- TestNG
- GitHub Actions
- Node.js

---

## CI/CD Workflow

The workflow is defined in: https://github.com/therishitakerr/sample-react-app/actions/workflows/main.yml


### What it does:
1. Checks out the code
2. Sets up Node.js and Java
3. Installs dependencies
4. Builds the React application
5. Executes Playwright automated tests

The pipeline runs automatically on **push** and **pull request** events.

---

## Related Repositories

- **React App**: https://github.com/therishitakerr/sample-react-app  
- **Playwright Test Scripts**: https://github.com/therishitakerr/sample-playwright-test-scripts  

---

## Outcome

- Automated validation of UI flows
- Early detection of regressions
- Consistent and reliable test execution via CI/CD

---
