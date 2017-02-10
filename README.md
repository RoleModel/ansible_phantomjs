Ansible PhantomJS Role
=========

Installs PhantomJS 64-bit binary for versions 1.9.6+.

Role Variables
--------------

```yml
phantomjs_version: 2.1.1
```


Example Playbook
----------------

```yml
- hosts: servers
  roles:
    - { role: phantomjs, phantomjs_version: 2.1.1 }
```
