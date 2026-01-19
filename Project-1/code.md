# Ansible Project 1: Create User + SSH Key + Passwordless Sudo (EC2)

This project uses **Ansible** to automate Linux user management on an **AWS EC2 (Ubuntu)** server.

## ✅ Goal
On the target server, this automation will:

- Create a new user: `devops`
- Add the user to the `sudo` group
- Upload an SSH public key to allow key-based login
- Allow passwordless sudo for the new user
- Lock password login for the new user (SSH key only)

---

## 📌 Requirements
- Ansible installed on control machine (my PC/VM)
- SSH access to EC2 using AWS `.pem` key
- A personal SSH key pair for the new user (public key is copied to EC2)

---

## 🗂 Project Structure
```text
ansible-user-project/
├── ansible.cfg
├── inventory/
│   └── project1/
│       └── hosts
├── playbooks/
│   └── project1-users.yaml
└── roles/
    └── users/
        ├── defaults/
        │   └── main.yml
        └── tasks/
            └── main.yml

