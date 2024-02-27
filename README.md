`dockercheck` Ansible role
=========

Install and configure [Dockercheck](https://github.com/StuartApp/dockercheck)

Role Variables
--------------

Please check the [default file](defaults/main.yml) and the [variables file](vars/main.yml) to know how you can customize this role

Dependencies
------------

Currently there are no dependencies

Example Playbook
----------------

Include the role in your `requirements.yml` with:

```yaml
- src: stuart.dockercheck
  version: 0.2.0
```

Then you can call it in your playbook like this:

```yaml
    - hosts: servers
      roles:
        - { role: dockercheck }
      vars:
        - dockercheck_listen_port: 9500
```

License
-------

GPLv3

Author Information
------------------

This role was created while working for Stuart Delivery.