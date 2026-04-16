# devops-platform
Production-grade DevOps platform on AWS using Terraform, Kubernetes (EKS), CI/CD, GitOps, and full observability stack.
# 🚀 DevOps Platform (Production-Grade)

A production-grade cloud-native DevOps platform designed to simulate real-world infrastructure, deployment, and observability practices.

This project demonstrates end-to-end DevOps workflows including Infrastructure as Code, container orchestration, CI/CD automation, GitOps deployment, and system observability.

---

## 🧱 Current Phase

✅ Phase 1: Multi-service architecture with Docker and GitHub workflow

---

## ⚙️ Tech Stack

* Cloud: AWS (planned)
* Infrastructure: Terraform (planned)
* Containerization: Docker
* Orchestration: Kubernetes (EKS - upcoming)
* CI/CD: GitHub Actions / Jenkins (upcoming)
* GitOps: ArgoCD (upcoming)
* Monitoring: Prometheus, Grafana, Loki (upcoming)

---

## 🏗️ Architecture (Phase 1)

* Frontend → Static UI served via Nginx
* Backend → Flask API with health endpoint
* Worker → Background job processor
* Docker Compose → Local orchestration

---

## 📁 Project Structure

```
devops-platform/
│
├── apps/
│   ├── frontend/
│   ├── backend/
│   └── worker/
│
├── infra/terraform/
├── k8s/
├── helm/
├── gitops/
├── monitoring/
├── ci-cd/
├── docs/
└── docker-compose.yml
```

---

## 🚀 Getting Started

### 1. Clone Repository

```
git clone https://github.com/<your-username>/devops-platform.git
cd devops-platform
```

### 2. Run Services

```
docker-compose up --build
```

---

## 🌐 Services

| Service  | Description                   | Port |
| -------- | ----------------------------- | ---- |
| Frontend | UI Dashboard                  | 8080 |
| Backend  | API + Health Check            | 5000 |
| Worker   | Background Processing Service | -    |

---

## 🔍 Health Check

```
http://localhost:5000/health
```

Expected:

```
{"status": "ok"}
```

---

## 🧠 Key Concepts Implemented

* Multi-service architecture
* Containerized applications
* Service-to-service communication (Docker network)
* Health checks for system monitoring
* Git-based workflow (feature branches + PRs)

---

## 📌 Upcoming Phases

* Terraform-based AWS infrastructure
* Kubernetes deployment (EKS)
* CI/CD pipeline automation
* GitOps (ArgoCD)
* Observability stack (Prometheus, Grafana, Loki)
* Auto-scaling and self-healing systems

---

## 💣 Interview Highlights

* Designed a multi-service architecture with containerized applications
* Implemented health check endpoints for monitoring readiness
* Used Docker Compose for local orchestration and service discovery
* Followed production-grade Git workflow using feature branches and pull requests

---

## ⚠️ Important Notes

* No hardcoded localhost used for inter-service communication
* Clean project structure for scalability
* Designed with production mindset, not tutorial approach

---

## 👨‍💻 Author

Vikram – DevOps Engineer

---
