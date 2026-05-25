# SRE Control Plane

Infrastructure automation, observability orchestration, and platform operations repository for a production-style Site Reliability Engineering homelab.

This repository represents the **control plane** responsible for provisioning, automating, monitoring, securing, and operating infrastructure across the SRE environment.

---

## Objectives

This repository exists to provide:

- Infrastructure as Code (IaC)
- Kubernetes lifecycle management
- Configuration management
- Monitoring and observability automation
- CI/CD automation
- Backup and disaster recovery workflows
- Documentation and operational runbooks
- Reproducible infrastructure

---

## Architecture Philosophy

Infrastructure is divided into two logical domains:

### sre-monitoring-stack (VM1)

Production/managed platform:

- Kubernetes
- Grafana
- Prometheus
- Loki
- Alertmanager
- Applications and workloads

### sre-control-plane (VM2)

Operations and management platform:

- Terraform
- Helm
- Ansible
- Jenkins
- Nagios
- SSH automation
- Backup orchestration
- GitOps workflows

---

## Repository Structure

```text
terraform/     Infrastructure provisioning
ansible/       Configuration management
helm/           Kubernetes package deployments
nagios/         Monitoring checks and configs
scripts/        Automation utilities
backups/        Backup/restore workflows
ssh/            SSH configs and hardening
docs/           Architecture + runbooks
jenkins/        CI/CD pipelines
configs/        Sanitized example configs
```

---

## Security

This repository intentionally excludes:

- secrets
- API keys
- passwords
- kubeconfigs
- SSH private keys
- Terraform state secrets
- certificates

Sanitized examples are provided instead.

---

## Goals

- Enterprise-style SRE learning
- Platform engineering workflows
- Full homelab management
- GitOps-based operations
- Reproducible infrastructure
- Operational maturity

---

## Status

Active development.# sre-control-plane
