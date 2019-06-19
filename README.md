Role Name
=========

usermgmt

Tasks:

1. Create Linux user and its home directory
2. Add its public key in the target host know_hosts file
3. Add user to Sudo group

Requirements
------------
Please make sure remote user has  NOPASSWD SUDO rights.
Update user information  in /var/users.yml with or without sudo access as per requirement
Put user public key in files/ in <username>.pub format RSA 2048 
 

Role Variables
--------------

A description of the settable variables for this role should go here, including any variables that are in defaults/main.yml, vars/main.yml, and any variables that can/should be set via parameters to the role. Any variables that are read from other roles and/or the global scope (ie. hostvars, group vars, etc.) should be mentioned here as well.

Dependencies
------------

A list of other roles hosted on Galaxy should go here, plus any details in regards to parameters that may need to be set for other roles, or variables that are used from other roles.

Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

    - hosts: servers
      roles:
         - { role: username.rolename, x: 42 }
         
Run playbook
-------------
ansible-playbook -i <host path /env/..> usermgmt.yml 

ansible-play

Author Information
------------------
Amit Tiwari
# ansible_usermgmt
