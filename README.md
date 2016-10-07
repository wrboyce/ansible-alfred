wrboyce.alfred
==============

[![Build Status](https://travis-ci.org/wrboyce/ansible-alfred.svg)](https://travis-ci.org/wrboyce/ansible-alfred)

Install and Configure Alfred.app

Requirements
------------

* [Homebrew](http://brew.sh)

Role Variables
--------------

| variable | description |
|---|---|
| alfred_pp_email | sets the power pack email address |
| alfred_pp_code | sets the power pack license code |
| alfred_pp_hash | sets the power pack registration hash |
| alfred_prefs_folder | sets the alfred prefs sync folder |


Example Playbook
----------------

    - hosts: macos-workstations
      roles:
         - wrboyce.alfred

License
-------

Apache 2.0