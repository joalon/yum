Yum Server
=========

Install a yum server with httpd for all your local repository needs.

Requirements
------------

Needs the yum repositories to be downloaded before hosting.

Role Variables
--------------

protocol

http_port

ftp_port

local_mount_path

Example Playbook
----------------

    - hosts: yum
      roles:
         - { role: joalon.yum, protocol: "http", http_port: "80" }

Author Information
------------------

Written by Joakim Lönnegren (joakimlonnegren at gmail.com) / https://joalon.se/
