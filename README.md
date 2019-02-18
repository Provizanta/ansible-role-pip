Pip
=========

Python package manager.

Requirements
------------

None

Role variables 
--------------

    python_version: <python version for the packager>
    packages: <list of python packages with an optional version to be installed>
      - ...

Dependencies
------------

None

Example Playbook
----------------

    - hosts: localhost
      roles:
        - role: pip
          vars:
            python_version: 3
            packages:
              - basic-apps 

License
-------

MIT

Author Information
------------------

Tibor Csoka
