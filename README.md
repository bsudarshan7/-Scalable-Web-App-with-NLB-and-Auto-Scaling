
             # Scalable Web Application using NLB & Auto Scaling

Built a scalable Flask web application on AWS using Network Load
Balancer (NLB) and Auto Scaling.

Completed an end-to-end AWS project demonstrating network-level
traffic distribution, high availability, health checks, and automatic
EC2 instance scaling.

## Technologies & Services Used:

- Amazon EC2
- Network Load Balancer (NLB)
- Target Groups & Health Checks
- Auto Scaling Group (ASG)
- Launch Templates
- Custom AMI
- Ubuntu Linux
- Python Flask
- systemd Services
- VPC
- Security Groups

## Project Workflow:

1. Developed and deployed a CloudMart Flask web application on EC2.
2. Configured the Flask application to run on the required application
   port.
3. Created a custom AMI containing the application and server
   configuration.
4. Configured a Launch Template for consistent EC2 instance
   provisioning.
5. Created a Target Group and configured health checks for the Flask
   application.
6. Deployed a Network Load Balancer to distribute incoming traffic
   across healthy EC2 instances.
7. Configured an Auto Scaling Group to maintain the required number
   of application instances.
8. Configured automatic application startup using systemd.
9. Verified NLB connectivity, target health, traffic forwarding, and
   application availability.
10. Tested the scalable architecture with multiple EC2 instances.

## Key Outcomes:

- High Availability Architecture
- Network Load Balancing using NLB
- Traffic Distribution across EC2 instances
- Target Health Monitoring
- Automatic EC2 Instance Scaling
- Infrastructure Provisioning using Launch Templates
- Linux Application Hosting
- Scalable Flask Application Deployment

## Architecture:

Users
   |
   v
Network Load Balancer
   |
   v
Target Group
   |
   +-------------------+
   |                   |
   v                   v
EC2 Instance 1     EC2 Instance 2
   |                   |
   +---------+---------+
             |
             v
       Flask Application

             ^
             |
     Auto Scaling Group
             ^
             |
      Launch Template
             ^
             |
         Custom AMI

## Networking Concepts:

- TCP/IP
- Network Load Balancing
- Traffic Distribution
- Client-Server Communication
- Target Groups
- Health Checks
- VPC Networking
- Network Interfaces
- Security Groups

## What I Learned:

- Understanding Network Load Balancer architecture
- Configuring EC2 instances for scalable deployments
- Understanding traffic flow through an NLB
- Configuring Target Groups and health checks
- Working with Auto Scaling Groups
- Using Launch Templates and Custom AMIs
- Linux server administration
- Deploying and managing Flask applications on AWS
- Understanding AWS networking and high-availability architecture
