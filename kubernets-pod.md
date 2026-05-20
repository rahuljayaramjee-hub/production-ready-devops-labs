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
