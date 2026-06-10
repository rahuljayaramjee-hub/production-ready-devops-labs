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

---


# Kubernetes Deployments

A Deployment is a Kubernetes resource used to manage and scale Pods. It ensures the desired number of Pods are running and automatically replaces failed Pods.

Deployments make application updates and scaling easier in a Kubernetes cluster.



---


# Kubernetes Namespaces

A Namespace is a way to organize and isolate resources within a Kubernetes cluster. It helps teams manage applications and avoid resource conflicts.

Namespaces improve resource management and provide logical separation between environments such as development, testing, and production.
