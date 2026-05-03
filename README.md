# gcp-load-balanced-web-app

## Project Overview
This project demonstrates the deployment of a scalable and highly available web application on Google Cloud Platform (GCP) using Infrastructure as Code principles and cloud services.

The application is deployed using:
- Compute Engine (VM instances)
- Managed Instance Group (MIG)
- HTTP Load Balancer
- Custom VPC and Firewall configuration
- Startup scripts for automation

---

## Architecture
The system follows a basic load-balanced architecture:

User → HTTP Load Balancer → Managed Instance Group → Multiple VM Instances (Apache Web Servers)

---

##  Key Features
-  Automated VM provisioning using Instance Templates
-  Auto-scaling using Managed Instance Groups
-  Load balancing traffic across multiple instances
-  Health checks for high availability
-  Custom VPC and firewall configuration
-  Startup script to auto-deploy Apache web server

---

##  Technologies Used
- Google Cloud Platform (GCP)
- Compute Engine
- Load Balancer (HTTP)
- VPC Networking
- Linux (Ubuntu)
- Apache Web Server
- gcloud CLI

---

## 📸 Screenshots
-Shows instance group health check passing successfully.
-Displays different VM hostnames when refreshing the browser, proving load balancing works.

---

##  How It Works
1. A custom VPC and subnet are created
2. Firewall rules allow HTTP and health check traffic
3. An instance template defines VM configuration
4. A managed instance group launches multiple VMs
5. A load balancer distributes traffic across instances
6. Health checks ensure only healthy instances receive traffic
7. Startup script automatically installs and configures Apache

---

##  Outcome
- Successfully deployed a scalable web application
- Achieved high availability using load balancing
- Demonstrated Infrastructure as Code using gcloud CLI
- Implemented real-world cloud architecture on GCP



## 👨‍💻 Author
Your Name  
Cloud Computing Project – GCP Load Balancing Demo
