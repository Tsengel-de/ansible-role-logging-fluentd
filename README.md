# Ansible Role: logging-fluentd

Minimal Ansible role for Fluentd logging configuration.

## Description

This role provides basic Fluentd setup for log aggregation.

## Requirements

- Ansible 2.9+
- Debian/Ubuntu or RHEL/CentOS systems

## Example Playbook

```yaml
- hosts: servers
  roles:
    - Tsengel-de.logging-fluentd
```

## License

MIT
