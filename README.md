Role Name
=========

The goal is to deploy a Mac using mostly Homebrew.  Bonus goal would be to do post install setup like adding Github and Amazon creds.

Requirements
------------

This playbook is run from a local connection via:

```
ansible-playbook -i hosts site.yml --ask-sudo-pass
```


Homebrew installed - 
  _ruby -e "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install)"_

Ansible installed via Brew
  _brew install ansible --HEAD_

Github Auth'd
  _cat ~/.ssh/id_rsa.pub & add that to GitHub_

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

GNU General Public License v2.0

Author Information
------------------

Chris Livermore
[@e30chris](https://twitter.com/e30chris)
[Sandors Systems Scribbles](http://sandorsscribbl.es/)
