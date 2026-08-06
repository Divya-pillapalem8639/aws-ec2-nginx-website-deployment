# AWS EC2 Nginx Website Deployment

## Project overview

This project demonstrates how to deploy a static portfolio website on an AWS EC2 Ubuntu server using Nginx. The deployment includes Linux server configuration, security group setup, web server installation, and website hosting.

## Architecture

User Browser → Internet → AWS Security Group → EC2 Ubuntu Instance → Nginx → Portfolio Website

## AWS services used

* Amazon EC2
* Security Groups
* IAM
* Ubuntu Linux
* Nginx

## Deployment steps

1. Launched an Ubuntu EC2 instance
2. Configured security groups (SSH and HTTP)
3. Connected using SSH
4. Updated the server
5. Installed Nginx
6. Deployed a custom HTML/CSS portfolio website
7. Restarted the Nginx service
8. Verified public website accessibility

## Linux commands used

```bash
sudo apt update
sudo apt upgrade -y
sudo apt install nginx -y
sudo systemctl status nginx
sudo systemctl restart nginx


## Project screenshots

* EC2 instance
* Security group configuration
* SSH connection
* Nginx status
* Portfolio website

## Outcome

Successfully deployed a production-style static website on AWS EC2 using Nginx and Linux administration commands.

## Author

**Divya**
AWS and DevOps portfolio project


