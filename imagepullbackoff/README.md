# ImagePullBackOff

## Investigation

```bash
kubectl describe pod <pod-name>
```

## Common Causes

- Invalid image name
- Image tag missing
- Registry authentication issue

## Resolution

- Verify image name
- Verify image tag
- Configure imagePullSecrets
