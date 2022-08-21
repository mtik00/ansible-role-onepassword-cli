mtik00.onepassword_cli
======================

An ansible role to install and configure the 1Password CLI tool.

Requirements
------------

This role has no other requirements.

Role Variables
--------------

Varables are defined in `default.main.yml`:
* `apt_cache_valid_time`: How long the apt cache is valid for (needed to install `git`)
* `one_password_gpg_key`: The location to store the 1Password GPG key

Dependencies
------------

This role has no dependencies.

Example Playbook
----------------

    - hosts: servers
      roles:
         - { role: mtik00.onepassword_cli }

License
-------

MIT
