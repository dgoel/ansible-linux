# Ansible Playbook

Ansible playbooks to manage Linux-based workstations, primarily Ubuntu.


## Usage

```sh
# Set up everything
$ ansible-playbook --ask-become-pass local.yaml

# Set up tasks that match a tag
$ ansible-playbook --tags=dev --ask-become-pass local.yaml
```
