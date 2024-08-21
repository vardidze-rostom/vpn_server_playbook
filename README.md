# VPN Server playbook
The playbook prepare a server for install a VPN or some site.

## How to run the playbook:

1. Install the necessary ansible roles:
```
ansible-galaxy role install -f -r requirements.yml
```
2. 
Run the playbook:
```
ansible-playbook vpn_server.yml
```
Or you can run with specific tag:
```
ansible-playbook vpn_server.yml --tag=vpn-server
```
