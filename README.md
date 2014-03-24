authoritative_dns
=================

This roles enables users to configure the zabbix-agent service.

For supprted platform ist adds aleo the zabbix oficial repository.

- https://www.zabbix.com/documentation/2.0/manual/installation/install_from_packages
- https://www.zabbix.com/documentation/2.2/manual/installation/install_from_packages


Requirements
------------
This role requires Ansible 1.4 or higher, and platform requirements are listed
in the metadata file. It should work also with lower version, but I have never tested it.

Role Variables
--------------
Please readme the descriptions in the

  - defautls/main.yml
  - vars/main.yml

The variables in the `defautls/main.yml` could be overriden in the `host_vars`/`group_vars`.
The variables in the `vars/main.yml` are global for all managed servers.

Dependencies
------------

None

License
-------

BSD

Author Information
------------------

Peter Hudec
