Role Name
=========

An ansible role to manage bashrc profiles

Requirements
------------

None

Role Variables
--------------

````
---
# defaults file for ansible-bashrc
bashrc_backups: true  #defines if backups should be taken when managing bashrc....default here is true..
bashrc_enable_color_prompt: false  #defines if color prompts are to be defined or not when bashrc_modify_default_settings is true
bashrc_modify_default_settings: false  #defines if settings defined in template are enabled which are not defaults
enable_bashrc_management: false  #defines if bashrc is managed or not
````

Dependencies
------------

None

Example Playbook
----------------

    - hosts: servers
      roles:
         - { role: mrlesmithjr.bashrc }

License
-------

BSD

Author Information
------------------

Larry Smith Jr.
- @mrlesmithjr
- http://everythingshouldbevirtual.com
- mrlesmithjr [at] gmail.com
