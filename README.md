WARNING: This role is no longer maintained !!!
==============================================

You are strongly encouraged to switch to the new roles stack on https://github.com/ElaoInfra
--------------------------------------------------------------------------------------------

By the way, this role will remain available on https://github.com/ElaoLegacy
----------------------------------------------------------------------------


Ansible Role - Bower
====================

A bower role to install bower on elao symfony standard vagrant box


Requirements
------------

This role only run on elao symfony standard vagrant box. See https://vagrantcloud.com/elao/symfony-standard-debian

Role Variables
--------------

    elao_bower_version: '>0'  # Bower version


Example Playbook
----------------

    - hosts: servers
      roles:
         - { role: elao.bower }


License
-------

MIT


Author Information
------------------

http://www.elao.com/
