# Highly Available & Scalable Web Application on AWS

This project demonstrates a fault-tolerant web application infrastructure deployed on AWS. The goal is to host a website that is resilient to server failures and can automatically scale based on user traffic.

---

## 🛠️ Tech Stack & AWS Services

* **Cloud Provider:** AWS
* **Core Services:**
    * **EC2:** For virtual web servers.
    * **Application Load Balancer (ELB):** To distribute traffic.
    * **Auto Scaling Group (ASG):** For scalability and self-healing.
    * **S3:** For storing static assets (CSS, images).
    * **IAM:** For secure role-based permissions.
    * **VPC & Security Groups:** For network isolation and firewalling.
* **Web Server:** Nginx
* **Frontend:** HTML5 & CSS3

---
## ✨ Key Features

* **High Availability:** Deployed across multiple Availability Zones to prevent a single point of failure.
* **Scalability:** Automatically scales out during high traffic and scales in to save costs during quiet periods.
* **Fault Tolerance:** The Auto Scaling Group automatically replaces any instances that fail health checks.
* **Decoupled Architecture:** Static assets are served from S3 to reduce the load on the compute instances.

---
## 📂 Repository Structure

* `/Website Code`: Contains the `index.html` and `style.css` files for the frontend.
* `/Project Architecture`: Contains the architecture diagram, video demo, and other design assets.
