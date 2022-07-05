Ansible Role: ansible_role_epel
=========

An Ansible role that installs EPEL repositories on supported Red Hat Enterprise Linux-based distributions.

<ul>
<li>CentOS 7/8
<li>Red Hat Enterprise Linux 7/8
</ul>

Requirements
------------

This role needs the following collections:
* community.general.rhsm_repository  

Role Variables
--------------

This role has no user configurable variables.


Dependencies
------------

This role has no external dependencies.

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