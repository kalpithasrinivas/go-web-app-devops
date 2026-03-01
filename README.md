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

🐳 Containerization (Docker)

• Created a Dockerfile to containerize the Go web application
• Built Docker images locally and in CI pipeline
• Pushed images to DockerHub registry
• Used Docker images for Kubernetes deployments
<img width="1900" height="851" alt="image" src="https://github.com/user-attachments/assets/0cff9077-a934-41b4-8267-7ffcdd3aed74" />


## 🔁 CI/CD Pipeline

CI (GitHub Actions):
- Builds Go application
- Builds Docker image
- Pushes image to DockerHub
<img width="1868" height="710" alt="image" src="https://github.com/user-attachments/assets/40783cd2-9c7b-4fcb-9e96-2f5c7ffe1d80" />

CD (Argo CD – GitOps):
- Monitors Helm charts in GitHub
- Automatically deploys updates to EKS cluster
<img width="1895" height="931" alt="image" src="https://github.com/user-attachments/assets/18f89e69-57c1-4fd1-aada-817775a66528" />

---

## ☸️ Kubernetes Deployment
Resources managed using Helm:
- Deployment
- Service
- Ingress
- AWS LoadBalancer
<img width="1483" height="762" alt="image" src="https://github.com/user-attachments/assets/e3bd110e-c62b-4776-a235-d2004dde8c12" />

---

## 🌐 Live Application
Accessible via AWS LoadBalancer URL: http://afe2e090621514598ba820ac6d642eab-46b83e444c55c30c.elb.us-east-1.amazonaws.com/#about
<img width="1907" height="943" alt="image" src="https://github.com/user-attachments/assets/31958142-fb37-45a8-bfd4-96939ee09840" />


