Ansible role: youtube-dl
========================

[![Build Status](https://travis-ci.org/hedii/ansible-role-youtube-dl.svg?branch=master)](https://travis-ci.org/hedii/ansible-role-youtube-dl)

Installs [youtube-dl](https://github.com/rg3/youtube-dl) on any Linux or UNIX system.

Youtube-dl is a small command-line program to download videos from YouTube.com and other video platforms.

Requirements
------------

None.

Role Variables
--------------

Available variables are listed below, along with default values (see `defaults/main.yml`)

```yml
# The path where youtube-dl executable will be installed.
# It is recommended to not change this path.
youtubedl_executable_path: "/usr/local/bin/youtube-dl"

# Do we need to update youtube-dl if it is already installed?
youtubedl_update: false
```


Dependencies
------------

None.

Example Playbook
----------------
```yml
- hosts: servers
  roles:
    - hedii.youtube-dl
```

License
-------

MIT

Author Information
------------------

[Hedi Chaibi](https://hedichaibi.com)
