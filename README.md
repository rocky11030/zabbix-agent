Table of Contents
================
可以安装在ubuntu和centos客户端
参数可以在 zabbix-agent.yml 设定
以下为默认设置:设定了zabbix_server的IP地址为10.2.8.230,zabbix_version为3.0

```
---
- hosts: zabbix-agent
  roles:
    - role: ../../zabbix-agent
      agent_server: 10.2.8.230
      agent_serveractive: 10.2.8.230
      zabbix_version: 3.0
```
