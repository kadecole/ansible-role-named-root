Ansible Role: named-root
=========

Ansible role to check version and download if needed named.root file from http://www.internic.net/domain/

Requirements
------------

Using bind as DNS server.

Role Variables
--------------

Available variables are listed below, along with default values (see defaults/main.yml):

```
bind_config_basepath: /etc/bind
```

Used to set the directory where the downloaded named.root file will end up

```
named_root_md5: a1d7e8e26cf5697de1da80f1d6b52c67
named_root_sha256: f2dd3ea44863ccd6f2b3089c5b98432a2ce6615a0b4c7c4350cbc23666a5d32d
```

The MD5 and sha256 hash for the current named.root file found here: http://www.internic.net/domain/

Dependencies
------------

None

Example Playbook
----------------
```
    - hosts: servers
      roles:
         - { role: kadecole.ansible-role-named-root, x: 42 }
```

License
-------

BSD

Author Information
------------------

Kade Cole - https://github.com/kadecole/ansible-role-named-root
