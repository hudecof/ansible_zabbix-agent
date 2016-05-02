zabbix-agentd
=================

This roles enables users to configure the zabbix-agent service.

For supported platform it adds also the zabbix official repository.

- https://www.zabbix.com/documentation/2.0/manual/installation/install_from_packages
- https://www.zabbix.com/documentation/2.2/manual/installation/install_from_packages
- https://www.zabbix.com/documentation/2.4/manual/installation/install_from_packages


Requirements
------------
This role requires Ansible 1.4 or higher, and platform requirements are listed
in the metadata file. It should work also with lower version, but I have never tested it.

Role Variables
--------------
Please readme the descriptions in the

  - defautls/main.yml
  - vars/main.yml

The variables in the `defautls/main.yml` could be overridden in the `host_vars`/`group_vars`.
The variables in the `vars/main.yml` are global for all managed servers.


Dependencies
------------

This role assumes uning official zabbix repository. Thera are few differenciec between the official packaging and the upstream one.


License
-------

BSD

Author Information
------------------

Peter Hudec
