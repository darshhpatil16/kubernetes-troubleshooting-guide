# Kubernetes Troubleshooting Guide

Real-world Kubernetes issues and resolutions.

## Topics

### CrashLoopBackOff
Cause:
- Application startup failure

Resolution:
- kubectl logs <pod>

### Node Not Ready
Cause:
- Kubelet issue

Resolution:
- Check node status

### PVC Pending
Cause:
- StorageClass issue

Resolution:
- Verify PV and PVC binding
