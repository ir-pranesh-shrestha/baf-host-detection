# BAF Host Detection Test

GitHub Actions workflows to test BAF anomaly detection for standard and non-standard hosts.

## Workflows

| Workflow | Description |
|---|---|
| `standard-hosts.yml` | Curls known legitimate package registry and CI/CD hosts |
| `non-standard-hosts.yml` | Curls non-standard, staging, and suspicious hosts |

## Usage

Trigger either workflow manually from the **Actions** tab in GitHub using `workflow_dispatch`.
