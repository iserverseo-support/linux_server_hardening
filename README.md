# Linux Server Hardening

Ansible role for applying a practical baseline security configuration to Linux servers.

## What this role does

This role provides configurable Linux server hardening, including:

- SSH security configuration
- Root SSH login restriction
- SSH authentication limits
- SSH idle connection timeouts
- Firewall configuration
- Basic kernel/sysctl hardening
- TCP SYN cookie protection
- IP forwarding control
- Core dump restrictions
- Package cache updates

The role supports common Debian-based and RHEL-based Linux systems.

## Supported Systems

- Ubuntu
- Debian
- AlmaLinux
- Rocky Linux
- RHEL-compatible systems

## Requirements

- Ansible 2.14+
- Python available on the managed host
- `ansible.posix`
- `community.general`

Install the required collections:

```bash
ansible-galaxy collection install ansible.posix community.general
