# 🚀 Enterprise Web Application Deployment on AWS  
### CI/CD • Auto Scaling • High Availability • Monitoring

---

## 📌 Project Concept

This project demonstrates how to design and deploy an **enterprise-grade web application infrastructure on AWS** using industry best practices.  
The goal is to build a **secure, scalable, highly available, and monitored system** similar to what is used in real-world production environments.

This project is built **hands-on**, fully documented, and suitable for **cloud/DevOps portfolios and interviews**.

---

## ❗ Problem Statement

Traditional web applications often face challenges such as:
- ❌ Single server failure
- ❌ No traffic distribution
- ❌ Manual scaling
- ❌ Poor monitoring and alerting
- ❌ Weak security controls
- ❌ No clear documentation

These issues lead to **downtime, poor performance, and security risks**.

---

## ✅ Solution Overview

To solve these problems, this project implements:

- ✔️ A **custom VPC** for network isolation
- ✔️ **Multiple EC2 instances** for redundancy
- ✔️ **Application Load Balancer (ALB)** for traffic distribution
- ✔️ **Amazon RDS (MySQL)** for managed database services
- ✔️ **IAM roles & users** for secure access
- ✔️ **CloudWatch monitoring & alarms** for observability
- ✔️ Clear **documentation and screenshots** for understanding

---

## 🧱 Architecture Overview

**User → ALB → EC2 Web Servers → RDS Database**

- Traffic enters through the **Application Load Balancer**
- Requests are distributed to **multiple EC2 instances**
- Application connects securely to **Amazon RDS**
- Monitoring is handled by **CloudWatch**
- Access is controlled using **IAM**

---

## 🧰 Tools & AWS Services Used

### ☁️ AWS Services
- Amazon VPC
- Amazon EC2
- Application Load Balancer (ALB)
- Amazon RDS (MySQL)
- IAM (Users & Roles)
- Amazon CloudWatch

### 🛠️ Tools
- Git & GitHub
- AWS Management Console
- SSH (Linux)
- Bash scripting

---

## 🧪 Implementation Steps

### 1️⃣ VPC & Networking
- Created a custom VPC
- Configured public subnets
- Attached Internet Gateway
- Updated route tables

### 2️⃣ EC2 Web Servers
- Launched two EC2 instances
- Installed web server
- Enabled SSH access
- Verified public IP connectivity

### 3️⃣ Security Groups
- Allowed HTTP (80) and SSH (22)
- Restricted database access
- Applied least-privilege rules

### 4️⃣ Application Load Balancer
- Created ALB
- Configured target groups
- Registered EC2 instances
- Verified traffic distribution

### 5️⃣ Database (RDS)
- Created MySQL RDS instance
- Enabled Multi-AZ
- Connected RDS from EC2
- Verified database access

### 6️⃣ IAM Configuration
- Created IAM users
- Created IAM roles
- Attached roles to EC2
- Applied security best practices

### 7️⃣ Monitoring & Alerts
- Enabled CloudWatch metrics
- Monitored CPU utilization
- Created CloudWatch alarms

---

## 📸 Screenshots

### 🌐 VPC & Networking
![VPC Dashboard](screenshots/01_VPC_Dashboard.png)
![Public Subnets](screenshots/02_Public_Subnets.png)
![EC2 Public IPs](screenshots/03_EC2_PublicIPs.png)

### 🖥️ EC2 / Web Servers
![SSH Web Server 1](screenshots/04_SSH_WS1.png)
![SSH Web Server 2](screenshots/05_SSH_WS2.png)

### 🔐 Security Groups
![Security Groups](screenshots/06_SG_WS.png)

### ⚖️ Load Balancer
![ALB Configuration](screenshots/07_ALB_Config.png)
![ALB Browser Test](screenshots/08_ALB_Browser_Test.png)

### 🗄️ Database
![RDS Dashboard](screenshots/09_RDS_Dashboard.png)
![EC2 to RDS Connection](screenshots/10_EC2_RDS_Connection.png)

### 👤 IAM
![IAM Role](screenshots/11_IAM_Role.png)
![IAM User](screenshots/12_IAM_User.png)

### 📊 Monitoring
![CloudWatch CPU Metric](screenshots/13_EC2_CPU_Metric.png)

---

## 🎯 Project Outcome

- ✅ High availability achieved using ALB + multiple EC2 instances
- ✅ Improved security with IAM and Security Groups
- ✅ Scalable architecture ready for production use
- ✅ Full monitoring and alerting enabled
- ✅ Clear documentation for reuse and learning

---

## 🧠 Skills Gained

- AWS Cloud Architecture
- VPC & Networking
- EC2, ALB, RDS configuration
- IAM security best practices
- Monitoring & observability
- Enterprise-level documentation
- GitHub portfolio structuring

---

## 📂 Repository Structure

