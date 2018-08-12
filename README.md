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
spotbugs_version: 3.1.3
```


Dependencies
------------

This role depends on:

* redtail83.oraclejdk8


Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

    - hosts: servers
      roles:
         - { role: redtail83.spotbugs }

License
-------

MIT
