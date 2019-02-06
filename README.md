isset.docker [![pipeline status](https://gitlab.isset.nl/operations/isset.docker/badges/master/pipeline.svg)](https://gitlab.isset.nl/operations/isset.docker/commits/master)
=========

_Installs docker._

Requirements
------------

Ansible 2.5 or above is highly recommended.

Role Variables
--------------

	n/a

Dependencies
------------

    isset.package

Example Playbook
----------------

    - hosts: all
      become: yes
      roles:
        - role: isset.docker

License
-------

MIT

Author Information
------------------

Gerben Geijteman <gerben@isset.nl>
