Kubectl
=========

Ansible Role to install kubectl tool.

Role Variables
--------------

```
# Kubectl version
kubectl_version: 1.23.0
```

Example Playbook
----------------

```yaml
- name: Ansible Playbook to install kubectl tool
  hosts: all
  gather_facts: yes
  any_errors_fatal: true
  become: true
  roles:
    - role: kubectl
      tags:
        - kubectl
```

License
-------

MIT

Author Information
------------------

Ewerton Silva <ewerton116@gmail.com>
