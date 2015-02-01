helga
========

Ansible role for Helga, THE irc bot. https://github.com/shaunduncan/helga

TODO
----

1. fill out the rest of this document completely
2. fix plugin install to be defined by vars
3. replace specific vars with sane defaults

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
-------------------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

    - hosts: servers
    - { role: helga, helga_nick: olga, irc_host: chat.freenode.net }

License
-------

GPLv3

Variables
---------
 * `helga_version` - Can be set to a valid helga version number, or `latest` to always force a pip upgrade

Author Information
------------------

Justin Caratzas
bigjust@lambdaphil.es
