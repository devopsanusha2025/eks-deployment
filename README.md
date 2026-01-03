# EKS Deployment Project

This project contains Kubernetes manifests to deploy microservices on AWS EKS.

## Tech Stack
- Kubernetes (EKS)
- Docker
- GitHub Actions (for CI/CD)

## Files
- `deployment.yaml` – Deployment configuration
- `service.yaml` – LoadBalancer service
- `hpa.yaml` – Horizontal Pod Autoscaler

## How to Deploy
1. Connect to your EKS cluster
2. Apply manifests:
   ```bash
   kubectl apply -f deployment.yaml
   kubectl apply -f service.yaml
   kubectl apply -f hpa.yaml
