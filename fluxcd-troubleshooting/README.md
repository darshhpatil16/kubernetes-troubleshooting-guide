# FluxCD Troubleshooting

## Common Error

```text
Source is not ready, artifact not found
```

## Investigation

```bash
kubectl get kustomizations -A
kubectl get gitrepositories -A
kubectl describe kustomization <name>
```

## Resolution

- Verify GitRepository
- Verify branch
- Verify path
- Reconcile Flux

```bash
flux reconcile source git <repo-name>
flux reconcile kustomization <kustomization-name>
```
