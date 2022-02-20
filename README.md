# ansible-telegraf-install
Installing Telegraf Service Using Ansible on CentOS 7

# telegraf.conf Containing Plugin of:
> [[outputs.prometheus_client]], [[inputs.system]], [[inputs.cpu]], [[inputs.mem]], [[inputs.disk]], [[inputs.diskio]]


This playbook script works:
```
- Disable SELinux
- Disable Firewalld
- Add yum Package Manager Repositories 
- Make a backup file telegraf.conf to telegraf.bak
- Make File and Setup Configuration of telegraf.conf
- Start and Enable Telegraf Service
```
Telegraf Runs Port on **8086**

If you want to add different/some plugin, go to this link:
https://github.com/influxdata/telegraf/tree/master/plugins
