Node Exporter
=========

An Ansible role to install Prometheus Node Exporter on Linux servers.

Requirements
------------

None

Role Variables
--------------

- node_exporter_port: Port for the node exporter to listen on

Dependencies
------------

None

Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

    - hosts: servers
      roles:
         - { role: node_exporter_role, node_exporter_port: 9100 }

License
-------

BSD

Author Information
------------------

Ahmed Shibani <sheipani@gmail.com>