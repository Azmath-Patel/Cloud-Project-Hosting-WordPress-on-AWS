# Cloud-Project-Hosting-WordPress-on-AWS
🚀 Project Overview

This project demonstrates how to deploy a WordPress site on AWS using EC2, RDS, and VPC. It simulates a real-world cloud deployment scenario, showcasing my ability to:

Set up cloud infrastructure on AWS

Manage web servers

Configure and deploy WordPress for professional use




| Component  | Technology     | Description                                                     |
| ---------- | -------------- | --------------------------------------------------------------- |
| Hosting    | ☁️ AWS EC2     | Virtual server to host WordPress                                |
| Database   | 🗄️ AWS RDS     | Managed MySQL database for storing WordPress data               |
| Web Server | 🌐 Apache      | Handles HTTP requests and serves the WordPress site             |
| Backend    | ⚙️ PHP & MySQL | Power the dynamic content of WordPress                          |
| CMS        | 🎨 WordPress   | Content management system for building and managing the website |



📌 Architecture Overview
[User Browser] <---> [AWS EC2 (Apache + PHP + WordPress)] <---> [AWS RDS (MySQL Database)]
                   |
                   +--> [VPC for networking & security]
![Architecture](architecture.png)


Key Points:

EC2 instance hosts WordPress application

RDS instance stores WordPress database

VPC provides secure networking

📸 Screenshots

WordPress Dashboard
![Architecture](architecture.png)

Homepage of the deployed site
![Architecture](architecture.png)

EC2 instance running WordPress
![Architecture](architecture.png)

(Add screenshots in your repo or link them here using ![Screenshot](path-to-image))

🔗 GitHub Repository

View the Project Repository




📖 How to Deploy (Optional)

Launch an EC2 instance with Amazon Linux or Ubuntu.

Install Apache, PHP, and other dependencies:

sudo yum update -y
sudo yum install httpd php php-mysqlnd -y
sudo systemctl start httpd
sudo systemctl enable httpd


Launch an RDS MySQL instance and note the endpoint.

Configure WordPress to connect to the RDS database.

Update security groups to allow HTTP/HTTPS access.

Test the website by visiting your EC2 public IP or domain.


📬 Contact Me

If you have questions or want to discuss this project, feel free to reach out:

Email: YOUR_EMAIL_HERE

LinkedIn: YOUR_LINKEDIN_PROFILE




