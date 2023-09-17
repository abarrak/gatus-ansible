Gatus Ansible Role
=================
[![CI: Lint](https://github.com/abarrak/gatus-ansible/actions/workflows/lint.yml/badge.svg)](https://github.com/abarrak/gatus-ansible/actions/workflows/lint.yml)
[![CI: Tests](https://github.com/abarrak/gatus-ansible/actions/workflows/test.yml/badge.svg)](https://github.com/abarrak/gatus-ansible/actions/workflows/test.yml)
[![Release](https://github.com/abarrak/gatus-ansible/actions/workflows/release.yml/badge.svg)](https://github.com/abarrak/gatus-ansible/actions/workflows/release.yml)

This is an ansible role to install and configure gatus.

[Gatus](https://github.com/TwiN/gatus) is an utomated developer-oriented status page.

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

    - hosts: gatus
      import_role:
        name: abarrak.gatus

A sample configuration [(config template)](https://github.com/abarrak/gatus-ansible/blob/main/templates/config.yml.j2) for gatus is used.

You can override for your setup or use [CI/CD offering in this repo.](https://github.com/abarrak/gatus-pipelines)

License
-------

MIT.

Author Information
------------------

Abdullah Barrak [(@abarrak).](https://github.com/abarrak)
