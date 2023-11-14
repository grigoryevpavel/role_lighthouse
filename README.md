Role Name
=========

lighthouse-role

Requirements
------------

Role installs lighthouse. 

Role Variables
--------------

| Variable name | Variable description |
|-------------|---------------------|
| lighthouse_dest | Template directory for storing installation scripts |
|-----------------|-----------------------------------------------------|
| hostport        | Port number on which was started lighthouse control panel|
 
How to use role
----------------

  - hosts: servers
    roles:
        - { role: lighthouse-role }

License
-------

MIT

Author Information
------------------

Pavel Grigoryev


