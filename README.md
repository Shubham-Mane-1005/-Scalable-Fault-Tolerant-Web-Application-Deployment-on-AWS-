# 🚀 AWS Scalable & Fault-Tolerant Web Application

## 📌 Project Overview

This project demonstrates a highly available, scalable, and fault-tolerant web application architecture on AWS. It ensures continuous availability and performance even during failures by using load balancing, auto scaling, and CDN.

---

## 🛠️ Tech Stack

* AWS CloudFront (CDN)
* AWS S3 (Static Website Hosting)
* AWS Application Load Balancer (ALB)
* AWS EC2 (Auto Scaling Group)
* AWS CloudWatch & CloudTrail

---

## 🏗️ Architecture

* Users access the application via CloudFront CDN
* Static content is served from S3
* Dynamic requests are routed through ALB
* EC2 instances in Auto Scaling Group handle backend processing
* CloudWatch monitors performance and logs

---

## ⚙️ Features

* High Availability
* Fault Tolerance
* Auto Scaling
* Load Balancing
* CDN Integration for faster delivery
* Monitoring and Logging

---

## 🚀 Deployment Steps

1. Create S3 bucket for static hosting
2. Configure CloudFront distribution
3. Launch EC2 instances with Auto Scaling Group
4. Configure Application Load Balancer
5. Attach target group to ALB
6. Enable monitoring using CloudWatch

---

## 📊 Output

* Highly available web application
* Automatic scaling based on traffic
* Improved performance using CDN
* Continuous monitoring and logging

---

## 📂 Project Files

* `project.pdf` – Detailed documentation
* `architecture.png` – Architecture diagram

---

## 🎯 Use Case

* Production-ready web hosting
* High-traffic applications
* Fault-tolerant systems

---

## 👨‍💻 Author

Shubham Mane

---

## 🔗 Project Documentation

[Click here to view full project](project.pdf)
