httpd
=========

A brief description of the role goes here.

Requirements
------------
None

Role Variables
--------------
Variable is coming from `vars/main.yml`
```yml
dest: "/var/www/html"
```

Dependencies
------------
None

Example Playbook
----------------
```yml
---
- name: Installing httpd
  hosts: webservers
  become: true
  roles:
    - httpd
```

License
-------

BSD

Author Information
------------------
Author: Lokesh Kamalay
