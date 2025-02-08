prometheus_node_exporter
========================
[![Ansible Lint](https://github.com/oxivanisher/role-prometheus_node_exporter/actions/workflows/ansible-lint.yml/badge.svg)](https://github.com/oxivanisher/role-prometheus_node_exporter/actions/workflows/ansible-lint.yml)

Install and enable the Prometheus node exporter on Debian based systems.

Role Variables
--------------

None

Dependencies
------------

None

Example Playbook
----------------
```yaml
- name: Debian clients
  hosts: debian
  roles:
    - role: oxivanisher.linux_base.prometheus_node_exporter
```

License
-------

BSD

Author Information
------------------

This role is part of the [oxivanisher.linux_base](https://galaxy.ansible.com/ui/repo/published/oxivanisher/linux_base/) collection, and the source for that is located on [github](https://github.com/oxivanisher/collection-linux_base).
