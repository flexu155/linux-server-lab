Linux Server Lab
A hands-on Linux server project focused on system administration, networking, Nginx, troubleshooting, and DevOps fundamentals.
Project Overview
The goal of this project is to build and configure a Linux server in a virtual machine and learn the fundamentals of server administration through practical work.
The project is being developed step by step, with new technologies and DevOps practices added over time.
Environment
Linux: Ubuntu
Virtualization: Virtual Machine
Web Server: Nginx
Protocol: HTTP
Port: 80
What I Have Done
Created and configured a Linux virtual machine
Configured network connectivity
Verified internet access
Installed Nginx
Started and stopped the Nginx service using systemctl
Checked the Nginx service status
Verified listening ports using ss
Tested the web server using curl
Created a custom HTML page
Accessed the web server from the host machine
Inspected Nginx and system logs
Practiced troubleshooting by stopping and restarting the service
Architecture
Host Machine
     │
     ▼
Linux Virtual Machine
     │
     ▼
    Nginx
     │
     ▼
  HTML Page
Useful Commands
Check system information
cat /etc/os-release
uname -a
Check network configuration
ip addr
Check Nginx status
sudo systemctl status nginx
Start Nginx
sudo systemctl start nginx
Stop Nginx
sudo systemctl stop nginx
Check listening ports
sudo ss -tulpn
Test the web server
curl http://localhost/
curl -I http://localhost/
Check logs
sudo journalctl -u nginx
Screenshots
Screenshots documenting the project are available in the screenshots directory.
What I Learned
Through this project I am learning how Linux servers work in practice, including:
Basic Linux system administration
Services and systemd
Networking and ports
HTTP and web servers
Nginx
Command-line troubleshooting
Logs and basic diagnostics
Working with a Linux server through a terminal
Next Steps
The project will be expanded with additional DevOps technologies and practices:
SSH
Linux firewall
Bash scripting
Docker
Docker Compose
CI/CD
Infrastructure as Code
Cloud
Monitoring
Kubernetes
Status
🚧 In progress
This project is continuously evolving as I learn new Linux and DevOps concepts.
