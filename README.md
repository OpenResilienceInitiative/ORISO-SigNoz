# ORISO SigNoz

This repository keeps ORISO-specific SigNoz notes, helper scripts, and historical
configuration references for the observability stack.

## Current Ownership

Runtime deployment and environment-specific configuration are managed from
[ORISO-Helm](https://github.com/OpenResilienceInitiative/ORISO-Helm). Keep Helm
values, Kubernetes manifests, and release wiring there so dev, pre-dev, and
production stay consistent.

Use this repository only for SigNoz-specific supporting material that does not
belong in the platform Helm chart, such as:

- operational notes
- helper scripts
- exported or reference configuration
- migration notes for the SigNoz stack

## Access And Credentials

Do not store live URLs, IP addresses, usernames, passwords, tokens, or Slack
webhook values in this repository. Use the agreed credential store and the
current environment runbooks instead.

## Repository Contents

- `monitoring/`: legacy/helper monitoring scripts and examples
- `DEPLOYMENT.md`: historical deployment notes
- `MONITORING-GUIDE.md`: monitoring reference notes
- `signoz-values-*.yaml`: historical/reference values files

Before using any historical file from this repository, compare it with the
current ORISO-Helm chart and the running environment.

## Notes

- The correct product spelling is **SigNoz**.
- Avoid adding environment-specific secrets or one-off server details here.
- Prefer small updates that keep this repository as a lightweight reference.
