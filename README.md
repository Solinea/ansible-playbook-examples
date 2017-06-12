# ansible-playbook-examples

# Ansible Roles 
 The ansible roles are not resident in this repository.  They must be pulled from other repositories.  To do that. run the following command *inside* the roles directory
```commandline
$ ansible-galaxy install -r ./install_roles.yml -p .
```

# Ansible Playbooks
 Directories other than the `roles` directory contains a vagrantfile and a playbook.  The vagrantfile uses the playbook as its provisioner. See the `README.md` in each subdirectory for details.
