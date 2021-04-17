Add docker network
=========

Add docker network

Role Variables
--------------

| Variables: | Defaults values: |
|------------|:----------------:|
| docker_net | my_network       |
| subnet     | 172.1.1
| prefix     | 24


Dependencies
------------

d1t5u.docker_install

Example Playbook
----------------

    - hosts: servers
      roles:
         - d1t5u.docker_network

License
-------

MIT

Author Information
------------------

Tsurganov Dmitry
