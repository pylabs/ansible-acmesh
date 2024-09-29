acmesh
=========

Install acme.sh package.

Role Variables
--------------

```yaml
acmesh_version: ACME_VERSION
```

Dependencies
------------

- pylabs.sysbase

Example Playbook
----------------

```yaml
- hosts: servers
  vars:
    acmesh_version: "3.0.9"
  roles:
    - role: pylabs.acmesh
```

License
-------

MIT

Author Information
------------------

William Wu
