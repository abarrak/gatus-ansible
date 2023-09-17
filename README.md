Plik Ansible Role
=================
[![CI](https://github.com/abarrak/gatus-ansible-role/actions/workflows/test.yml/badge.svg)](https://github.com/abarrak/gatus-ansible-role/actions/workflows/test.yml)
[![Release](https://github.com/abarrak/gatus-ansible-role/actions/workflows/release.yml/badge.svg)](https://github.com/abarrak/gatus-ansible-role/actions/workflows/release.yml)

This is an ansible role to install and configure gatus.

[Gatus]() is a ...

Requirements
------------

Linux server.

Role Variables
--------------

The role contains default varibles in `defaults/main.yml`, and should be overriden as convenient.


Dependencies
------------

None.

Example Playbook
----------------

Install the role:

    ansible-galaxy install abarrak.gatus

Include it to run the setup tasks:

    - hosts: gatus-server
      import_role:
        name: abarrak.gatus

For plik configuration, override the [config template](https://github.com/abarrak/gatus-ansible-role/blob/main/templates/config.yml.j2) for gatus.

License
-------

MIT.

Author Information
------------------

Abdullah Barrak [(@abarrak).](https://github.com/abarrak)
