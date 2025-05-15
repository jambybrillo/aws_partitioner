# Lab #7 – Launching an Amazon RDS Database Instance

## 📘 Overview

This repository documents **Lab #7** of **AWS Cloud Quest: Cloud Practitioner**, where we launch an **Amazon RDS** (Relational Database Service) database instance. This lab helps us understand how to provision and manage an RDS database using the AWS Management Console.

---

## 🧠 Objectives

- Launch an Amazon RDS database instance.
- Configure database settings such as engine type, instance class, storage, and security groups.
- Connect to the database using endpoint details.

---

## 🛠️ Steps Performed

### 1. Navigate to Amazon RDS Console
- Open the **RDS service** from AWS Management Console.

### 2. Create Database
- Choose **Create database**.
- Select **Standard Create**.
- Choose the **engine**: `MySQL` (or `PostgreSQL`, etc.).
- Set version, instance type (`db.t3.micro` for free-tier), and allocate storage.

### 3. Set DB Details
- DB Instance Identifier: `my-lab7-db`
- Master username: `admin`
- Master password: `********`

### 4. Configure Connectivity
- VPC: Default or custom VPC
- Enable public access: Yes (for test access)
- VPC security group: New or existing

### 5. Additional Configuration
- Database name: `lab7db`
- Backup: Enable/Disable (as needed)
- Monitoring and auto-scaling: Default settings

### 6. Launch Instance
- Click **Create Database**.
- Wait for the status to become `Available`.

### 7. Connect to RDS Instance
- Use **endpoint** from RDS dashboard.
- Connect using any MySQL client like MySQL Workbench or CLI.

---

## 📸 Screenshots (Optional)

You can include screenshots inside a `screenshots/` folder:
- `rds-dashboard.png`: Showing the RDS instance running

---

## 📂 Resources Used

- AWS RDS
- MySQL (or selected engine)
- AWS Management Console

---

## 🔐 Notes

- Ensure you secure your credentials and endpoint information.
- Terminate unused RDS instances to avoid charges.

---

## 📅 Date Completed

**May 15, 2025**

