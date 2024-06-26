# GCP DevOps Project
## Sprint 01: Initial Setup and Simple Docker Integration

### Overview
This document outlines the steps to create a new GitHub repository, set up the repository according to company best practices, implement branch protection, write a simple Docker image, test the code locally, and push the code to the GitHub repository.

### 1. Creating a New GitHub Repository
- Navigate to [GitHub](https://github.com/) and sign in.
- Click on the "+" icon in the upper right corner and select **New repository**.
- Name your repository `GCP_DevOps_Project`.
- Choose the visibility (public or private).
- Initialize the repository with a README if required.

### 2. Setting Up the Repository According to Company Best Practices
- **Add `.gitignore`**: Create a `.gitignore` file suitable for Python/Node.js or any other stack you are using.
- **License**: Add a `LICENSE` file according to the company's policy on open source contributions.
- **Contribution Guidelines**: Include a `CONTRIBUTING.md` file to guide other developers on how to contribute to the repository.

### 3. Branch Protection
- Go to the repository settings on GitHub.
- Under the **Branches** section, click on **Add rule**.
- Enter `main` in the branch name pattern.
- Check the following options:
  - **Require pull request reviews before merging**: Choose how many reviewers are required.
  - **Require status checks to pass before merging**: Enable status checks if necessary.
  - **Include administrators**: Enforce all configured restrictions for administrators.
  - **Restrict who can push to matching branches**: Optionally, set who can push to the main branch.

### 4. Writing a Simple Docker Image
- Create a `Dockerfile` in the root of your project
  
