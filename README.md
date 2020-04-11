![Ansible Lint](https://github.com/johanneskastl/ansible-role-caasp_nfs_server_configuration/workflows/Ansible%20Lint/badge.svg)

caasp_nfs_server_configuration
=========

Configure a NFS server to create and share a directory `/caasp_data`.

**Attention**:
This is shared to the whole subnet the node is in, so this is intended for testing purposes only.

Requirements
------------

None.

Role Variables
--------------

`nfs_server_service`: Name of the nfs-server service, if this is not 'nfs-server.service'.

Dependencies
------------

None.

Example Playbook
----------------

    - hosts: servers
      roles:
         - { role: 'johanneskastl.caasp_nfs_server_configuration' }

License
-------

BSD-3-Clause

Author Information
------------------

I am Johannes Kastl, reachable via kastl@b1-systems.de.
