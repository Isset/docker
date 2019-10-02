isset.docker [![pipeline status](https://gitlab.isset.nl/operations/isset.docker/badges/master/pipeline.svg)](https://gitlab.isset.nl/operations/isset.docker/commits/master)
=========

_Installs docker._

Requirements
------------

Ansible 2.6 or above is highly recommended.

Role Variables
--------------

    isset_docker_state: present
    isset_docker_key_url: https://download.docker.com/linux/ubuntu/gpg
    isset_docker_key_id: "0EBFCD88"
    isset_docker_package: docker-ce
    isset_docker_repo_filename: docker
    isset_docker_repo: "deb [arch=amd64] https://download.docker.com/linux/ubuntu bionic stable"
    isset_docker_daemon: '{}'

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
