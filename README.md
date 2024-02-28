# Ansible Example

This is just a simple example of how Ansible, its roles, and variables work. This is simply meant for understanding how things are working.

*Note: The inventory file utilizes the localhost twice in inventory groups to show how group_vars work*

## Running

The `ansible.cfg` is setup to run as-is so simply run the following from within this directory:
```
ansible-playbook playbook.yml
```