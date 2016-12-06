Role Name
=========

An Ansible role to install Yarn package manager.

Requirements
------------
Node.JS is required to use Yarn, but not to install this role. You should ensure that a
correct version of Node.JS is available on the target system.


Role Variables
--------------
- `yarn_version`: (default: latest) The version of Yarn to install.


Dependencies
------------
None


Example Playbook
----------------
    - hosts: servers
      roles:
         - { role: munkyjunky.yarn, yarn_version: 0.16.1 }


License
-------
MIT
