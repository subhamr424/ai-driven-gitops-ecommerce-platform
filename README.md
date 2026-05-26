# AI-Driven GitOps Ecommerce Deployment Platform

Production-grade cloud-native ecommerce deployment platform built using Kubernetes, Docker, Helm, ArgoCD, and GitHub Actions with fully automated GitOps CI/CD workflows.

---

# 🚀 Features

- Automated CI/CD pipeline using GitHub Actions
- GitOps deployment workflow with ArgoCD
- Automatic Docker image versioning (`v1 → v2 → v3`)
- Kubernetes rolling deployments
- Helm-based application deployment
- FastAPI backend with JWT authentication
- Frontend + Backend containerized deployment
- Horizontal Pod Autoscaler (HPA)
- Persistent Volumes (PV/PVC)
- Kubernetes Ingress routing
- Network Policies
- Automated DockerHub image publishing
- Self-healing Kubernetes deployments
- End-to-end automated deployment after every Git push

---

# 🛠 Tech Stack

- Kubernetes
- Docker
- Helm
- ArgoCD
- GitHub Actions
- FastAPI
- Python
- Linux
- DockerHub
- YAML
- GitOps

---

# ⚙️ CI/CD GitOps Workflow

```text
Developer Pushes Code
        ↓
GitHub Actions Trigger
        ↓
Docker Image Build
        ↓
Auto Version Tagging (v1/v2/v3)
        ↓
Push Image to DockerHub
        ↓
Update Helm values.yaml
        ↓
Commit Changes Back to GitHub
        ↓
ArgoCD Detects Changes
        ↓
Kubernetes Auto Sync
        ↓
Rolling Deployment
