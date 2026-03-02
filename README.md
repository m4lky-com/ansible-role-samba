# Samba Ansible Role

## Requirements

Ubuntu 20.04+ or 22.04+

## Example Playbook

```yaml
- hosts: samba_hosts
  become: true
  roles:
    - ansible-role-samba