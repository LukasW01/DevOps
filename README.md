# DevOps

This repository contains Ansible playbooks for deploying various services and applications.

## Getting Started

Install Ansible & packages: 

```bash
# PIP3
pip install ansible ansible-lint molecule docker

# Ansible Galaxy
ansible-galaxy install -r requirements.yml --force
```

Run the playbooks

```bash
ansible-playbook -i inventory run.yml --vault-password-file vault.txt --become-password-file become.txt
```

## License

This program is licensed under the MIT-License. See the "LICENSE" file for more information
