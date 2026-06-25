# 🚀 End-to-End CI/CD Pipeline using GitHub, Jenkins, Docker & Kubernetes

![GitHub](https://img.shields.io/badge/GitHub-Version%20Control-181717?style=for-the-badge&logo=github)
![Jenkins](https://img.shields.io/badge/Jenkins-CI/CD-D24939?style=for-the-badge&logo=jenkins)
![Docker](https://img.shields.io/badge/Docker-Containerization-2496ED?style=for-the-badge&logo=docker)
![Kubernetes](https://img.shields.io/badge/Kubernetes-Orchestration-326CE5?style=for-the-badge&logo=kubernetes)
![AWS](https://img.shields.io/badge/AWS-Cloud-FF9900?style=for-the-badge&logo=amazonaws)

---

## 📖 Overview

This project demonstrates an **End-to-End CI/CD Pipeline** built using **GitHub, Jenkins, Docker, Kubernetes, and AWS**.

Whenever code is pushed to GitHub, Jenkins automatically:

- Clones the source code
- Builds the application using Maven
- Creates a Docker image
- Pushes the image to Docker Hub
- Deploys the latest version to a Kubernetes cluster

This setup enables fully automated application deployment with minimal manual intervention.

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

## ☁️ Cloud

- AWS EC2
- AWS VPC
- Security Groups

## 🔄 CI/CD

- Git
- GitHub
- Jenkins

## 🐳 Containerization

- Docker
- Docker Hub

## ☸️ Container Orchestration

- Kubernetes
- kubeadm
- kubectl
- containerd
- Calico

## 💻 Application

- Java
- Spring Boot
- Maven

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
- OpenJDK 17

### Kubernetes Master Node

- Ubuntu 24.04 LTS
- kubeadm
- kubectl
- containerd
- Calico Network Plugin

### Kubernetes Worker Node

- Ubuntu 24.04 LTS
- kubeadm
- containerd

---

# 🔄 CI/CD Workflow

1. Developer pushes code to GitHub.
2. Jenkins automatically triggers the pipeline.
3. Source code is cloned from GitHub.
4. Maven builds the application.
5. Docker image is created.
6. Docker image is pushed to Docker Hub.
7. Kubernetes updates the deployment.
8. New pods are created using the latest image.
9. Application becomes available through the Kubernetes Service.

---

# ✨ Key Features

- Automated CI/CD Pipeline
- GitHub Integration
- Jenkins Declarative Pipeline
- Docker Image Build & Push
- Kubernetes Deployment
- Rolling Updates
- Infrastructure Hosted on AWS
- Scalable Kubernetes Architecture

---

# 📈 Future Enhancements

- GitHub Webhooks
- SonarQube Code Quality Analysis
- Trivy Image Security Scanning
- Prometheus Monitoring
- Grafana Dashboards
- Helm Charts
- Argo CD (GitOps)
- AWS EKS Deployment

---

# 👨‍💻 Author

**Rakesh S**

📧 Email: **rakeshs2k26@gmail.com**

💼 LinkedIn: **https://www.linkedin.com/in/rakesh-s-66750328a/**

🐙 GitHub: **https://github.com/RS-cloud-intellipaat**

---

## ⭐ Support

If you found this project useful, please consider giving it a **⭐ Star** on GitHub!
