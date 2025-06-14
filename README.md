# 🌐 MulticloudDep – Your DevOps Dashboard Across Clouds

Welcome to **MulticloudDep**, a cloud-agnostic DevOps dashboard designed to streamline deployment tracking across multiple cloud platforms. Whether you're deploying on AWS, Azure, GCP, or on-premises, this tool provides real-time insights into your CI/CD pipelines, deployment metrics, and system performance.

---

## 🚀 What Is It?

MulticloudDep is a centralized dashboard that aggregates deployment data from various cloud environments, offering:

- ✅ Real-Time Deployment Tracking
- 📊 Unified Metrics Visualization
- 🔄 CI/CD Pipeline Insights

---

## 🛠️ Tech Stack

This project leverages a combination of modern DevOps tools and cloud services:

- **Frontend:** Streamlit – for building interactive dashboards.
- **Backend:** Python – for data processing and API integrations.
- **Containerization:** Docker
- **Orchestration:** Kubernetes
- **Infrastructure as Code:** Terraform
- **CI/CD:** Jenkins, GitHub Actions
- **Monitoring:** Prometheus, Grafana

---

## ⚙️ Setup & Usage

### ✅ Prerequisites

- Python 3.8+
- Docker
- Kubernetes (`kubectl`)
- Terraform
- Helm
- Jenkins (optional)

### 🚀 Installation

```bash
git clone https://github.com/pkd17/MulticloudDep.git
cd MulticloudDep
docker-compose build
cd infra/
terraform init
terraform apply
kubectl apply -f ../k8s/
```
