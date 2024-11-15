# Installation Guide for Ansible on Debian Base

This guide covers the installation of Ansible on a Debian-based system. Follow the steps below to install Ansible.

## Prerequisites

Make sure you have root or `sudo` privileges before starting the installation process.

## Step 1: Install Dependencies and Configure Ansible Repository

Install the required dependencies by running the following command:

```bash
sudo apt install -y software-properties-common
```

```bash
sudo add-apt-repository --yes --update ppa:ansible/ansible
```
```bash
sudo apt update
```
```bash
sudo apt install -y ansible
```

# Ansible Playbook for Server Hardening and Docker Installation

This Ansible playbook is designed to:
1. Apply essential security hardening measures to the server.
2. Install Docker and Docker Compose to prepare the server for container-based applications.

## Requirements

- **Ansible**: Ensure Ansible is installed on the control machine.
- **Inventory**: Define target servers in an Ansible inventory file.

## Setup

1. Clone this repository:

   ```bash
   git clone https://github.com/echoamir/Ansible.git
