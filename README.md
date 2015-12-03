# ansible-wordpress

These are some simple ansible roles to get a wordpress instance up and runnin on a Ubuntu machine. Feel free to take this and use it however you like. I got a lot of help from the Ansible Docs, Digtial Ocean, and Google. 

####This playbook will build wordpress with:
* MySQL
* PHP5
* Apache2

There are some variables in the /roles/mysql/defaults directory that you will need to change for your own instance.

It might be worth looking into [Ansible Vault](http://docs.ansible.com/ansible/playbooks_vault.html) for passwords within these roles/playbooks.
