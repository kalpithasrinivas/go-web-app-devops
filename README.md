# 🚀 End-to-End CI/CD & GitOps Deployment – Go Web App

This project demonstrates a complete DevOps pipeline by containerizing a Go web application and deploying it to AWS EKS using GitHub Actions, Docker, Helm, and Argo CD.

---

## ⚙️ Tech Stack
- AWS EKS
- Docker
- Kubernetes
- Helm
- Argo CD
- GitHub Actions
- NGINX Ingress Controller
- DockerHub

---

## 🔁 CI/CD Pipeline

CI (GitHub Actions):
- Builds Go application
- Builds Docker image
- Pushes image to DockerHub

CD (Argo CD – GitOps):
- Monitors Helm charts in GitHub
- Automatically deploys updates to EKS cluster

---

## ☸️ Kubernetes Deployment
Resources managed using Helm:
- Deployment
- Service
- Ingress
- AWS LoadBalancer

---

## 🌐 Live Application
Accessible via AWS LoadBalancer URL: http://afe2e090621514598ba820ac6d642eab-46b83e444c55c30c.elb.us-east-1.amazonaws.com/#about

