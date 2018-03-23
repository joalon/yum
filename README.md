Yum Server
=========

Install a yum server with httpd for all your local repository needs.

Requirements
------------

Needs the yum repositories to be downloaded before hosting.

Role Variables
--------------

A description of the settable variables for this role should go here, including any variables that are in defaults/main.yml, vars/main.yml, and any variables that can/should be set via parameters to the role. Any variables that are read from other roles and/or the global scope (ie. hostvars, group vars, etc.) should be mentioned here as well.

Example Playbook
----------------

    - hosts: yum
      roles:
         - { role: joalon.yum, protocol: "http", port: "80" }

Author Information
------------------

Written by Joakim Lönnegren (joakimlonnegren at gmail.com) / https://joalon.se/
