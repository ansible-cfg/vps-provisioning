# vps-provisioning

A set of ansible playbooks designed to provision a VPS using the steps details [in this guide](https://github.com/drduh/Debian-Privacy-Server-Guide). You'll need a server (be that a VPS, VM, etc) to be able to run these playbooks.

## Run the playbooks

Edit the hosts file to change the domain to your own VPS, and then run ansible:
```
ansible-playbook -i hosts site.yml --private-key /path/to/your/key
```

