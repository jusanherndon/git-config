git-config
=========

This role configues both git config and github cli

Requirements
------------

community.general

Role Variables
--------------

* user: name of linux user
* user_name: name associated with your github account
* user_email: email associated with your github account
* user_editor: name of default editor 
* user_mergetool: name of defualt merge tool
* user_conflictstyle: name of confilct style for default mergetool
* user_mergetool_prompt: bool

Dependencies
------------


Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

    - hosts: servers
      roles:
        vars_file:
          - "variables/variables.yml"
        - jusanherndon.git-config


License
-------

BSD

Author Information
------------------

