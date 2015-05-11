Role Name
=========

The goal is to deploy a Mac using mostly Homebrew.  Bonus goal would be to do post install setup like adding Github and Amazon creds.

Requirements
------------

Ansible
Homebrew installed -   
  _ruby -e "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install)"_
  
Github Auth'd
Github API token set

Role Variables
--------------

mac_username: local user on the Mac that is logged in and running this playbook.


Dependencies
------------



Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

    - hosts: servers
      roles:
         - { role: username.rolename, x: 42 }

License
-------

BSD

Author Information
------------------

Chris Livermore
[@e30chris](https://twitter.com/e30chris)
[Sandors Systems Scribbles](http://sandorsscribbl.es/)
