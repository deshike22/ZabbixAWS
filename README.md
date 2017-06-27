# ZabbixAWS
Infrastructure as a code for Zabbix in AWS

## Zabbix_Proxy_CloudFormation.json.template
This will deploy a Zabbix proxy including mysql server inside the specified ec2 instance. It is required to specify VPC id and Subnet Id for placing the proxy. Also it will ask for Zabbix server IP which will then configure both Zabbix proxy and Zabbix agent.
