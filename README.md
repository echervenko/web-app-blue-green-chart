# web-app-blue-green-chart

## Note

Using `RollingUpdate Strategy` to trigger Blue-Green Deployment
```
strategy:
  rollingUpdate:
    maxSurge: 100%
    maxUnavailable: 0%
```
