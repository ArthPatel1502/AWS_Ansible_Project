# AWS Infrastructure Automation with Ansible

Automated the configuration and management of AWS EC2 instances using **Ansible**, enabling a single control node to manage multiple remote servers securely through **SSH key-based authentication** without installing any agents.

---

## 🚀 Project Overview

This project demonstrates how Ansible automates infrastructure management on AWS. An **Ansible Control Node** connects to one or more **EC2 instances** over SSH using **SSH key pairs**, executes playbooks, and applies configuration changes consistently across all managed servers.

---

## 🛠️ Tech Stack

- AWS EC2
- Ansible
- Ubuntu Linux
- YAML
- SSH
- SSH Key Authentication (`ssh-keygen`)
- AWS CLI

---

## 📂 Project Structure

```text
AWS_Ansible_Project/
│── ansible.cfg
│── inventory
│── playbook.yml
│── README.md
```

---

## ⚙️ Prerequisites

- AWS Account
- EC2 Instance(s)
- SSH Key Pair
- AWS CLI Configured
- Ansible Installed

---

## ▶️ Run the Project

Clone the repository:

```bash
git clone https://github.com/ArthPatel1502/AWS_Ansible_Project.git
cd AWS_Ansible_Project
```

Run the playbook:

```bash
ansible-playbook -i inventory playbook.yml
```

Verify connectivity:

```bash
ansible all -m ping
```

---

## 🔑 Key Concepts Learned

- Infrastructure as Code (IaC)
- Configuration Management
- Agentless Architecture
- SSH Key-based Authentication (`ssh-keygen`)
- Managing Multiple Servers from a Single Control Node
- Inventory Management
- Playbooks
- YAML Syntax
- Ansible Modules
- Tasks
- Idempotency
- AWS EC2 Provisioning & Management

---

## 📚 What I Learned

- Set up passwordless SSH authentication using `ssh-keygen`.
- Configure an Ansible Control Node to securely access remote EC2 instances.
- Manage multiple servers from a single machine using an inventory file.
- Write reusable Ansible playbooks to automate server configuration.
- Execute repeatable and idempotent automation tasks.
- Understand how Ansible simplifies infrastructure management at scale.

---

## 📈 Future Improvements

- Dynamic AWS Inventory
- Ansible Roles
- Jinja2 Templates
- Variables & Handlers
- Ansible Vault
- Terraform + Ansible Integration
- CI/CD Pipeline Integration

---

## 📚 Learning Resource

Built while learning from the **DevOps Zero to Hero** series by **Abhishek Veeramalla**, with the implementation recreated independently to strengthen my understanding of Ansible and AWS automation.

---

## 👨‍💻 Author

**Arth Patel**

GitHub: https://github.com/ArthPatel1502
