# Microservices DevOps Platform (AWS + Kubernetes + Terraform)

## 🚀 Overview
This project demonstrates a production-grade microservices architecture deployed on AWS using Kubernetes (EKS), Terraform IaC, and CI/CD automation.

---

## 🏗 Architecture
- API Gateway / Ingress Controller
- Microservices (Node.js / Java / Python)
- Kubernetes (EKS)
- PostgreSQL / MongoDB
- Redis caching

---

## ⚙️ Tech Stack
- AWS (EKS, EC2, S3, RDS, IAM)
- Kubernetes + Helm
- Terraform (IaC)
- Docker
- GitHub Actions CI/CD
- Prometheus + Grafana

---

## 🔄 CI/CD Flow
GitHub Push → GitHub Actions → Docker Build → Push to ECR → Deploy to EKS

---

## 🚀 Deployment Steps
```bash
terraform init
terraform apply
kubectl apply -f k8s-manifests/
