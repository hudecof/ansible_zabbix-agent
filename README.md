# zabbix-agentd

This role install and configure the zabbix-agent service.



## Requirements
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


## Dependencies

This role assumes using official zabbix repository. There are few differenciec between the official packaging and the upstream one.

- hudecof.zabbix-repo

If want to use the distibution package, you need to tweak the varilabes to fit your distribution.

## License

BSD

## Author Information

Peter Hudec
CNC, a.s.
Slovakia
