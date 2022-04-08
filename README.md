## Ansible playbook for automation home server deployment

to use script for your needs:
- create ssh key pair
- create hosts file
- encrypt your pihole and root password with ansible-vault
```
[home]
main_home_server ansible_host=your_server_ip
```
- run:
```
ansible-playbook main.yml --ask-vault-pass
```