pyslackers.provider
===================

[![Build Status](https://travis-ci.org/ovv/ansible-role-provider.svg?branch=master)](https://travis-ci.org/ovv/ansible-role-provider)

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
