Debian-Hhvm
===========

HipHop Virtual Machine for PHP

Requirements
------------

This role requires a debian compliant system such as ubuntu.

Role Variables
--------------

No variables

Dependencies
------------

None

Example Playbook
----------------

    - hosts: servers
      roles:
         - { role: cowops.debian-php-hhvm }

Tasks
-----

  - Install [hhvm](http://www.hhvm.com/) as PHP
  - Setup with default php.ini

License
-------

BSD
