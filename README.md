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
# 📄 AWS Scalable & Fault-Tolerant Web Application

---

## 📌 1. Introduction

This project demonstrates the design and implementation of a scalable and fault-tolerant web application on AWS. The architecture ensures high availability, reliability, and performance by using services like CloudFront, S3, Application Load Balancer (ALB), and EC2 Auto Scaling.

---

## 🎯 2. Objectives

* To build a highly available web application
* To implement fault-tolerant architecture
* To achieve scalability using Auto Scaling
* To improve performance using CDN (CloudFront)

---

## 🏗️ 3. Architecture Diagram

<img width="660" height="746" alt="image" src="https://github.com/user-attachments/assets/85343390-3372-45cd-a649-8e91433b37a5" />


## 🛠️ 4. Services Used

* Amazon CloudFront – Content Delivery Network
* Amazon S3 – Static website hosting
* Application Load Balancer (ALB) – Load distribution
* Amazon EC2 – Compute instances
* Auto Scaling Group – Automatic scaling
* Amazon CloudWatch – Monitoring and logging

---

## 🔄 5. Working / Flow of Project

1. User sends request to the application
2. Request first goes to CloudFront (CDN)
3. Static content is served from S3 bucket
4. Dynamic requests are forwarded to ALB
5. ALB distributes traffic to EC2 instances
6. Auto Scaling Group adjusts instances based on traffic
7. CloudWatch monitors logs and performance

---

## ⚙️ 6. Implementation Steps

1. Created an S3 bucket for static content hosting
2. Configured CloudFront distribution
3. Launched EC2 instances
4. Created Auto Scaling Group
5. Configured Application Load Balancer
6. Attached target group to ALB
7. Enabled monitoring using CloudWatch

---

## 📊 7. Output / Results

* Application remains available even if one instance fails
* Traffic is distributed efficiently
* Automatic scaling based on user demand
* Improved performance using CDN

---

## ⚠️ 8. Challenges Faced

* Configuring Load Balancer correctly
* Managing security groups and permissions
* Auto Scaling configuration tuning

---

## ✅ 9. Conclusion

This project successfully demonstrates a production-ready AWS architecture that ensures high availability, scalability, and fault tolerance. It is suitable for real-world web applications handling dynamic traffic.

---

## 🔮 10. Future Enhancements

* Implement CI/CD pipeline using GitHub Actions
* Use Infrastructure as Code tools like Terraform
* Add alerting system using CloudWatch alarms

---

## 👨‍💻 11. Author

Shubham Mane

[Click here to view full project](project.pdf)
