# ORISO SigNoz

This repository contains ORISO-specific supporting material for the observability
stack.

## Purpose

The repository is intended as a lightweight place for SigNoz-related reference
material, helper scripts, and operational notes that are useful for the ORISO
platform team.

Runtime deployment and environment configuration are managed through
[ORISO-Helm](https://github.com/OpenResilienceInitiative/ORISO-Helm).

## Repository Contents

- `monitoring/`: helper scripts and monitoring examples
- `DEPLOYMENT.md`: deployment notes
- `MONITORING-GUIDE.md`: monitoring notes
- `signoz-values-*.yaml`: reference values files

## Working Guidelines

- Keep operational documentation short and current.
- Keep environment-specific configuration in the Helm chart where possible.
- Do not commit secrets or personal access details.
- Prefer small, focused updates that are easy to review.
