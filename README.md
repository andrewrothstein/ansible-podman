andrewrothstein.podman
=========
[![Build Status](https://travis-ci.org/andrewrothstein/ansible-podman.svg?branch=master)](https://travis-ci.org/andrewrothstein/ansible-podman)

Installs [Podman](https://podman.io/)

Requirements
------------

See [meta/main.yml](meta/main.yml)

Role Variables
--------------

See [defaults/main.yml](defaults/main.yml)

Dependencies
------------

See [meta/main.yml](meta/main.yml)

Example Playbook
----------------

```yml
- hosts: servers
  roles:
    - andrewrothstein.podman
```

License
-------

MIT

Author Information
------------------

Andrew Rothstein <andrew.rothstein@gmail.com>
