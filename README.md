Ansible PhantomJS Role
=========

Installs PhantomJS 64-bit binary


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
