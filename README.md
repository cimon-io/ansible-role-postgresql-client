PostgreSQL-Client role
======================

An ansible role that installs postgresql-client package.

Requirements
------------

None

Role Variables
--------------

Available variables are listed below, along with default values (see `defaults/main.yml`):

```yaml
postgresql_client_version: "9.6"
```

Postgresql-client package version which will be installed.


Dependencies
------------

None

Example Playbook
----------------

```yaml
- hosts: servers
  roles:
    - role: postgresql-client
      postgresql_client_version: 9.6
```

License
-------

MIT

