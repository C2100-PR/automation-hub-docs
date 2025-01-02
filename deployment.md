# Automation Hub Deployment

## Cluster Setup
```bash
gcloud container clusters get-credentials private-cluster-auto --region=us-west1
```

## Container Deployment
```yaml
apiVersion: apps/v1
kind: Deployment
metadata:
  name: automation-controller
spec:
  replicas: 3
```