# Renovate configuration for Argo CD GitOps

Shared Renovate base config for GitOps state repos. Includes common settings, automerge rules, and managers for Kubernetes, Argo CD, Helm values, and Docker image tags in YAML files.

## Usage

In your repo's `renovate.json`:

```json
{
  "$schema": "https://docs.renovatebot.com/renovate-schema.json",
  "extends": ["github>Nasus20202/argocd-renovate"]
}
```

Add any repo-specific `packageRules`, `customManagers`, or manager overrides on top.
