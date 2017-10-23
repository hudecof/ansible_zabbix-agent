# zabbix-agentd

This role install and configure the zabbix-agent service.


## Requirements
------------

- ansible: 2.1
- roles:
  - hudecof.zabbix-repo

Role Variables
--------------
Please readme the descriptions in the

  - defautls/main.yml
  - vars/main.yml

The variables in the `defautls/main.yml` could be overridden in the `host_vars`/`group_vars`.


## Dependencies

This role assumes using official zabbix repository. There are few differences between the official packaging and the upstream one.

If want to use the distribution package, you need to tweak the varilabes to fit your distribution.

## License

BSD

## Author Information

Peter Hudec
CNC, a.s.