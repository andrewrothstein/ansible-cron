andrewrothstein.cron
=========
[![Build Status](https://travis-ci.org/andrewrothstein/ansible-cron.svg?branch=master)](https://travis-ci.org/andrewrothstein/ansible-cron)

Installs cron/crontab

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
    - andrewrothstein.cron
```

License
-------

MIT

Author Information
------------------

Andrew Rothstein <andrew.rothstein@gmail.com>
