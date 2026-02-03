# TASK 12 – Commands Used
## 1. SSH Key Permission
chmod 400 aws.pem

## 2. Connect to EC2
ssh -i aws.pem ubuntu@PUBLIC-IP

## 3. Update System
sudo apt update -y

## 4. Install Nginx Web Server
sudo apt install Nginx -y

## 5. Start Nginx Service
sudo systemctl start Nginx

## 6. Enable Nginx on Boot
sudo systemctl enable Nginx

## 7. Check Status
sudo systemctl status Nginx

## 8. Create Custom Web Page
cd /var/www/html                
sudo vi index.html             
### Added Content
- `<h1>Welcome to My First AWS EC2 Server</h1>`
- `<p>Task 12 completed</p>`

## 9. Restart Apache
sudo systemctl restart Nginx

## 10. Verify in Browser
http://PUBLIC-IP

## 11. Instance Management
### Stop instance               
From AWS Console → Stop Instance

# Terminate instance after task
From AWS Console → Terminate Instance

## Security Group Rules
- Port 22 → SSH → My IP  
- Port 80 → HTTP → Anywhere

## Output
- SSH connection successful  
- Web page hosted and accessible  
- EC2 running
