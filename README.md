# GitOps-Deployment-with-GitHub-Actions-and-Terraform

This project showcases a complete GitOps-driven CI/CD pipeline using GitHub Actions for automation, Terraform for infrastructure provisioning, Docker and Helm for application deployment, and SonarCloud for continuous code quality assurance.

## 🔧 Technologies Used

- GitHub Actions (CI/CD)
- GitOps Methodology
- Terraform
- Amazon Web Services (EKS, ECR)
- Docker
- Helm Charts
- Kubernetes
- SonarCloud
- Static Code Analysis
- Pull Request Workflows

## 📌 Project Overview

This pipeline automates the full software development lifecycle with GitOps principles, ensuring traceability, repeatability, and collaboration from code to production. The core components include:

- Continuous Integration and Deployment using GitHub Actions.
- Infrastructure provisioning and management on AWS using Terraform.
- Containerization of application code using Docker and storing images in ECR.
- Kubernetes deployment using Helm Charts for scalable, declarative application releases.
- Integration with SonarCloud for static code analysis, enforcing code quality and security.
- Pull request workflows for code reviews, testing, and automated promotion to production.

## 🚀 Features

- GitOps-driven automation for infrastructure and application deployments.
- Declarative infrastructure as code using Terraform.
- Scalable, reproducible deloyments on AWS EKS.
- Container image management via Amazon ECR.
- Quality gates and code scanning using SonarCloud.
- Collaborative development through GitHub pull requests and actions.


> **Note:**  
> The source code and target deployment files (e.g., application source files) are not included in this repository.  
> However, the project structure and configurations are designed to be compatible with standard AWS-based DevOps workflows.  
> These files can be extracted, reused, or adapted from other AWS infrastructure or application repositories as needed for demonstration or production purposes.
