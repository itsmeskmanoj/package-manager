# esetup

This sets up the server to adhere to the internally published standard of directory layout/structure specification.
This role also installs the supervisor program, intended to currently serve as our current choice of application manager/orchestrator.

Requirements
------------


Role Variables
--------------

Since this role creates the janastu service user, the setup of the user  
requires the password must be provided.
janastu_servu_passwd: *the password for the janastu service user. (hashed)*


Example Usage
-------------

    - hosts: servers
      import_roles:
        name: esetup

License
-------

Proprietary

Author Information
------------------

DevOps Team, janastu Networks
