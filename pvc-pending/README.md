# PVC Pending

## Symptoms

```bash
kubectl get pvc
```

Output:

```text
Pending
```

## Investigation

```bash
kubectl describe pvc <pvc-name>
kubectl get storageclass
kubectl get pv
```

## Common Causes

- Missing StorageClass
- Incorrect StorageClass
- Insufficient storage

## Resolution

- Verify StorageClass
- Verify PV binding
- Check storage quota

## Lessons Learned

Always verify StorageClass configuration first.
