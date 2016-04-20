awscli
======

[![Build Status](https://travis-ci.org/kbrebanov/ansible-awscli.svg?branch=master)](https://travis-ci.org/kbrebanov/ansible-awscli)

Installs awscli

Requirements
------------

This role requires Ansible 1.9 or higher.

Role Variables
--------------

| Name           | Default | Description                         |
|:---------------|:--------|:------------------------------------|
| awscli_version | 1.10.4  | Default installed version of awscli |

Dependencies
------------

- kbrebanov.pip

Example Playbook
----------------

Install awscli
```
- hosts: all
  roles:
    - kbrebanov.awscli
```

License
-------

BSD

Author Information
------------------

Kevin Brebanov
