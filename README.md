Ansible Role: named-root
=========

Ansible role to check version and download if needed named.root file from http://www.internic.net/domain/

Requirements
------------

Using bind as DNS server.

Role Variables
--------------

A description of the settable variables for this role should go here, including any variables that are in defaults/main.yml, vars/main.yml, and any variables that can/should be set via parameters to the role. Any variables that are read from other roles and/or the global scope (ie. hostvars, group vars, etc.) should be mentioned here as well.

Dependencies
------------

None

Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

    - hosts: servers
      roles:
         - { role: kadecole.ansible-role-named-root, x: 42 }

License
-------

BSD

Author Information
------------------

Kade Cole - https://github.com/kadecole/ansible-role-smarthost
