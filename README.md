terraform
=========

Role to install terraform using tfenv

Requirements
------------

- Only tested with CentOS7 and RHEL7
- THe Internet connection is required for cloning tfenv repository

Role Variables
--------------

version

Dependencies
------------

- Role create-terraform-user should be executed beforehand

Example Playbook
----------------

    - hosts: servers
      roles:
         - { role: terraform }

License
-------

BSD

Author Information
------------------

nm7-jp
