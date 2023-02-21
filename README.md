joenyland.updates
=========================

[![CI](https://github.com/JoeNyland/ansible-updates-role/actions/workflows/ci.yml/badge.svg)](https://github.com/JoeNyland/ansible-updates-role/actions/workflows/ci.yml)

Installs system updates.

Requirements
------------

None.

Role Variables
--------------


### `updates_reboot_allowed`

Should the host be rebooted after installing updates that require a reboot to be applied?

Dependencies
------------

None.

Example Playbook
----------------

```yaml
- hosts: server
  roles:
    - joenyland.updates
```

License
-------

MIT

Author Information
------------------

⌨️ with ❤️ by [Joe Nyland](https://joe.nyland.io)
