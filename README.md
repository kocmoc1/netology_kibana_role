Role Name
=========

Install Kibana

Requirements
------------

No special requirements.

Role Variables
--------------

Default: 
elk_stack_version: "7.14.0"

Vars:
kibana_version: "{{ elk_stack_version }}" 


Dependencies
------------
Depends on: 
```
  - src: git@github.com:netology-code/mnt-homeworks-ansible.git
    scm: git
    version: "2.1.4"
    name: elastic 
```



Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

    - hosts: servers
      roles:
         - { role: username.rolename, x: 42 }

License
-------

BSD

kocmoc1
------------------

Email: kocmoc1@gmail.com
