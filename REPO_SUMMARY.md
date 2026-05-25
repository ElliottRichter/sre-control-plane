# Repository Summary

## Purpose

`sre-control-plane` provides the operational management layer for the SRE lab.

This repository acts as the source of truth for:

- infrastructure provisioning
- automation
- monitoring
- backups
- CI/CD
- documentation
- operational procedures

---

## Scope

This repository manages:

### Infrastructure
- Terraform provisioning
- Helm deployments
- Kubernetes lifecycle operations

### Configuration Management
- Ansible automation
- SSH configuration
- System hardening

### Monitoring
- Nagios checks
- Alerting integration
- Observability workflows

### CI/CD
- Jenkins pipelines
- deployment automation
- validation workflows

### Documentation
- architecture diagrams
- screenshots
- operational runbooks
- network inventory

---

## Design Philosophy

Declarative infrastructure.

Git repository is source of truth.

Runtime systems are disposable and reproducible.

Documentation is mandatory.
