# ansible-telegraf-install
Installing Telegraf Service on CentOS 7

This playbook script works:
- Disable SELinux
- Disable Firewalld
- Add yum Package Manager Repositories 
- Make a backup file telegraf.conf to telegraf.bak
- Make File and Setup Configuration of telegraf.conf
- telegraf.conf Containing Plugin of: [[outputs.prometheus_client]], [[inputs.system]], [[inputs.cpu]], [[inputs.mem]], [[inputs.disk]], [[inputs.diskio]]
- Start and Enable Telegraf Service

Telegraf Runs Port on **8086**
