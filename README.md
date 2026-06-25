# 🚀 End-to-End CI/CD Pipeline using GitHub, Jenkins, Docker & Kubernetes

![GitHub](https://img.shields.io/badge/GitHub-Version%20Control-181717?style=for-the-badge&logo=github)
![Jenkins](https://img.shields.io/badge/Jenkins-CI/CD-D24939?style=for-the-badge&logo=jenkins)
![Docker](https://img.shields.io/badge/Docker-Containerization-2496ED?style=for-the-badge&logo=docker)
![Kubernetes](https://img.shields.io/badge/Kubernetes-Orchestration-326CE5?style=for-the-badge&logo=kubernetes)
![AWS](https://img.shields.io/badge/AWS-Cloud-FF9900?style=for-the-badge&logo=amazonaws)

---

## 📖 Overview

This project demonstrates a complete **End-to-End CI/CD Pipeline** using modern DevOps tools.

Whenever code is pushed to GitHub, Jenkins automatically:

- Clones the repository
- Builds the application
- Creates a Docker image
- Pushes the image to Docker Hub
- Deploys the latest version to a Kubernetes Cluster

The entire deployment process is fully automated.

---

# 🏗 Architecture

```text
Developer
    │
    ▼
GitHub Repository
    │
    ▼
Jenkins Pipeline
    │
    ▼
Maven Build
    │
    ▼
Docker Build
    │
    ▼
Docker Hub
    │
    ▼
Kubernetes Cluster
    │
    ▼
Application Running
```

---

# 🛠 Tech Stack

## ☁ Cloud

- AWS EC2
- AWS VPC
- Security Groups

---

## 🚀 CI/CD

- Git
- GitHub
- Jenkins

---

## 🐳 Containerization

- Docker
- Docker Hub

---

## ☸ Container Orchestration

- Kubernetes
- kubeadm
- kubectl
- containerd
- Calico

---

## 💻 Programming

- Java / Spring Boot
- Flask (Optional)

---

## ⚙ Build Tool

- Maven

---

## 🐧 Operating System

- Ubuntu Linux

---

# 📂 Project Structure

```text
.
├── Dockerfile
├── Jenkinsfile
├── deployment.yaml
├── service.yaml
├── pom.xml
├── src/
└── README.md
```

---

# 🚀 Infrastructure Setup

### Jenkins Server

- Ubuntu 24.04 LTS
- Jenkins
- Docker
- Java 17

---

### Kubernetes Master

- Ubuntu
- kubeadm
- containerd
- kubectl
- Calico

---

### Kubernetes Worker

- Ubuntu
- kubeadm
- containerd

---

# 🔄 CI/CD Workflow

1. Developer pushes code to GitHub
2. Jenkins detects changes
3. Jenkins clones repository
4. Maven builds the application
5. Docker image is created
6. Docker image is pushed to Docker Hub
7. Kubernetes deployment is updated
8. New Pods are created
9. Application becomes available

---

# ✨ Features

- Automated CI/CD Pipeline
- Docker Image Build
- Docker Hub Integration
- Kubernetes Deployment
- Rolling Updates
- GitHub Integration
- Jenkins Declarative Pipeline
- Infrastructure hosted on AWS

---

# 📸 Project Screenshots

## Jenkins Pipeline

> Add screenshot here

```
images/jenkins-pipeline.png
```

---

## Docker Hub Repository

> Add screenshot here

```
images/dockerhub.png
```

---

## Kubernetes Pods

> Add screenshot here

```
images/k8s-pods.png
```

---

## Running Application

> Add screenshot here

```
images/application.png
```

---

# 📈 Future Improvements

- GitHub Webhooks
- SonarQube Code Analysis
- Trivy Image Scanning
- Prometheus Monitoring
- Grafana Dashboard
- Helm Charts
- ArgoCD
- EKS Deployment

---

# 👨‍💻 Author

## Rakesh S

📧 Email

rakeshs2k26@gmail.com

💼 LinkedIn

https://www.linkedin.com/in/rakesh-s-66750328a/

🐙 GitHub

https://github.com/RS-cloud-intellipaat

---

# ⭐ If you found this project helpful

Give this repository a ⭐ Star.
