# Post-Deployment Monitoring Rules

## Alert Recipients
- Phillip Roark (mobile)
- Corey Roark (mobile)

## Monitoring Thresholds
- CPU: 80%
- Memory: 85%
- Latency: 2s

## Automated Actions
- Auto-scaling enabled
- Error recovery activation
- Health checks every 30s

## Logging
- 30 day retention
- BigQuery export
- Key metrics: Errors, Latency, Traffic

## Response Actions
1. SMS/Push notification to recipients
2. Auto-scale if thresholds exceeded
3. Error recovery initialization
4. Health check frequency increase