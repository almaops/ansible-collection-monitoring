[![License](https://img.shields.io/badge/license-MIT%20License-brightgreen.svg)](./LICENSE)
[![ansible-lint](https://github.com/almaops/ansible-collection-monitoring/actions/workflows/ansible-lint.yml/badge.svg?branch=main)](https://github.com/almaops/ansible-collection-monitoring/actions/workflows/ansible-lint.yml)
# Ansible Collection - almaops.monitoring

## Description
This collection provides roles for deploying monitoring stack. It includes roles for deploying applications such as Grafana or Prometheus.

## Installation
With command line from Ansible Galaxy:
```
ansible-galaxy collection install almaops.monitoring
```
With requirements file:
```
~# cat /path/to/your/requirements.yml
---
collections:
# from Ansible Galaxy
- name: almaops.monitoring
# from Git repository
- name: https://github.com/almaops/ansible-collection-monitoring.git
  type: git
...
~# ansible-galaxy install -r /path/to/your/requirements.yml
```

## Roles

### almaops.monitoring.ct_grafana
This roles deploys container with Grafana. Please consult with role's [README](./roles/ct_grafana/README.md)

### almaops.monitoring.ct_loki
This roles deploys container with Grafana Loki. Please consult with role's [README](./roles/ct_loki/README.md)
