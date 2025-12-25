# Terraform Project

This project demonstrates creating infrastructure on AWS using **Terraform**.

---

## 📌 Overview
The project covers provisioning the following AWS resources:  
- **EKS Cluster**  
- **2 Worker Nodes** (t3.medium)  
- **Elastic Load Balancer (ELB)**  
- **VPC & Subnets**  
- **Security Groups**  
- **Ingress Controller** for Kubernetes  

---

## 🛠 Tools & Technologies
- Terraform  
- AWS (EKS, ELB, VPC, Security Groups)  
- Kubernetes (Ingress Controller)  

---

## ⚙️ Deployment Steps
1. Write Terraform scripts for all required resources  
2. Apply Terraform scripts to create infrastructure  
3. Install Kubernetes resources (pods, services, ingress controller) on EKS  
4. Use ELB to route external traffic to the cluster  

---

## 📄 Notes
- Worker nodes use instance type **t3.medium**  
- Ingress controller manages external access to Kubernetes services  
- Can be extended with CI/CD pipelines for automated deployments  
