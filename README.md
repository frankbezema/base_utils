dockpack.base_utils
=========

Utilities - These utilities are not present in the minimal install.

Requirements
------------

This role was built for  RedHat systems like RHEL 6, Centos 7.

Role Variables
--------------

base_utils:
  \- net-tools

Dependencies
------------

Might need EPEL depending on you choice.



Example Playbook
----------------
For a complete example with this role check out my buildserver:
git clone https://github.com/bbaassssiiee/buildserver.git

Example of how to use this role:

    - hosts: servers
      roles:
         - { role: dockpack.base_utils }

License
-------

MIT

Author Information
------------------
Bas Meijer @bbaassssiiee
