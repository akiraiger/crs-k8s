# Kubernetes Deployment on EKS

Deploy your docker images on kubernetes cluster

## Requirements

- Docker
- AWS account (permission ECR, EKS)
- `awscli`
- `eksctl`
- `kubectl`

## Outlines

- Containerize your app with Docker
  - [x] Docker intro
  - [x] `Dockerfile`
- Build Docker images
  - [x] Building and running image locally
- Create Kubernetes cluster on AWS
  - [x] Kubernetes intro
  - [x] Install requirements
  - [x] Setup `awscli`
  - [x] Create cluster with `eksctl`
- EKS Deployment
  - [x] Upload image to AWS ECR
  - [x] Scripts
    - [x] Deployment (Deployment in Kubernetes)
    - [x] Service (Type of services)
  - [x] Accessing cluster
  - [x] Manage cluster (Update node size, and/or image version)

## References
- https://kubernetes.io/id/docs/concepts/services-networking/service/
- https://kubernetes.io/id/docs/concepts/workloads/controllers/deployment/
- https://medium.com/google-cloud/kubernetes-nodeport-vs-loadbalancer-vs-ingress-when-should-i-use-what-922f010849e0
