# 🚀 Jenkins-Static-Website-CICD

> **Author:** Sudarshan Bhosale  
> **Role:** Cloud & DevOps Engineer (Fresher – Hands-on Project)  
> **Environment:** AWS EC2 (Ubuntu), Jenkins, GitHub, Nginx, Linux  

---

## 📌 Project Overview

In this project, I implemented a **complete Jenkins CI/CD pipeline** to deploy a **static website** on an AWS Web Server using **Nginx**.  
The pipeline automates the workflow from **code commit → build → artifact transfer → deployment → hosting on port 80**.

This project simulates **real-world DevOps practices**, including automation, security handling, troubleshooting Jenkins pipeline errors, SSH permissions, and multi-server deployment.

---

## 🧠 My Real Hands-On Responsibilities

I personally performed:

- Setup of **Jenkins CI/CD Server (EC2 Ubuntu)**
- Setup of **Web Hosting Server (EC2 Ubuntu)**
- Integrated **GitHub with Jenkins (SCM)**
- Created **Jenkins Freestyle Job**
- Developed **Linux Shell Automation Scripts**
- Implemented **Secure SCP & SSH Connectivity**
- Installed & Configured **Nginx Web Server**
- Opened HTTP Port 80 for users
- Debugged real Jenkins issues like:  
  ✔ zip not installed  
  ✔ SSH permission denied  
  ✔ PEM key access errors

This project helped me understand **how Jenkins executes CI/CD pipelines and production deployment workflows**.

---

## 🧩 Technologies & Tools Used

| Technology | Purpose |
|------------|--------|
| Jenkins    | CI/CD Automation |
| GitHub     | Source Code Repository |
| AWS EC2    | Cloud Infrastructure |
| Ubuntu     | Server OS |
| Nginx      | Web Hosting |
| SSH / SCP  | Secure Communication |
| HTML       | Static Website |

---

## 🏗️ Project Architecture
---

## 🧩 Technologies & Tools Used :-

| Technology | Purpose |
|----------|--------|
| Jenkins | CI/CD Automation |
| GitHub | Source Code Management |
| Nginx | Web Server |
| Ubuntu | Server OS |
| SSH / SCP | Secure Communication |
| HTML | Static Website |
| AWS EC2 | Cloud Infrastructure |

---
## 🏗️ Architecture Diagram :-
```
+-------------+        +---------------------+        +----------------------+
| Developer   | -----> | GitHub Repository   | -----> | Jenkins Server       |
| (Local PC)  |  Push  | (Source Code SCM)   |  Pull  | (CI/CD Automation)   |
+-------------+        +---------------------+        +----------+-----------+
                                                                      |
                                                                      | SCP / SSH
                                                                      v
                                                           +----------------------+
                                                           | Web Server           |
                                                           | (Nginx)              |
                                                           | Static Website Host  |
                                                           | Port 80 (HTTP)       |
                                                           +----------+-----------+
                                                                      |
                                                                      v
                                                           +----------------------+
                                                           | Users                |
                                                           | Access via Browser   |
                                                           +----------------------+

```
## 🏗️ High-Level Architecture Diagram









🖥️ Infrastructure

1️⃣ Jenkins Server

Ubuntu EC2

Jenkins Installed

Pulls Code

Packages Files

Transfers & Deploys

2️⃣ Web Server

Ubuntu EC2

Nginx Installed

Port 80 Enabled






