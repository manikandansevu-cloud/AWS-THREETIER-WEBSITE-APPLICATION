# ☁️ AWS Three-Tier Web Application Deployment

![AWS](https://img.shields.io/badge/AWS-Cloud-orange?style=for-the-badge&logo=amazonaws)
![EC2](https://img.shields.io/badge/EC2-Running-blue?style=for-the-badge)
![RDS](https://img.shields.io/badge/RDS-MySQL-green?style=for-the-badge)
![ALB](https://img.shields.io/badge/Application_Load_Balancer-Active-red?style=for-the-badge)
![Auto Scaling](https://img.shields.io/badge/Auto_Scaling-Enabled-success?style=for-the-badge)

---

# 📌 Project Overview

This project demonstrates the deployment of a **Three-Tier Web Application** on **Amazon Web Services (AWS)** using highly available and scalable cloud infrastructure.

The architecture consists of:

- 🌐 Presentation Tier (EC2)
- ⚙️ Application Tier
- 🗄 Database Tier (Amazon RDS)

The application uses **Application Load Balancer**, **Auto Scaling**, **Amazon RDS**, and **Amazon VPC** to provide a secure and highly available environment.

---

# 🏗 AWS Architecture

```
                     Internet
                         │
                         ▼
            Application Load Balancer
                         │
          ┌──────────────┴──────────────┐
          │                             │
      EC2 Instance                  EC2 Instance
    (Auto Scaling)                (Auto Scaling)
          │                             │
          └──────────────┬──────────────┘
                         │
                     Amazon RDS
                      MySQL DB
```

---

# 🚀 AWS Services Used

| AWS Service | Purpose |
|-------------|---------|
| Amazon EC2 | Web Server |
| Amazon RDS | Database |
| Application Load Balancer | Load Balancing |
| Auto Scaling Group | Automatic Scaling |
| Amazon VPC | Network |
| Security Groups | Firewall |
| IAM | Identity Management |
| Internet Gateway | Internet Access |

---

# ✨ Features

- High Availability
- Auto Scaling
- Application Load Balancer
- Amazon RDS Database
- Secure VPC
- Public & Private Subnets
- Security Groups
- Fault Tolerance
- Scalable Architecture

---

# 🔄 Project Workflow

1. User accesses the application.
2. Request reaches the Application Load Balancer.
3. Load Balancer distributes traffic to EC2 instances.
4. Auto Scaling manages EC2 instances automatically.
5. EC2 connects securely to Amazon RDS.
6. Database returns the requested data.

---

# 📸 Project Screenshots



## 🌐 Website Home Page

![Website](./screenshots/WEBSITE%20IMAGE.png)

---

## 💻 Amazon EC2 Instance

![EC2](screenshots/EC2.png)

---



## ⚖️ Application Load Balancer

![Load Balancer](./screenshots/LOAD%20BALANCER.png)

---



## 📈 Auto Scaling Group

![Auto Scaling Group](./screenshots/AUTO%20SCALING.png)

---

## 🗄 Amazon RDS Database

![RDS](screenshots/RDS.png)

---

## 🌍 Amazon VPC

![VPC](screenshots/VPC.png)

---

# 🎯 Project Outcome

Successfully deployed a **Three-Tier Web Application** on AWS using:

- Amazon EC2
- Application Load Balancer
- Auto Scaling Group
- Amazon RDS
- Amazon VPC
- Security Groups
- IAM

### Benefits

- ✔ High Availability
- ✔ Scalability
- ✔ Secure Infrastructure
- ✔ Load Balancing
- ✔ Automatic Scaling
- ✔ Database Integration

---

# 📂 Repository Structure

```
AWS-THREETIER-WEBSITE-APPLICATION/
│
├── README.md
│
└── screenshots/
    ├── WEBSITEIMAGE.png
    ├── EC2.png
    ├── LOADBALANCER.png
    ├── AUTOSCALING.png
    ├── RDS.png
    └── VPC.png
```

---

# 👨‍💻 Author

**Manikandan S**

AWS Cloud Practitioner

GitHub: https://github.com/manikandansevu-cloud

LinkedIn: https://www.linkedin.com/in/YOUR-LINKEDIN/

---

## ⭐ If you found this project useful, please give it a Star!
