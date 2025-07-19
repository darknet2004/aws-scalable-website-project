# Highly Available & Scalable Web Application on AWS

This project demonstrates a fault-tolerant web application infrastructure on AWS. The goal is to host a website that is resilient to server failures and can automatically scale based on user traffic.

## Architecture Diagram
![Architecture Diagram](Flowchart.png)

## AWS Services Used
- **EC2:** Provides virtual servers for hosting the web application.
- **Application Load Balancer (ELB):** Distributes traffic across multiple EC2 instances.
- **Auto Scaling Group (ASG):** Automatically adds or removes servers based on load and replaces failed instances.
- **S3:** Stores and serves static assets like images and CSS.
- **IAM:** Manages secure access to AWS services using roles.
- **VPC & Security Groups:** Provides a secure, isolated network and firewall rules.

## Deployment Steps
This project was deployed manually through the AWS Management Console. The key steps involved:
1. Setting up S3 for static hosting and IAM for permissions.
2. Configuring an EC2 instance with Nginx and creating a "Golden AMI".
3. Deploying an Application Load Balancer and an Auto Scaling Group using the AMI.
4. Configuring Security Groups and Network ACLs to secure the application.

## How to Access
The live website can be accessed via the Load Balancer's DNS name. [Currently closed]
