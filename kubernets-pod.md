# Kubernetes Pod Basics ☸️

## Overview

This project demonstrates how to create and run a basic Kubernetes Pod using YAML configuration.

## Pod Configuration

```yaml
apiVersion: v1
kind: Pod
metadata:
  name: nginx-pod

spec:
  containers:
    - name: nginx-container
      image: nginx
      ports:
        - containerPort: 80
```
## Commands Used

```bash
kubectl apply -f pod.yaml
kubectl get pods
kubectl describe pod nginx-pod
```

## Skills Learned

- Kubernetes Pod creation
- YAML configuration
- kubectl basic commands
- Container deployment

---

## Technologies Used

- Kubernetes
- kubectl
- Nginx
- Linux

## Goal

Learning Kubernetes fundamentals for DevOps and Cloud Engineering.
this is the production level


---

# Pod Lifecycle

A Pod goes through different phases during its lifecycle in Kubernetes.

## Phases
- **Pending** – Pod is being created.
- **Running** – Containers are running successfully.
- **Succeeded** – Task completed successfully.
- **Failed** – One or more containers failed.
- **Unknown** – Kubernetes cannot determine the Pod status.

Understanding Pod lifecycle phases helps in monitoring and troubleshooting applications in a Kubernetes cluster.
