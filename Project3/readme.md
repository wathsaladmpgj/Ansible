# 🚀 Ansible Project 3 – Configure & Manage Services (Nginx)

## 📌 Project Summary
This project demonstrates **real-world Linux service management using Ansible**.
The automation ensures that the **Nginx web server** is installed, configured, enabled at boot, running,
and continuously verified across Linux servers.

This project follows **industry best practices** used by DevOps and SRE teams:
- Role-based Ansible structure
- Idempotent execution
- OS-aware tasks
- Safe service restarts using handlers
- Built-in service health verification

---

## 🧠 Why This Project Exists
In real production environments:
- Manually managing services causes configuration drift
- Restarting services unnecessarily causes downtime
- Teams need **repeatable, auditable automation**

This project solves those problems using **Ansible automation**.

---

## 🎯 Project Objectives
✔ Install Nginx on Linux servers  
✔ Enable Nginx at system startup  
✔ Ensure Nginx is always running  
✔ Deploy a custom HTML health page  
✔ Restart Nginx **only when required**  
✔ Verify service health using HTTP checks  

---

## 🏗️ Architecture Overview


