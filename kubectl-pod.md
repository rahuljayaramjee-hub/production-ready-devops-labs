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

  ---

  ---

  # YAML in Kubernetes

YAML (YAML Ain't Markup Language) is a human-readable format used to define Kubernetes resources such as Pods, Services, and Deployments.

YAML files describe the desired state of an application, which Kubernetes uses to create and manage resources automatically.


  # Kubernetes Services

A Service in Kubernetes provides a stable network endpoint to access Pods. It helps applications communicate reliably even when Pods are created or deleted.

Services enable load balancing and service discovery within a Kubernetes cluster.
