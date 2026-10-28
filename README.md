# DevOps Capstone Project

[![CI Build](https://github.com/ArchiniPatil/devops-capstone-project/actions/workflows/ci-build.yaml/badge.svg)](https://github.com/ArchiniPatil/devops-capstone-project/actions/workflows/ci-build.yaml)

This repository contains the completed Customer Accounts REST API microservice as part of the DevOps Capstone Project.

## Overview

This microservice provides complete RESTful capabilities for managing customer account resources, including creating, reading, updating, listing, and deleting accounts. It is containerized using Docker, deployed to Kubernetes, and features continuous integration and automated deployment pipelines.

## Project Features

- **RESTful API**: Full CRUD support for account management.
- **Security**: Hardened with Flask-Talisman security headers and CORS policy configurations.
- **Continuous Integration**: GitHub Actions workflow running automated Flake8 linting and unit test suites with code coverage metrics.
- **Containerization**: Optimized Docker image configured for non-root execution.
- **Deployment**: Automated Tekton CD pipeline for Kubernetes deployment.
