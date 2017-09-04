### Overview
Change your linux host hostname by ansible
### Usage
Change your ansible  inventory file like this:  
Ansible inventory hosts example:  
```
[server_group]
'hostname1' ansible_host='172.30.100.81'
'hostname2' ansible_host='172.30.100.82'
'hostname3' ansible_host='172.30.100.83'
```