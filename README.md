docker
========

This role is responsible for installing docker and all dependencies.

Requirements
------------

This role doesn't require anything beyond the standard modules.

Role Variables
--------------

The following variables are defined, and their default values are listed.

* `docker_apt_key_url`: http://keyserver.ubuntu.com/pks/lookup?op=get&search=0xD8576A8BA88D21E9
* `docker_apt_key_id`: A88D21E9
* `docker_pkg_name`: lxc-docker

Dependencies
------------

A list of other roles hosted on Galaxy should go here, plus any details in regards to parameters that may need to be set for other roles, or variables that are used from other roles.

Example Playbook
-------------------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

    - hosts: servers
      roles:
         - { role: username.rolename, x: 42 }

License
-------

BSD

Author Information
------------------

Justin Phelps
