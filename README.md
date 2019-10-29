`dockercheck` Ansible role
=========

Install and configure [Dockercheck](https://github.com/StuartApp/dockercheck)


Role Variables
--------------

### `dockercheck_version`

Which `dockercheck` version to install.
Default value: "v0.1"

### `dockercheck_svc_user`

The user that is going to run the service
Default value: "docker"

### `dockercheck_svc_group`

The group that is going to run the service
Default value: "docker"

### `dockercheck_svc_state`

Set the service state
Default value: started

### `dockercheck_svc_enabled`

Enable or disable the service at boot time
Default value: yes

Dependencies
------------

Currently there are no dependencies

Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

    - hosts: servers
      roles:
         - { role: dockercheck }

License
-------

GPLv3

Author Information
------------------

This role was created while working for Stuart Delivery. [We are hiring!](https://stuart.com/careers/)
