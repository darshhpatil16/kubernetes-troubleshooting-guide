# Kubernetes Troubleshooting Guide

A collection of real-world Kubernetes production issues, troubleshooting commands, root causes, and resolutions.

---

## Topics Covered

- CrashLoopBackOff
- PVC Pending
- Node Not Ready
- Ingress Issues
- ImagePullBackOff
- ContainerCreating
- Resource Limits
- FluxCD Troubleshooting

---

## Useful Commands

### Check Pods

```bash
kubectl get pods -A
```

### Describe Pod

```bash
kubectl describe pod <pod-name>
```

### View Logs

```bash
kubectl logs <pod-name>
```

### Check Events

```bash
kubectl get events --sort-by=.metadata.creationTimestamp
```

### Check Nodes

```bash
kubectl get nodes
```

---

## Troubleshooting Methodology

1. Identify the issue.
2. Collect logs.
3. Check events.
4. Verify resources.
5. Validate configurations.
6. Implement fix.
7. Monitor stability.

---

## Author

Darshan Patil

Cloud DevOps Engineer
