Vim
=========

Install and configure a local instance of Vim with some plugins. This is an example role used in a series of Ansible articles for Enable SysAdmin:

[8 steps to developing an Ansible role in Linux](https://www.redhat.com/sysadmin/developing-ansible-role)

Requirements
------------

Linux OS

Role Variables
--------------

A description of the settable variables for this role should go here, including any variables that are in defaults/main.yml, vars/main.yml, and any variables that can/should be set via parameters to the role. Any variables that are read from other roles and/or the global scope (ie. hostvars, group vars, etc.) should be mentioned here as well.

Dependencies
------------

None

Example Playbook
----------------

Use the role like this:

    - name: Configure Vim using role
      import_role:
        name: vim

License
-------

MIT

Author Information
------------------

Ricardo Gerardi

