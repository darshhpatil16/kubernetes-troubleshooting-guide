# Node Not Ready

## Symptoms

```bash
kubectl get nodes
```

Output:

```text
NotReady
```

## Investigation

```bash
kubectl describe node <node-name>
```

## Common Causes

- Kubelet stopped
- Network issue
- Resource exhaustion

## Resolution

- Restart kubelet
- Verify node health
- Verify connectivity

## Lessons Learned

Node conditions provide valuable diagnostic information.
