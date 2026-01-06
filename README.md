# End-to-End-Cloud-DevOps-Automation-Project-CI-CD-IaC-
This project demonstrates a complete end-to-end DevOps automation workflow using modern DevOps tools and AWS cloud services. The goal of the project is to automate build, test, infrastructure provisioning, and deployment of a web application using CI/CD pipelines and Infrastructure as Code (IaC).

This project is designed to showcase real-world DevOps skills suitable for DevOps Engineer (Fresher / Junior) roles.

🛠️ Tech Stack & Tools

Cloud Platform: AWS

CI/CD: Jenkins

Containerization: Docker

Infrastructure as Code: Terraform

Version Control: Git, GitHub

OS: Linux (Ubuntu / Amazon Linux)

Monitoring: AWS CloudWatch

Scripting: Bash

⚙️ Architecture Overview

Developer pushes code to GitHub

Jenkins pipeline triggers automatically

Jenkins:

Pulls source code

Builds Docker image

Runs basic tests

Terraform provisions AWS infrastructure:

EC2

VPC

Security Groups

IAM Roles

Docker container is deployed on AWS EC2

Application is monitored using AWS CloudWatch

🔄 CI/CD Pipeline Workflow

Automated code integration using GitHub

Jenkins pipeline for build and deployment

Docker used to ensure consistent runtime environment

Terraform used for automated infrastructure provisioning

Zero manual intervention during deployment

📂 Project Structure
├── Jenkinsfile
├── Dockerfile
├── terraform/
│   ├── main.tf
│   ├── variables.tf
│   ├── outputs.tf
├── app/
│   ├── source_code
├── README.md

🧪 Key Features

End-to-end automated CI/CD pipeline

Dockerized application deployment

Infrastructure provisioning using Terraform (IaC)

Secure AWS configuration using IAM roles and Security Groups

Improved deployment consistency and reliability

Reduced manual deployment effort by 80%

📈 Learning Outcomes

Hands-on experience with real-world DevOps tools

Strong understanding of CI/CD concepts

Practical knowledge of AWS cloud infrastructure

Experience with Infrastructure as Code (Terraform)

Linux system and deployment workflow understanding

👨‍💻 Author

Karthik Yadav N

GitHub: https://github.com/Karthi-yadav

LinkedIn: https://linkedin.com/in/karthi5

📌 Note

This project was built as part of DevOps hands-on training and self-learning to gain practical experience in cloud-based DevOps workflows.
