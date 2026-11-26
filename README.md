# Project 14 - App Deployment using EKS

## Components
- Docker
- Amazon ECR
- Amazon EKS
- Kubernetes Deployment
- Kubernetes Service (LoadBalancer)

## Files
- app.py
- Dockerfile
- requirements.txt
- deployment.yaml
- service.yaml

## Deployment

kubectl apply -f deployment.yaml

kubectl apply -f service.yaml

kubectl get pods

kubectl get svc
