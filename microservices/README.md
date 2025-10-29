# Microservices

This directory contains all microservices for the application container.
Each subdirectory represents a single microservice following CLAUDE.md standards.

## Adding New Microservices

Use ApplicationClaim to add new microservices:

```yaml
apiVersion: platform.example.org/v1alpha1
kind: ApplicationClaim
metadata:
  name: my-service
spec:
  appContainer: parking-automation
  name: my-service
  language: python
  framework: fastapi
  database: postgres
  cache: redis
```

## Current Services

- (Services will be listed here as they are added)
- parking-automation (python/fastapi)
- reservation-service (python/fastapi)
