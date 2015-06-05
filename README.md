PhantomJS
=========

Installs PhantomJS 64-bit binary


Role Variables
--------------

```
phantomjs_version: 1.9.8
```


Example Playbook
----------------

```
- hosts: servers
  roles:
     - { role: phantomjs, phantomjs_version: 1.9.8 }
```
