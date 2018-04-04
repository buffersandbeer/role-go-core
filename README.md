Golang Core
=========

Globally installs golang and configures for use

Requirements
------------

None

Role Variables
--------------

None

Dependencies
------------

- buffersandbeer.role-core
- buffersandbeer.role-dev-core

Example Playbook
----------------


    - hosts: servers
      roles:
         - buffersandbeer.role-core
         - buffersandbeer.role-dev-core
         - buffersandbeer.role-go-core

License
-------

BSD

Author Information
------------------

I am buffersandbeer
