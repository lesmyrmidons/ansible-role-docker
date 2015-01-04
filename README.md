ansible-role-docker
===================

[![Build Status](https://travis-ci.org/lesmyrmidons/ansible-role-docker.svg?branch=master)](https://travis-ci.org/lesmyrmidons/ansible-role-docker)

Ansible Role - Docker on Debian.

## Requirements

None.

## Role Variables

For Debian :

To change the list of packages to install:

	docker_packages:
	  - docker.io

## Example Playbook

    - hosts: docker
      roles:
        - { role: lesmyrmidons.docker }

## License

MIT / BSD
