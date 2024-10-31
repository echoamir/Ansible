# Ansible Playbook for Server Hardening and Docker Installation

This Ansible playbook is designed to:
1. Apply essential security hardening measures to the server.
2. Install Docker and Docker Compose to prepare the server for container-based applications.

## Requirements

- **Ansible**: Ensure Ansible is installed on the control machine.
- **Inventory**: Define target servers in an Ansible inventory file.

## Setup

  1- git clone https://github.com/echoamir/Ansible.git
  2- cd Ansible/roles
  3- config your inventory file
  4- ansible-playbook playboook.yml
