# CI/CD Final Project

**Project name:** ci-cd-final-project
**Author:** Ssshtea

A Python Flask application with a complete CI/CD pipeline using GitHub Actions, Tekton, and OpenShift Pipelines.

## Pipeline overview
- GitHub Actions: lint with flake8, run unit tests with nose
- Tekton: cleanup, clone, flake8, nose, and build tasks
- OpenShift: deployment of the application
