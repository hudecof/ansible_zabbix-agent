# zabbix-agentd

This role install and configure the zabbix-agent service.


## Requirements
------------

- ansible: 2.1
- roles:
  - hudecof.zabbix_repo

## Role Variables

Please readme the descriptions in the

  - `defautls/main.yml`
  - `templates/zabbix_agentd.conf.j2`

The variables in the `defautls/main.yml` could be overridden in the `host_vars`/`group_vars`.


## Dependencies

This role assumes using official zabbix repository. There are few differences between the official packaging and the upstream one.

If want to use the distribution package, you need to tweak the varilabes to fit your distribution.

## Example

### host/group variables
```
zabbix_agent_include_prefix: "{{ playbook_dir }}/files/zabbix/include"
zabbix_agent_include_list: []

zabbix_agent_scripts_prefix: "{{ playbook_dir }}/files/zabbix/include/scripts"
zabbix_agent_scripts_list: []

zabbix_agent_config_Server:
  - 192.168.10.10
  - 127.0.0.1
zabbix_agent_config_ServerActive:
  - 192.168.10.10
zabbix_agent_config_ListenIP:
  - 0.0.0.0
  - ::0
zabbix_agent_config_StartAgents: 3
zabbix_agent_config_LogFileSize: 1
```

## License

BSD

## Author Information

Peter Hudec