# DevOps Microservices Project 🚀

This project demonstrates a full DevOps pipeline using:
- Microservices in Node.js
- Dockerized services
- Kubernetes + Helm for orchestration
- CI/CD (can be extended with GitHub Actions / GitLab CI)
- Deployed on Minikube / AWS EC2

## 🧱 Microservices
- `auth` – handles authentication
- `payment` – handles payment endpoints
- `user` – (placeholder or to be implemented)

## 🛠 DevOps Stack
- **Docker**
- **Kubernetes** with `minikube`
- **Helm** for service packaging
- **AWS EC2 (Ubuntu)** as hosting environment

## 🚀 How to Run
1. Clone the repo
2. Use Docker to build services
3. Use `helm install` to deploy charts to Minikube

```bash
helm install auth ./k8s/helm/charts/auth
helm install payment ./k8s/helm/charts/payment

