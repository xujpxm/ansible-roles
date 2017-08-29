### Prometheus install playbook
Prometheus server and node_exporter install started by supervisor(required supervisord installed).
## Overview
* Change defaults/main.yml 'xxx_path'、'xxx_download_url' and version variables befor your installation.
* Include or remove your tasks you needed in the tasks/main.yml.
* Alertmanager: change your own smtp settting