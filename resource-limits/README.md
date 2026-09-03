# Resource Limits

## Investigation

```bash
kubectl top pod
kubectl top node
```

## Common Causes

- Low CPU request
- Low memory limit
- Node resource exhaustion

## Resolution

- Adjust requests
- Adjust limits
- Scale deployment
