# AWS_3_TIER_ARCHITECTURE_PROJECT


🚀 AWS 3-Tier Web Application Architecture

📌 Project Summary

Implemented a secure and scalable 3-Tier Web Application Architecture using Amazon Web Services, ensuring high availability, controlled network access, and reliable performance.

This project demonstrates how real-world applications are deployed in the cloud using separate layers for user access, application processing, and database management.

⸻

🏗️ Architecture Overview

The infrastructure was divided into three layers to improve performance, security, and availability.

1. Presentation Layer

Services Used:
	•	Application Load Balancer

Configuration:
	•	Load Balancer deployed in public subnet
	•	Distributed incoming traffic across multiple servers
	•	Configured health checks to maintain availability

Outcome:
	•	Improved system uptime
	•	Ensured reliable user access

⸻

2. Application Layer

Services Used:
	•	Amazon EC2
	•	Auto Scaling Group
	•	Launch Template

Configuration:
	•	Application hosted on EC2 instances in private subnet
	•	Launch Template used for consistent configuration
	•	Auto Scaling adjusted instance count based on demand

Outcome:
	•	Achieved automatic scaling
	•	Maintained application performance during traffic changes

⸻

3. Database Layer

Services Used:
	•	Amazon RDS (MySQL)

Configuration:
	•	Database deployed in private subnet
	•	Access restricted using security groups
	•	Only application servers allowed to connect

Outcome:
	•	Improved database security
	•	Ensured reliable data storage

⸻

🌐 Network and Security Setup

Services Used:
	•	Amazon VPC
	•	Security Groups
	•	IAM Roles

Configuration:
	•	Created custom VPC
	•	Public subnet for Load Balancer
	•	Private subnets for EC2 and database
	•	Restricted access between layers

Outcome:
	•	Secure communication between components
	•	Prevented direct public access to backend resources

⸻

📊 Monitoring and Logging

Services Used:
	•	Amazon CloudWatch
	•	Amazon S3

Configuration:
	•	Monitored EC2 performance using CloudWatch
	•	Configured alerts based on CPU usage
	•	Enabled Load Balancer access logs in S3

Outcome:
	•	Improved system visibility
	•	Helped in troubleshooting and performance monitoring

⸻

🔄 How the System Works
	1.	User sends request to Load Balancer
	2.	Load Balancer forwards request to application server
	3.	Application server processes request
	4.	Data stored in RDS database
	5.	CloudWatch monitors system performance

⸻

🛠️ AWS Services Used
	•	EC2
	•	Application Load Balancer
	•	Auto Scaling Group
	•	RDS MySQL
	•	VPC
	•	CloudWatch
	•	S3
	•	IAM

⸻

🎯 Key Skills Demonstrated
	•	Cloud infrastructure deployment
	•	High availability implementation
	•	Network security configuration
	•	Auto Scaling setup
	•	Monitoring and logging

⸻

👤 Author

saravana kumar G
Cloud & DevOps Engineer

