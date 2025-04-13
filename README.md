# 🛠️ Simple DevOps Stack

This project demonstrates a simple automated web stack deployment using **Ansible** and **Docker Compose**.  
It deploys **Nginx + PHP + MySQL** stack on a Linux host via Ansible playbook and includes GitHub Actions CI.

## 📦 Stack Components
- Nginx (web server)
- PHP (running via FPM)
- MySQL 5.7
- Docker & Docker Compose
- Ansible for provisioning
- GitHub Actions (syntax validation for playbooks)

## 🚀 How It Works
- Ansible installs Docker + Docker Compose on the target host
- Docker Compose spins up Nginx, PHP and MySQL
- Basic Nginx config routes PHP requests via FastCGI

## 📁 Folder Structure
simple-devops-stack/ 
├── ansible/ # Ansible playbook and inventory 
├── docker/ # Docker Compose + container configs 
├── .github/workflows/ # CI pipeline with Ansible lint 
└── README.md

## ✅ CI Pipeline
This project includes GitHub Actions to perform:
- Ansible playbook syntax checks

## 🧠 Why This Project?
This project is designed to showcase core DevOps skills:
- Infrastructure as Code (IaC)
- Automation with Ansible
- Container orchestration (basic level)
- CI integration

## 👨�💻 Author
**Roman Golubiev**  
[LinkedIn](https://www.linkedin.com/in/golubiev)