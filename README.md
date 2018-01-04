Role Name
=========

Ansible role with configuration specific to a provider.


Role Variables
--------------
* `provider`: Virtual machine provider. One of `digital-ocean` or `qemu`.

Example Playbook
----------------

```yml
- hosts: localhost
  roles: 
    - pyslackers.provider
```

License
-------

MIT
