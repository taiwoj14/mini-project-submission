## Project Overview

This project documents the setup and verification of my local DevOps environment.
The environment was prepared to support cloud, containerization, Kubernetes,
Infrastructure as Code, automation, and CI/CD activities.

## Environment

- Operating System: Ubuntu 24.04 LTS on WSL2
- Editor: Visual Studio Code
- Version Control: Git and GitHub
- Cloud Platforms: AWS and Microsoft Azure
- Containerization: Docker
- Kubernetes: Minikube and kubectl
- Package Manager: Helm
- Infrastructure as Code: Terraform
- Configuration Management: Ansible
- Runtime: Node.js
- JSON Processing: jq


# DevOps Environment Setup

## 1. Environment Configuration

The Bash configuration used for the environment is provided in:

- `bashrc.txt`

## 2. Tooling Verification

Version checks for the required DevOps tools are documented in:

- `DevOps Tools Verification Report.txt`

The verification includes Git, Python, Java, Docker, Docker Compose, kubectl,
Terraform, Ansible, Helm, Minikube, AWS CLI, and Azure CLI.

## 3. Local Kubernetes Cluster Proof

A screenshot showing the running Minikube Kubernetes cluster is available at:

- `screenshots/minikube-cluster-proof.png`


## 4. Setup and Troubleshooting

### Package Manager

APT was used to install and manage Linux packages on Ubuntu.

Additional tools were installed using their official installation methods where
appropriate.

### Troubleshooting

During the setup process, Minikube initially encountered a cluster startup
issue. The problem was resolved by restarting Minikube:

```bash
minikube stop
minikube start


## 5. The Kubernetes cluster was then verified using:

kubectl cluster-info
minikube status

## 6. VERIFICATION

All required tools were verified using version commands documented in DevOps-Tools-Verification-Report
