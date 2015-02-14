# My Ansible Playbooks
My perosnal [Ansible](http://docs.ansible.com/) playbooks

##Configuration

##[Ansible configuration file](http://docs.ansible.com/intro_configuration.html)
You need the Ansible config file called 'ansible.cfg' with content as follows:

    [defaults]
    hostfile       = ./inventory/inventory.ini

##[Inventory](http://docs.ansible.com/intro_inventory.html)
Create inventory file in folder inventory called 'inventory.ini' with your list of servers

    admin@example.com:22

##Usage
- Upgrade server: `$ ansible-playbook playbooks/upgrade.yml`
