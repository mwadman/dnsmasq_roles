dnsmasq Role
=========

Installs and configures dnsmasq.

Requirements
------------

None

Role Variables
--------------

Variables are defined in defaults/main.yml

Example Playbook
----------------

To install and configure dnsmasq:

```yaml
---
- hosts: localhost
  connection: local
  roles:
    - mwadman.dnsmasq_roles.dnsmasq
```
