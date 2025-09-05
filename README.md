# 🚀 GitOps Workflow with ArgoCD and Kubernetes (K3s)

## 📌 Project Overview

This project demonstrates the implementation of a **GitOps pipeline** using **ArgoCD** on a lightweight Kubernetes distribution, **K3s**, hosted on an AWS EC2 instance. The deployment state of applications is managed and synced directly from a GitHub repository, enabling version-controlled, automated, and auditable deployments.

---

## 🛠️ Tools & Technologies

- **Kubernetes (K3s)** – Lightweight Kubernetes distribution
- **ArgoCD** – GitOps continuous delivery tool for Kubernetes
- **Docker** – Containerization platform
- **GitHub** – Source control for manifest files
- **AWS EC2** – Cloud compute instance for hosting K3s

---

## ✅ Project Objectives

- Set up K3s Kubernetes cluster on AWS EC2
- Deploy and configure ArgoCD for GitOps
- Store Kubernetes manifests in GitHub
- Use ArgoCD to auto-sync application deployments from GitHub
- Demonstrate GitOps workflow via Git-based updates

---

## 🧰 Setup Instructions

### 🔹 PART 1: K3s Installation (on AWS EC2)

```bash
# Install K3s
curl -sfL https://get.k3s.io | sh -

# Verify installation
k3s kubectl get nodes
