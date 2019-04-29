Ansible Role: SpotBugs
=========

Install SpotBugs for CentOS and Ubuntu linux.

Requirements
------------

None.

Role Variables
--------------

Here is the list of all variables for this role.
```yml
# SpotBugs version
spotbugs_version: 3.1.12
```


Dependencies
------------

This role depends on:

* redtail83.java_gui


Example Playbook
----------------

Both CentOS 7 and Ubuntu 16.04:

    - hosts: servers
      roles:
         - { role: redtail83.spotbugs }

License
-------

MIT
