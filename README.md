ansible
=======

Installs Ansible

Requirements
------------

This role requires Ansible 1.6 or higher.

Role Variables
--------------

| Name                    | Default | Description                   |
|-------------------------|---------|-------------------------------|
| ansible_install_version | 2.0.0   | Version of Ansible to install |

Dependencies
------------

None

Example Playbook
----------------

Install Ansible

```
- hosts: all
  roles:
    - dwcramer.ansible
```

License
-------

BSD

Author Information
------------------

Kevin Brebanov
