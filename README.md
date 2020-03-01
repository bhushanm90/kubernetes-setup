Role Name
=========
ME
kubernetes-setup

A brief description of the role goes here.


#Supported OS version
----------------------

RedHat Family
CentOS6/7
 
Debian Family
Ubuntu-16/17

Requirements
------------

Any pre-requisites that may not be covered by Ansible itself or the role should be mentioned here. For instance, if the role uses the EC2 module, it may be a good idea to mention in this section that the boto package is required.

Role Variables
--------------

A description of the settable variables for this role should go here, including any variables that are in defaults/main.yml, vars/main.yml, and any variables that can/should be set via parameters to the role. Any variables that are read from other roles and/or the global scope (ie. hostvars, group vars, etc.) should be mentioned here as well.

Dependencies
------------

A list of other roles hosted on Galaxy should go here, plus any details in regards to parameters that may need to be set for other roles, or variables that are used from other roles.

Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

## Global YML file 
------------------

- hosts: master
  become: true
  roles:
    - kubernetes-setup


ansible-playbook common.yml
=============================================================================

INVENTORY: example
-----------------

[cluster]
3.88.33.75
3.95.151.123


[master]
3.88.33.75


[worker]
3.95.151.123



License
-------

Private
===============================================================
Author Information
------------------
Bhushan B Mahajan
-: ANSIBLE Ninja

It's hard to beat a person who never Gives up !!!


Contact: bmahajan0@gmail.com 


Please feel free to contact me if you need any further information.
==================================================================
