# Jenkins-Sonarqube-Docker

This project aims to create a CI/CD pipeline that automates the software development process and ensures code quality. By integrating Jenkins, Sonarqube, and Docker, we can streamline the development workflow, enhance collaboration, and simplify the deployment of software applications.

## Table of Contents

- [Introduction](#introduction)
- [Usage](#usage)

## Introduction

The Jenkins-Sonarqube-Docker project leverages popular tools in the software development ecosystem to establish an efficient CI/CD pipeline. Here's a brief overview of each component:

- **Jenkins**: Jenkins is an open-source automation server that simplifies tasks such as building, testing, and deploying software. It provides a versatile environment for automating various stages of the development lifecycle.

- **Sonarqube**: Sonarqube is a code quality management tool that analyzes and manages code quality in software projects. It helps identify issues, such as bugs, vulnerabilities, and code smells, enabling developers to continuously improve the quality of their code.

- **Docker**: Docker is a containerization platform that allows applications to be packaged and run in isolated environments. It simplifies deployment by ensuring consistent runtime environments across different platforms, reducing dependency issues and improving portability.

Here's a brief overview of the project workflow:

1. Create an AWS EC2 instance and install Jenkins on it.
2. Set up a GitHub repository and integrate it with Jenkins.
3. Configure Sonarqube to analyze code quality in the GitHub repository.
4. Create a Docker image of the application.
5. Deploy the Docker image using Jenkins.

## Usage

To utilize the Jenkins-Sonarqube-Docker pipeline, follow these guidelines:

1. Commit your code changes to the configured Github repository.
2. Jenkins will automatically trigger the pipeline upon receiving the code changes.
3. The pipeline will build your application, run tests, and analyze the code quality using Sonarqube.
4. If the code meets the defined quality gates, the pipeline will proceed to create a Docker image of your application.
5. Finally, Jenkins will deploy the Docker image to the desired target environment.
