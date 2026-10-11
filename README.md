[![DevOps CI/CD Pipeline](https://github.com/Nyanners31/devops-automation-demo/actions/workflows/ci-cd.yml/badge.svg)](https://github.com/Nyanners31/devops-automation-demo/actions/workflows/ci-cd.yml)



# DevOps CI/CD Automation Demo

![CI/CD Pipeline](https://github.com/Nyanners31/devops-automation-demo/actions/workflows/ci-cd.yml/badge.svg)

An automated continuous integration and continuous deployment pipeline built with **GitHub Actions**.

## Pipeline Architecture
- **Linting & Code Quality**: Validates Python syntax and enforces PEP8 standards using `flake8`.
- **Containerization**: Configures isolated environments using `Docker Buildx` to build and tag lightweight production container images.
- **Staging Deployment**: Simulates an automated staging release gate triggered on pushes to the `main` branch.

## Tech Stack
- **CI/CD Platform**: GitHub Actions
- **Containerization**: Docker Buildx
- **Linter**: Flake8 / Python 3.10
