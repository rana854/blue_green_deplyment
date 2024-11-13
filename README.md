# Blue-Green Deployment

This repository demonstrates how to set up a Blue-Green Deployment strategy for a microservices application using Jenkins, Docker, and Kubernetes (Minikube). The goal is to minimize downtime by deploying a new version of the application in a "blue" environment while keeping the "green" (current live version) active. Once the blue environment is tested and verified, traffic is switched to the new version.

## Prerequisites

Before you begin, ensure you have the following tools installed and configured:
- **Docker** (for containerization)
- **Minikube** (for local Kubernetes cluster)
- **Jenkins** (for automating the CI/CD pipeline)
- **kubectl** (for interacting with your Kubernetes cluster)
- **Git** (for cloning the repository)

  ## Clone the Repository
```
git clone https://github.com/rana854/blue_green_deplyment.git
```
