# 🚀 AWS EC2 Web Deployment using Nginx

![AWS](https://img.shields.io/badge/AWS-EC2-orange)
![Linux](https://img.shields.io/badge/Linux-Ubuntu-blue)
![Web Server](https://img.shields.io/badge/WebServer-Nginx-green)
![Project](https://img.shields.io/badge/Project-Completed-brightgreen)

---

## 📌 Project Overview

This project demonstrates the deployment of a web application on a cloud server using **Amazon EC2** and **Nginx**.

It covers launching a virtual machine, configuring network access, connecting via SSH, and hosting a website using a Linux-based web server.

---

## 🏗️ Architecture

User → EC2 Instance → Nginx Web Server → Website

---

## ⚙️ Implementation Steps

### 🔹 Step 1: Launch EC2 Instance
- Created an EC2 instance using Ubuntu
- Configured key pair and instance settings

![EC2 Instance](images/1-ec2-instance.png)

---

### 🔹 Step 2: Configure Security Group
- Allowed inbound traffic:
  - SSH (Port 22)
  - HTTP (Port 80)

![Security Group](images/2-security-group.png)

---

### 🔹 Step 3: Connect via SSH
- Connected to EC2 instance using SSH
- Accessed Linux terminal remotely

![SSH Connection](images/3-ssh-connection.png)

---

### 🔹 Step 4: Install and Run Nginx
- Installed Nginx web server
- Started and enabled the service

![Nginx Running](images/4-nginx-running.png)

---

### 🔹 Step 5: Deploy Website
- Created and hosted a custom HTML webpage
- Accessed via EC2 public IP

![Final Output](images/5-final-output.png)

---

## 🌐 Final Output

✅ Successfully deployed a website using AWS EC2 and Nginx  
✅ Application accessible via public IP  
✅ Fully functional cloud-based web hosting  

---

## 🛠️ Tech Stack

- ☁️ AWS EC2  
- 🐧 Ubuntu Linux  
- 🌐 Nginx  
- 💻 HTML, CSS  

---

## 📚 Learning Outcomes

- Understanding cloud-based virtual servers (EC2)  
- Configuring security groups and networking  
- Remote server access using SSH  
- Installing and managing Nginx web server  
- Deploying and hosting a web application  

---

## 🚀 Future Enhancements

- Add domain using Route 53  
- Enable HTTPS using SSL  
- Use CloudFront for CDN  
- Automate deployment  

---

## 👨‍💻 Author

Swaraj Sutradhar
