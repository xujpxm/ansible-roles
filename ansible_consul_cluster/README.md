### Overview
Consul Cluster install and monitored by supervisord
### Requirement
* supervisor
* consul
* the hosts in ansible inventory must have hostname for consul node_name, otherwise you must change your own node_name
### Detail
Change your consul argument in the defaults/main.yml file.
You can use local consul package by uncomment task:"Upload Consul package from local disk" 