Role Name
========

Common role that runs on most if not all boxen.

Requirements
------------


Role Variables
--------------


Dependencies
------------


How To Use
-------------------------

- 'ansible' with this role and most others in this repo refers to the 'mgmt' box/group as well as the designated user for ansible mgmt.

- Add pub keys for ansible/root into ./files/{root,ansible}-authorized_keys

- Populate ./templates/hosts.j2 with your hosts/groups.

- ansible-playbook -i inventory/foo common.yml

License
-------

BSD

Author Information
------------------

- Steven Acres 2015 <steven@swatteksystems.com>
- Steven Acres 2014 <steven@mcprohosting.com>
