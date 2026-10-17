# Secure Multi-AZ Amazon RDS Database Architecture

## 📋 Overview
This project showcases enterprise-grade cloud security by deploying an Amazon RDS PostgreSQL database entirely within a private subnet. By restricting public accessibility, the database is protected from direct external threats while remaining accessible to internal backend services.

## 🏗️ Architecture & Security Design
* **Engine:** PostgreSQL[cite: 6]
* **Subnet Group:** Configured across multiple Availability Zones (`us-east-1a` and `us-east-1b`) to ensure high availability and redundancy.
* **Network Isolation:** Public access set to **No**, ensuring the database resides strictly within private subnet layers.
* **Security Groups:** Enforces strict inbound/outbound firewall rules allowing only authorized internal compute layers to communicate with the database port.

## 🛠️ Key Skills Demonstrated
* Configuring RDS DB Subnet Groups for multi-AZ resiliency.
* Implementing security best practices (Private Subnet isolation).
* Managing relational database lifecycle states in AWS.

## 📸 Proof of Execution
# Secure Multi-AZ Amazon RDS Database Architecture

## 📋 Overview
This project showcases enterprise-grade cloud security by deploying an Amazon RDS PostgreSQL database entirely within a private subnet. By restricting public accessibility, the database is protected from direct external threats while remaining accessible to internal backend services.

## 🏗️ Architecture & Security Design
* **Engine:** PostgreSQL[cite: 6]
* **Subnet Group:** Configured across multiple Availability Zones (`us-east-1a` and `us-east-1b`) to ensure high availability and redundancy.
* **Network Isolation:** Public access set to **No**, ensuring the database resides strictly within private subnet layers.
* **Security Groups:** Enforces strict inbound/outbound firewall rules allowing only authorized internal compute layers to communicate with the database port.

## 🛠️ Key Skills Demonstrated
* Configuring RDS DB Subnet Groups for multi-AZ resiliency.
* Implementing security best practices (Private Subnet isolation).
* Managing relational database lifecycle states in AWS.

## 📸 Proof of Execution
<img width="1920" height="1080" alt="Screenshot (3540)" src="https://github.com/user-attachments/assets/69e3bb27-da3f-4765-8695-e58953447d4c" />
<img width="1920" height="1080" alt="Screenshot (3542)" src="https://github.com/user-attachments/assets/1befa6b2-f710-4948-8c7e-aba6d3aeadcf" />
<img width="1920" height="1080" alt="Screenshot (3541)" src="https://github.com/user-attachments/assets/c9d5389c-e032-4a63-9039-a5b2a4f0be8a" />
<img width="1920" height="1080" alt="Screenshot (3543)" src="https://github.com/user-attachments/assets/5fed3b79-26ef-41c4-972c-81a96a06299b" />




