Role Name
=========

roles-lighthouse

Requirements
------------

Role installs lighthouse. 

Role Variables
--------------

| Variable name | Variable description |
|---------------|----------------------|
| lighthouse_dest | Template directory for storing installation scripts |
| hostport        | Port number on which was started lighthouse control panel|
 
How to install in subfolder **roles** of current project folder
---------------

ansible-galaxy role install --roles-path ./roles git+https://github.com/grigoryevpavel/roles-lighthouse.git

How to use role
----------------

  - hosts: servers
    roles:
        - { role: roles-lighthouse }

License
-------

MIT

Author Information
------------------

Pavel Grigoryev


