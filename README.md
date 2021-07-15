ansible-supervisor-role
=========

Support for supervisor management for Debian

Requirements
------------

None

Role Variables
--------------
```YAML
##
# RabbitMQ server configuration
##
supervisor_enabled: false
supervisor_version: 5.7


```
Dependencies
------------

None

Example Playbook
----------------

    - hosts: servers
      roles:
         - { role: methorz.supervisor }

License
-------

BSD

Author Information
------------------

https://twitter.com/methor_z
