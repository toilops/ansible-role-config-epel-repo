Ansible Role Config EPEL Repo
=========
[![Build Status](https://travis-ci.org/toilops/ansible-role-config-epel-repo.svg?branch=master)](https://travis-ci.org/toilops/ansible-role-config-epel-repo)

Configure EPEL repository for Redhat Servers

Requirements
------------

Host must be in the Redhat family of operating systems.

Role Variables
--------------

Role does a simple yum install of epel-release

Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

```
    - hosts: servers
      tasks:
         - include_role:
             name: toilops.config-epel-repo
```
License
-------

MIT

Author Information
------------------

Find me on github [@BondAnthony](https://github.com/BondAnthony)
