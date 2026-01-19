# Ansible Project 2 — Install & Manage Packages on AWS EC2 (Ubuntu)

This project automates **Linux package installation and removal** on **AWS EC2 (Ubuntu)** using **Ansible**.  
It uses an **inventory + playbook + role** structure so it’s clean, reusable, and similar to real company projects.

---

## ✅ What this project does

On one or more EC2 servers, Ansible will:

1. Connect using **SSH key (.pem/private key)**
2. Update the package cache (`apt update`)
3. Install a standard set of tools (example: `git`, `curl`, `wget`, `htop`)
4. Remove unwanted packages (example: `telnet`)
5. Run safely multiple times (**idempotent**)

---

## 🧠 Why this project is useful

- You can manage **many servers at once**
- Avoid manual SSH + `apt install` on each server
- Keep all servers consistent (same tools everywhere)
- Easy to change packages later and re-run

---

## 🏗 Architecture


