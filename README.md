docker
========

This role is responsible for installing docker and all dependencies.

[![Build Status](https://drone-opsdev.rax.io/github.com/rack-roles/docker/status.svg?branch=master)](https://drone-opsdev.rax.io/github.com/rack-roles/docker)

Requirements
------------

This role doesn't require anything beyond the standard modules.

Role Variables
--------------

The following variables are defined, and their default values are listed.

* `docker_apt_key_url`: http://keyserver.ubuntu.com/pks/lookup?op=get&search=0xD8576A8BA88D21E9
* `docker_apt_key_id`: A88D21E9
* `docker_pkg_name`: lxc-docker
* `docker_registry`: False

Dependencies
------------

None

Example Playbook
-------------------------

Here is a simple example playbook:

    ---
    - hosts: all
      roles:
        - { role: Rackspace_Automation.docker, docker_registry: True }

License
-------

BSD

Author Information
------------------

[Rackspace - the open cloud company](http://rackspace.com)

Ask about our DevOps Automation Service - [www.rackspace.com/devops](http://rackspace.com/devops)
