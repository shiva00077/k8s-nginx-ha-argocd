# Kubernetes NGINX High Availability Project

## Overview
This project demonstrates high availability web hosting using Kubernetes.

## Features
- Load balancing
- Auto scaling
- Self-healing
- AWS EKS ready

## Architecture
User ? Ingress ? Service ? Pods

## Deployment
kubectl apply -f .

## AWS Deployment
Replace ingress with ALB controller.

## Testing
Delete pods and verify application availability.

