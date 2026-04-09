# Ansible Docker Nginx Setup 🚀

This project automates infrastructure setup using Ansible.

## 🔧 What it does
- Installs Docker on target server
- Installs Python Docker library
- Starts Docker service
- Runs Nginx container
- Serves custom HTML page

## 🛠 Tech Stack
- Ansible
- Docker
- AWS EC2
- Linux

## 📦 How to run
```bash
ansible-playbook -i inventory.ini docker_setup.yml
