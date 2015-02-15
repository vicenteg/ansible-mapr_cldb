mapr-cldb
========

Installs the CLDB services.

Requirements
------------

None

Role Variables
--------------

```
proxy_env:
  http_proxy: http://1.2.3.4:3128
  https_proxy: http://1.2.3.4:3128
```

Dependencies
------------

None

Example Playbook
-------------------------

```
- hosts: cldb
  max_fail_percentage: 0
  roles:
    - mapr-cldb
```

License
-------

MIT

Author Information
------------------

vgonzalez@mapr.com
