# SRE Architecture

## Environment Overview

VM1 = sre-monitoring-stack

Responsibilities:

- Kubernetes
- Grafana
- Prometheus
- Loki
- Alertmanager

VM2 = sre-control-plane

Responsibilities:

- Helm
- Terraform
- Ansible
- Jenkins
- Nagios
- Backup automation

---

## Philosophy

Infrastructure should be reproducible.

Git repository defines desired state.

Automation deploys state.

Monitoring validates state.
