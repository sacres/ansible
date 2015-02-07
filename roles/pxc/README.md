Role Name
========

pxc -- build a galera/Percona-xtradb cluster

Requirements
------------

None

Role Variables
--------------

pxc -- see main.yml-redacted in ./defaults

Dependencies
------------

None

License
-------

Apache 2.0

Author Information
------------------

- Patrick "CaptTofu" Galbraith <patg@patg.net> Original 
- Steven Acres <steven@mcprohosting.com> Reworked
- Steven Acres <steven@swatteksystems.com> Revised

How do I use this?
------------------


1. Add three galera hosts to your ansible hosts/inventory file

    [db]
    host1
    host2
    host3

2. Copy ./defaults/main.yml-redacted to ./defaults/main.yml and amend vars

3. Run your playbook 

    ansible-playbook -i inventory/db db.yml
