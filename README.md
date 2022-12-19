Ansible role: Prometheus
=========

Install prometheus on x86_64 systems with systemd >= 232

Requirements
------------

* ansible-core >= 2.13 -- will probably work with ansible version >= 2.10, not tested
* systemd >= 232
* x86_64 architecture

Role Variables
--------------

This role has multiple variables. The descriptions and defaults for all these variables can be found in the [defaults/main.yml](./defaults/main.yml) file.

Dependencies
------------

None.

Example Playbook
----------------

    - hosts: servers
      roles:
         - role: dragomirr.prometheus
           prometheus_db_dir: /opt/prometheus

License
-------

MIT
