# Ingress Issues

## Symptoms

Application inaccessible through URL.

## Investigation

```bash
kubectl get ingress
kubectl describe ingress
```

## Common Causes

- Incorrect host configuration
- Missing backend service
- DNS issue
- SSL certificate issue

## Resolution

- Verify ingress rules
- Verify service endpoints
- Validate SSL certificates
