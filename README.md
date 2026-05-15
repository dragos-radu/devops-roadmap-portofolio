# 🚀 DevOps Portfolio – Dragos

Building production-like DevOps projects focused on automation, scalability, and real-world workflows.

---

## 🧰 Tech Stack
- CI/CD: Jenkins, GitHub Actions
- Containers: Docker, Kubernetes
- Cloud: AWS (EC2, S3, IAM)
- IaC: Terraform, Ansible
- Monitoring: Prometheus, Grafana
- Scripting: Python, Bash
- Other: Linux, REST APIs

---

## 📂 Projects

### 🔹 Project 01 – Nginx Static Site
Deploy a static website using Nginx on a Linux environment.

- **Jira:** DEVOPS-1 (Epic), DEVOPS-2 (Task)
- **Tech:** AWS EC2, Ubuntu, Nginx
- **Status:** ✅ Completed
- 👉 [Repository](https://github.com/dragos-radu/devops-roadmap-portfolio/project-01-nginx-static-site)

---

### 🔹 Project 02 – Nginx Virtual Hosts with HTTPS
Deploy multiple static websites on the same EC2 instance using Nginx virtual hosts and Let's Encrypt SSL certificates.

- **Jira:** DEVOPS-3 (Epic), DEVOPS-4 to DEVOPS-7 (Tasks)
- **Tech:** AWS EC2, Ubuntu, Nginx, Route 53, Let's Encrypt
- **Domains:** app1.devopsroad.xyz, app2.devopsroad.xyz
- **Status:** ✅ Completed
- 👉 [Repository](https://github.com/dragos-radu/devops-roadmap-portfolio/project-02-nginx-virtual-hosts)

---

### 🔹 Project 03 – Nginx Load Balancer
Configure a Layer 7 load balancer using Nginx to distribute traffic across multiple backend web servers.

- **Jira:** DEVOPS-8 (Epic), DEVOPS-9 to DEVOPS-12 (Tasks)
- **Tech:** AWS EC2, Ubuntu, Nginx, Linux
- **Architecture:** 1 Load Balancer + 2 Backend Servers
- **Status:** ✅ Completed
- 👉 [Repository](https://github.com/dragos-radu/devops-roadmap-portfolio/project-03-nginx-load-balancer)

---

### 🔹 Project 04 – WordPress LAMP Stack with Nginx Reverse Proxy
Deploy a dynamic WordPress application using Apache, MySQL, PHP, and Nginx as a reverse proxy. Includes automated daily backups with cron scheduling.

- **Jira:** DEVOPS-13
- **Tech:** AWS EC2, Ubuntu 22.04, Apache, MySQL, PHP, Nginx, Bash
- **Architecture:** Nginx (port 80) → Apache (port 8080) → WordPress + MySQL
- **Features:** Daily automated backups, 7-day retention, reverse proxy setup
- **Status:** ✅ Completed
- 👉 [Repository](https://github.com/dragos-radu/devops-roadmap-portfolio/project-04-wordpress-lamp-nginx)

---

### 🔹 Project 05 – Consul Service Discovery with Nginx
Deploy a dynamic load balancing setup using Consul for service discovery and Consul Template for automatic Nginx configuration updates.

- **Jira:** DEVOPS-20 (Epic), DEVOPS-21 to DEVOPS-25 (Tasks)
- **Tech:** AWS EC2, Ubuntu 22.04, Nginx, Consul, Consul Template
- **Architecture:** Consul Server + 2 Backend Services with automatic health checks
- **Status:** ✅ Completed
- 👉 [Repository](https://github.com/dragos-radu/devops-roadmap-portfolio/project-05-consul-nginx-service-discovery)

---

## 🧠 Approach

This portfolio simulates a real DevOps environment:
- Each project is tracked in Jira
- Git commits are linked to tasks
- Focus on real-world workflows, not just tutorials

---

## 📌 Goal

Transition from Junior → Mid DevOps by building hands-on, production-like projects.
