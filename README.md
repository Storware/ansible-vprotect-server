Role Name
=========

This ansible role installs Storware vProtect Server - management server that manages multiple vProtect Nodes (provided in a separate role). Find out more here: https://storware.gitbook.io/storware-vprotect

Requirements
------------

Target host - CentOS/RHEL 7 minimal with root permissions.

Role Variables
--------------

- `server_fqdn` - optional, as it is set from hostname if not provided
- `db_password` - password for root account to access vProtect DB; regular vprotect user will have generated password

Dependencies
------------

None

Example Playbook
----------------

 - hosts: server
   roles:
   - xe0nic.ansible\_vprotect\_server

License
-------

BSD

Author Information
------------------
