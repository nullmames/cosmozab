# cosmozab
Zabbix stuff for Cosmos Nodes

## Introduction
This is a collection of instructions, configurations and templates to integrate Zabbix monitoring with standard Cosmos Nodes running.

Configurations are based on Ubuntu 20.04 but should work on most Linux distributions.

# Install Agent and Configs
We will be using 

## Install zabbix-agent2
TBA

## Configure zabbix-agent2

## Install Configs

Wget config

```bash
sudo wget https://raw.githubusercontent.com/nullmames/cosmozab/main/zabbix_agent2.d/zab.userparameters.cosmos.conf \
/etc/zabbix/zabbix_agent2.d/
```

Restart agent
```bash
sudo systemctl restart zabbix-agent2
```