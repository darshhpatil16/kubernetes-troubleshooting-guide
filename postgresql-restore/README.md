# PostgreSQL Restore Troubleshooting

## Symptoms

Restore process completed but nohup command continued running.

## Investigation

```bash
ps -ef | grep pg_restore
top
```

## Common Causes

- Index creation still running
- VACUUM process running
- ANALYZE operation in progress
- Large table rebuild

## Resolution

- Monitor active queries
- Check pg_stat_activity
- Validate database size
- Verify restore logs

## Lessons Learned

Database restore completion does not always mean all post-processing activities are finished.
