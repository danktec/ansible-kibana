# Ansible Kibana Role

## What it does
Installs Kibana and config

## Usage
Install in roles and call from playbook with:

```
- hosts: kibana_servers
  roles:
   - kibana
```

## Notes
uses its own embedded version of node.

prereqs include:
libstdc++.i686
glibc.i686 
