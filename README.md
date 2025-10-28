Vector ansible role
=========

This role deploys Vector (is a high-performance, open-source observability data pipeline)

Requirements
------------


Role Variables
--------------


Dependencies
------------


Example Playbook
----------------
```bash
- name: Deploy Vector
  hosts: vector
  become: true
  roles:
    - vector-role
```

License
-------

MIT

Author Information
------------------

KMke Kolmykov
