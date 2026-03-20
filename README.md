# 🚀 Helm NGINX Web App

Production-style Helm chart for deploying an NGINX application on Kubernetes.

## 📌 Features
- Helm templated Kubernetes deployment
- Configurable replicas via values.yaml
- Ingress-based traffic routing
- Rolling upgrades and rollback support
- Resource limits and health probes

## 🧱 Architecture
Browser → Ingress → Service → Deployment → Pods

## ⚙️ Installation

```bash
helm install nginx-webapp .
