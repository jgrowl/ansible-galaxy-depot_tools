depot_tools
========

This role installs [depot_tools](http://www.chromium.org/developers/how-tos/install-depot-tools). [depot_tools](http://www.chromium.org/developers/how-tos/install-depot-tools) is a package of scripts to manage checkouts and code reviews for Chromium and Chromium OS.

Role Variables
--------------

A description of the settable variables for this role should go here, including any variables that are in defaults/main.yml, vars/main.yml, and any variables that can/should be set via parameters to the role. Any variables that are read from other roles and/or the global scope (ie. hostvars, group vars, etc.) should be mentioned here as well.


Example Playbook
-------------------------

    - hosts: all
      roles:
         - { role: jgrowl.depot_tools }

License
-------

MIT

Author Information
------------------

[Jonathan Rowlands](https://github.com/jgrowl)
