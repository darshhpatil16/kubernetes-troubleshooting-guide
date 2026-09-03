# High Memory Utilization

## Symptoms

Node memory usage exceeded threshold.

## Investigation

```bash
kubectl top nodes
kubectl top pods -A
```

## Common Causes

- Memory leak
- Improper resource limits
- High application load

## Resolution

- Identify top consuming pods
- Tune resource requests and limits
- Scale workloads

## Lessons Learned

Always configure resource limits and monitor memory trends proactively.
