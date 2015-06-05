Ansible PhantomJS Role
=========

Installs PhantomJS 64-bit binary for versions 1.9.6+.

**Note**, precompiled binaries for PhantomJS 2 are not available for linux yet, so you'll need to compile those manually.

Role Variables
--------------

```yml
phantomjs_version: 1.9.8
```


Example Playbook
----------------

```yml
- hosts: servers
  roles:
     - { role: phantomjs, phantomjs_version: 1.9.8 }
```
