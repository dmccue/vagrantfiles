vagrantfiles
============

The ./vagrant_chefclientserver/Vagrantfile contains two virtual machines:
```
#Will automatically install the chef server at http://192.168.50.2
cd ./vagrant_chefclientserver
vagrant up chefserver
```
```
#Chef client will be installed and will register itself with the chefserver
cd ./vagrant_chefclientserver
vagrant up chefclient
```
