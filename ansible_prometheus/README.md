### Prometheus install playbook
Prometheus server and node_exporter install started by supervisor(required supervisord installed).
## Overview
* Change defaults/main.yml 'prometheus_install_path','node_exporter_download_url',package version variables for your own software version befor your installation.
* Include or remove your tasks you needed in the tasks/main.yml.