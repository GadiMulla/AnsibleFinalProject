# AnsibleFinalProject

This Ansible role performs the following tasks:

- Installs required packages (`htop`, `tree`, etc.).
- Updates the system packages.
- Installs Apache/httpd based on the OS family.
- Copies files to target hosts.
- Prints the number of RedHat and Debian hosts.

## Installation

To install this role, use `ansible-galaxy`:

```bash
ansible-galaxy install username.my_role

## Requirements

This role requires Ansible to be installed on the control node. Ensure that your target hosts are reachable and properly configured for Ansible connectivity.

# Usage
To use this role in your playbook, include it in the roles section:

- hosts: all
  roles:
    - username.my_role
