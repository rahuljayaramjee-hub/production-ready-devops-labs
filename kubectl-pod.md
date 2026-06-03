# Kubernetes Pods

A Pod is the smallest deployable unit in Kubernetes. It contains one or more containers that share network and storage resources.

## Features
- Runs containers
- Shares network and storage
- Managed by Kubernetes

## Example

```yaml
apiVersion: v1
kind: Pod
metadata:
  name: nginx-pod
spec:
  containers:
  - name: nginx
    image: nginx
```

Pods are the basic building blocks of applications running in a Kubernetes cluster.
