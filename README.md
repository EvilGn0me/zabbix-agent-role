Zabbix-Agent-Role
=========

This role installs zabbix agent from official repo.

This role can install modules.

you should add modules dictionary in zabbix_agent_vars:

~~~
modules:
  docker:
    name: 'docker'
    url: 'https://github.com/monitoringartist/zabbix-docker-monitoring/raw/gh-pages/ubuntu16/3.4/zabbix_module_docker.so'
~~~
