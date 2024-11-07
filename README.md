![CI - Cypress Tests](https://img.shields.io/github/actions/workflow/status/RubenDguez/ci-cd-github/main.yaml?label=CI%20-%20Cypress%20Tests&style=flat-square)
![CD - Deploy to Render](https://img.shields.io/github/actions/workflow/status/RubenDguez/ci-cd-github/deploy.yaml?label=CD%20-%20Deploy%20to%20Render&style=flat-square)
![License](https://img.shields.io/github/license/RubenDguez/ci-cd-github?style=flat-square)

# Full-Stack Application with CI/CD Pipeline
This project demonstrates the integration of a Continuous Integration (CI) and Continuous Deployment (CD) pipeline using GitHub Actions. The application runs Cypress tests on every pull request (PR) to the `develop` branch and automatically deploys to Render when changes are merged into the `main` branch.

## Overview

This project integrates a full-stack web application with a CI/CD pipeline that uses GitHub Actions to automate testing and deployment:
- **Cypress Tests**: Automatically runs on pull requests to the `develop` branch to ensure all code passes functional tests before merging.
- **Automated Deployment**: Deploys the latest code to Render whenever changes are merged into the `main` branch, ensuring the live application is always up-to-date.

## Features

- **Cypress Component Testing** on pull requests to the `develop` branch.
- **Continuous Deployment to Render** on merges to the `main` branch.
- **Full-Stack Application** with an automated CI/CD pipeline for streamlined development and deployment.

## Technologies Used

- **Node.js** for running the application.
- **Cypress** for testing the application.
- **GitHub Actions** for CI/CD pipeline automation.
- **Render** for hosting the application.
- **MongoDB** as the database.

### Installation

1. Clone this repository to your local machine:
   ```bash
   git clone https://github.com/YourUsername/ci-cd-github.git
   ```
2.	Navigate into the project folder:
    ```bash
    cd ci-cd-github
    ```
3. Install dependencies:
    ```bash
    npm install
    ```
4. Make sure that the required Render commands are working properly locally:
    ```bash
    npm run render-build
    npm run start
    ```
5. Run component test locally:
    ```bash
    npm run test-component
    ```

### CI/CD Configuration

This project requires two GitHub Actions workflows:

- **Cypress Tests Workflow**: Configured to run Cypress tests whenever a pull request is created targeting the `develop` branch, ensuring all functional tests are passed before any code merges.
  
- **Deploy to Render Workflow**: Configured to automatically deploy the application to Render whenever changes are merged into the `main` branch, using the Deploy Hook URL from Render.

## Contributing

To contribute to this project:

1. Fork the repository.
2. Create a new branch for your feature or bugfix.
3. Make your changes and commit them with clear messages.
4. Push your branch and create a pull request to the `develop` branch.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## Questions

- If you have further questions, you can contact me at: argenis.dominguez@hotmail.com
- This is my GitHub profile: [RubenDguez](https://github.com/RubenDguez)
