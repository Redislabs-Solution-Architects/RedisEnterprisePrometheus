# Monitoring Redis Enterprise with Prometheus

Example monitoring setup for Prometheus

## Pre-reqs
1. Ansible [installation](https://docs.ansible.com/ansible/latest/installation_guide/intro_installation.html)
2. Vagrant [installation](https://www.vagrantup.com/downloads.html)

## Setup Data collection

1. copy ansible/vars/main.yml.example to ansible/vars/main.yml and edit the file
2. install the necessary Ansible modules
```
cd ansible && rm -rf roles/* && ansible-galaxy install --roles-path roles -r requirements.yml
```
3. vagrant up
