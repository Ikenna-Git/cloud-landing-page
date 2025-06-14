# Cloud Landing Page Deployment Project

This project demonstrates how to provision a Linux server, configure a web server, and deploy a simple, responsive landing page using HTML and CSS. It is part of my cloud engineering learning journey focused on understanding real-world deployment and infrastructure management.

## 🚀 Project Overview

The goal was to set up a live, accessible landing page hosted on an EC2 instance using open-source tools and manual configuration steps. It covers basic cloud setup, web server installation, content deployment, and firewall rules configuration.

---

## 🛠️ Tech Stack

- **Amazon EC2** – Ubuntu 22.04 server instance  
- **Nginx** – Web server used for hosting the landing page  
- **HTML/CSS** – Static website content  
- **SSH & SCP** – Secure access and file transfers  
- **UFW** – Firewall management on Ubuntu

---

## 📦 Steps Taken

### 1. **Provisioning the Server**

- Launched an EC2 instance on AWS using Ubuntu 22.04.
- Added an inbound rule to allow HTTP (port 80) and SSH (port 22) access.
- Downloaded and configured the `.pem` key for secure SSH access.

### 2. **Connecting to the Server**

```bash
ssh -i my-key.pem ubuntu@<your-ec2-public-ip>
.


