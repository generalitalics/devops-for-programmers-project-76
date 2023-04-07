### Project of deploying Nginx Docker + Redmine Docker with using 2 Virtual Machines and Balancer
---

#### Hexlet tests and linter status:
[![Actions Status](https://github.com/generalitalics/devops-for-programmers-project-76/workflows/hexlet-check/badge.svg)](https://github.com/generalitalics/devops-for-programmers-project-76/actions)

:bangbang: Preliminarily use file vault-password in main directory with psw for Ansible Vault

- ___make install___ - install additional roles and collections
- ___make deploy___ - deploying Nginx Docker and Redmine Docker with configuration and add DataDog agent
- ___make decrypt___ - decrypting group_vars/webservers/vault.yml file with helps of Ansible Vault
- ___make encrypt___ - encrypting group_vars/webservers/vault.yml file with helps of Ansible Vault

Example: https://generalitalics.ru