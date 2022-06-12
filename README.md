Vector role
=========

Install Vector

Requirements
------------

—

Role Variables
--------------

vector_ver: "0.21.2"

vector_download_dir: "/vectordistrib"

vector_dir: "/vector"

vector_data: "/var/lib/vector"

Dependencies
------------

—

Example Playbook
----------------

```yaml
    - hosts: servers
      roles:
         - vector-role
```

License
-------

BSD

Author Information
------------------

Alexey Khrapov,  Netology, devops-13
