# Ansible Role: Patching Windows

#### Version: 1.0.1

[![pipeline status](https://gitlab.com/sparknsh/ansible-role-patching-windows/badges/master/pipeline.svg)](https://gitlab.com/sparknsh/ansible-role-patching-windows/commits/master)
[![Ansible Role](https://img.shields.io/ansible/role/30024.svg)](https://galaxy.ansible.com/sparknsh/patching_windows)
[![Ansible Role](https://img.shields.io/ansible/role/d/30024.svg)](https://galaxy.ansible.com/sparknsh/patching_windows)

Development of this project is managed in a private repository then pushed out to [GitLab](https://gitlab.com/sparknsh/ansible-role-patching-windows) and [GitHub](https://github.com/sparknsh/ansible-role-patching-windows) when we have a new version for you. If you have any issues please contact [sparknsh](https://www.sparknsh.com/contact?type=issue&name=ansible-role-patching-windows)

## Role Variables

```yaml
patching_windows_reboot: False
patching_windows_categories:
  - "CriticalUpdates"
  - "SecurityUpdates"
  - "Updates"
```

## Example Playbook

```yaml
- hosts: all
  vars_files:
    - vars/main.yml
  roles:
    - { role: sparknsh.patching_windows }
```

## License

MIT

## Author Information

This role was created in 2018 by [sparknsh](https://www.sparknsh.com) at [Rebel Media, Inc.](https://www.rebelmedia.io/)
