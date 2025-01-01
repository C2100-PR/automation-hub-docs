# Automation Hub Deployment

## GKE Setup
```bash
gcloud container clusters update private-cluster-auto \
  --region=us-west1 \
  --enable-master-authorized-networks
```

## Auto-scaling Configuration
```yaml
spec:
  replicas: 3
  template:
    spec:
      containers:
      - name: controller
        env:
        - name: AUTO_SCALING
          value: "enabled"
```