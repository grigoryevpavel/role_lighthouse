Role Name
=========

role_lighthouse

Description
------------

Role installs lighthouse. 

Role Variables
--------------

| Variable name | Variable description |
|---------------|----------------------|
| lighthouse_dest | Template directory for storing installation scripts |
| hostport        | Port number on which is started lighthouse control panel|
 

Role Dependencies
--------------

Role depends on role role_nginx.
 
How to install in subfolder **roles** of current project folder
---------------

ansible-galaxy role install --roles-path ./roles git+https://github.com/grigoryevpavel/roles-lighthouse.git

How to use role
----------------

  - hosts: servers
    roles:
        - { role: role_lighthouse }

Description
------------

Role installs lighthouse. 

Role Dependencies
--------------

Role depends on role role_nginx.
 
How to install in subfolder **roles** of current project folder
---------------
1. Install role_nginx:
    > ansible-galaxy role install --roles-path ./roles git+https://github.com/grigoryevpavel/roles-nginx.git
2.  Install role role_lighthouse:
    > ansible-galaxy role install --roles-path ./roles git+https://github.com/grigoryevpavel/roles-lighthouse.git

How to use role
----------------

  - hosts: servers
    roles:
        - { role: role_lighthouse }

License
-------

MIT

Author Information
------------------

Pavel Grigoryev


