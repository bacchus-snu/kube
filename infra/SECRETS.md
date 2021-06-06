# Secrets

## longhorn-system/basic-auth

HTTP basic auth token for longhorn ui.

```bash
kubectl -n longhorn-system create secret generic basic-auth --from-file=auth
```
