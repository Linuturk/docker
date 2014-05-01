docker
========

This role is responsible for installing docker and all dependencies.

[![Build Status](http://drone.onitato.com/github.com/rack-roles/docker/status.svg?branch=master)](http://drone.onitato.com/github.com/rack-roles/docker)

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

A list of other roles hosted on Galaxy should go here, plus any details in regards to parameters that may need to be set for other roles, or variables that are used from other roles.

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

Justin Phelps
