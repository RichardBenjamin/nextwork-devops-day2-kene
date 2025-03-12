# Cloud Web App Deployment  

## Overview  
This project demonstrates how to set up a web application in the cloud and integrate it with AWS services. It includes deploying the app on an EC2 instance, configuring security settings, and automating deployments via GitHub integration.  

## Features  
- Deploy a web app on AWS EC2  
- Set up SSH access and security groups  
- Connect a GitHub repository with AWS CodeDeploy/GitHub Actions  
- Automate deployments for continuous integration  

## Prerequisites  
- AWS account  
- GitHub repository  
- SSH key pair for EC2 access  
- AWS CLI & Git installed  

## Setup Instructions  

### 1. Launch EC2 Instance  
- Create an EC2 instance with a supported OS (e.g., Ubuntu)  
- Configure security groups to allow SSH (port 22) and HTTP/HTTPS (ports 80/443)  

### 2. Connect to EC2  
```sh
ssh -i your-key.pem ubuntu@your-ec2-ip


