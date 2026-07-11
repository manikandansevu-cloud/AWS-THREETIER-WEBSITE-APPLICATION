# AWS Three-Tier Web Application Deployment

## Project Overview

This project demonstrates the deployment of a scalable, secure, and highly available **Three-Tier Web Application** on Amazon Web Services (AWS).

The application uses Auto Scaling to automatically manage EC2 instances, an Application Load Balancer (ALB) to distribute incoming traffic, and Amazon RDS as the backend database.

---

## AWS Services Used

- Amazon EC2
- Amazon RDS (PostgreSQL)
- Application Load Balancer (ALB)
- Auto Scaling Group
- Amazon VPC
- Internet Gateway
- Public & Private Subnets
- Route Tables
- Security Groups
- IAM

---

## Architecture

### Presentation Tier
- Hosts the web application on EC2 instances.
- Receives user traffic through the Application Load Balancer.
- Provides high availability using Auto Scaling.

### Application Tier
- Processes user requests.
- Connects securely with the database.
- Runs PHP/Apache application.

### Database Tier
- Stores application data in Amazon RDS.
- Accessible only from the application servers.
- Secured using Security Groups.

---

## Features

- High Availability
- Auto Scaling
- Application Load Balancer
- Secure VPC Architecture
- Database Integration with Amazon RDS
- Public and Private Subnets
- Fault Tolerance
- Scalable Infrastructure

---

## AWS Architecture

```
                    Internet
                        │
                        ▼
          Application Load Balancer
                        │
          ┌─────────────┴─────────────┐
          │                           │
      EC2 Instance               EC2 Instance
    (Auto Scaling)            (Auto Scaling)
          │                           │
          └─────────────┬─────────────┘
                        │
                   Amazon RDS
                  (PostgreSQL)
```

---

## Project Workflow

1. User accesses the application using the Load Balancer DNS.
2. Application Load Balancer distributes traffic.
3. Auto Scaling launches or terminates EC2 instances based on demand.
4. EC2 instances process application requests.
5. Application communicates with Amazon RDS.
6. Database returns the requested data.

---

# Project Screenshots

## 🌐 Website Home Page

<img src="./screenshots/WEBSITEIMAGE.png" width="100%">

---

## 💻 EC2 Instance

<img src="./screenshots/EC2.png" width="100%">

---

## ⚖️ Application Load Balancer

<img src="./screenshots/LOADBALANCER.png" width="100%">

---

## 📈 Auto Scaling Group

<img src="./screenshots/AUTOSCALING.png" width="100%">

---

## 🗄️ Amazon RDS

<img src="./screenshots/RDS.png" width="100%">

---

## 🌍 Amazon VPC

<img src="./screenshots/VPC.png" width="100%">

## Outcome

Successfully deployed a highly available and scalable **Three-Tier Web Application** on AWS using:

- Amazon EC2
- Application Load Balancer
- Auto Scaling Group
- Amazon RDS
- Amazon VPC
- Security Groups

This architecture ensures scalability, fault tolerance, load balancing, and secure communication between the application and database tiers.

---

## Author

**Manikandan S**

AWS Cloud Practitioner

GitHub: https://github.com/YOUR_USERNAME

LinkedIn: https://www.linkedin.com/in/YOUR_PROFILE/
