MYSQL
=========

Easy MYSQL configuration for ubuntu

Requirements
------------

none

Role Variables
--------------

1. `root_password`: by default : root
1. `user`: by default : user
1. `password` : by default : user
1. `database` : by default : def_db

Dependencies
------------

none

Example Playbook
----------------

    - hosts: servers
      roles:
         - virhi.mysql

License
-------

MIT

Author Information
------------------

http://github.com/virhi
