# devops_day-12_worklog
# Cloud Basics Using AWS 

## Objective
To understand basic cloud infrastructure by launching an AWS EC2 Linux instance, connecting via SSH, installing a web server, and hosting a simple webpage.

## Tools Used
- AWS EC2 
- Ubuntu Linux
- Nginx Web Server
- SSH Client (Git Bash)

## Steps Performed
### 1. Created AWS Free Tier Account
- Logged into AWS Console  
- Accessed EC2 Dashboard

### 2. Launched EC2 Instance
- AMI: Ubuntu 22.04  
- Instance Type: t2.micro  
- Created key pair: aws.pem  
- Configured Security Group:
  - Port 22 – SSH  
  - Port 80 – HTTP

### 3. Connected via SSH
- Used key pair to securely access server from local machine.

### 4. Installed Web Server
- Installed Nginx  
- Started and enabled service

### 5. Accessed Application
- Opened browser using Public IP  
- Verified default Nginx page  
- Hosted custom HTML page

### 6. Instance Management
- Stopped instance after use  
- Understood termination process

## Architecture
User → Internet → Security Group (22,80) → EC2 Ubuntu → Nginx Web Server → Web Page

## Deliverables
- EC2 running instance screenshot  
- SSH connection terminal proof  
- Web page accessed via Public IP

## Learning Outcome
- Understanding of cloud basics  
- EC2 lifecycle  
- Security groups  
- SSH authentication  
- Web hosting on Linux server

## Conclusion
Successfully launched and configured an AWS EC2 instance, hosted a web application, and understood fundamental cloud concepts using AWS Free Tier.
