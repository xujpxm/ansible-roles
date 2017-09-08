### Overview
Consul Cluster install and monitored by supervisord.
### Requirement
* supervisor
* consul
### Detail
* Change your consul argument in the defaults/main.yml file.
* You can use local consul package by uncomment task:"Upload Consul package from local disk" 
* Templates file is included by templates dir
* You can add another template in the 'consul-template.conf' by add another 'template' block.
* Put your custom consul template in the ansible templates dir and change the 'source_template' name in the 'defaults/main.yml' file. Here is my prometheus file_sd_configs file examples
*  If you only have one consul-template template file, please change the consul_template_install task and comment one 'create consul-template file' task
* I change consul-template template delimiter from "{{}}" to "{##}",because it is conflicts with the ansible j2 template syntax.You can define it in the consul-template config file.