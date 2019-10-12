Ansible role: pip
=========

[![Build Status](https://travis-ci.com/Provizanta/ansible-role-pip.svg?branch=master)](https://travis-ci.com/Provizanta/ansible-role-pip)

Python package manager.

Requirements
------------

None

Role variables
--------------

These variables are defined in [defaults/main.yml](./defaults/main.yml):

    pip_version: 3
    pip_packages: []

Dependencies
------------

None

Example Playbook
----------------

    - hosts: localhost
      roles:
        - role: pip
          vars:
            pip_version: 3
            pip_packages:
              - basic-apps
              - name: datetime
                state: absent

License
-------

MIT

Author Information
------------------

Tibor Csóka
