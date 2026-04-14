# Project Overview
This project demonstrates a basic DevOps workflow including branching, pull requests, and issue tracking.

# Team Members & Contributions
Amna (Leader): Repository setup, Issue management, and Final Merging.
Malaika: Added Navigation Bar (Resolved Issue #1).
Tanqeen:Added Contact Section (Resolved Issue #2).
Areeba: Project Documentation and README setup (Resolved Issue #3).

# Workflow Followed
1. Created feature branches for each task.
2. Used commit messages with `fixes #issue_number` to automate issue closing.
3. Conducted Pull Request reviews before merging into the main branch.

## CI/CD Pipeline
This project uses **GitHub Actions** to automate the build and deployment process. 
Every time code is pushed to the `main` branch, a new Docker image is built and pushed to Docker Hub.

## Instructions
1. Clone the repository.
2. Build the Docker image locally: `docker build -t devops-project .`
3. Run the container: `docker run -p 80:80 devops-project`

## Changelog
- **Initial Release**: Static website files added.
- **Update**: Added Dockerfile for containerization.
- **Current Update**: Configured GitHub Actions for automated CI/CD pipeline.

- Tested by Areeba Khan
