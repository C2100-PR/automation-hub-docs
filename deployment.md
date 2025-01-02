# Automation Hub Setup

## GKE Configuration
- Region: us-west1
- Auto-scaling: enabled
- Monitoring: PC-Alerts

## Quick Deploy
```bash
gcloud container clusters get-credentials private-cluster-auto --region=us-west1
kubectl apply -f automation.yaml
```