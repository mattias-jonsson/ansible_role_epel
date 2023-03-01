Ansible Role: ansible_role_epel
=========

Installs EPEL repositories on the following distributions:

<ul>
<li>CentOS 7/8
<li>Red Hat Enterprise Linux 7/8
</ul>

Requirements
------------

This role is dependent on the following Ansible collections:

`community.general.rhsm_repository`


Role Variables
--------------

This role has no user configurable variables.


Dependencies
------------

None.

Example Playbook
----------------

    - hosts: servers

      roles:
         - role: ansible_role_epel

License
-------

MIT

Author Information
------------------

Mattias Jonsson