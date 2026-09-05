# Scalable Flask Web Application with NLB & Auto Scaling

## Overview

Built and deployed a scalable Flask web application on AWS using
Amazon EC2, Network Load Balancer (NLB), Target Groups, and Auto Scaling.

The project demonstrates how incoming application traffic can be
distributed across multiple EC2 instances while maintaining application
availability and automatically adjusting compute capacity.

## Architecture

```text
                    Users
                      |
                      |
                      v
          Network Load Balancer
                      |
                      v
                Target Group
                      |
          +-----------+-----------+
          |                       |
          v                       v
      EC2 Instance 1          EC2 Instance 2
          |                       |
          +-----------+-----------+
                      |
                      v
                Flask Application

              Auto Scaling Group
                      |
                      v
          Automatically manages
             EC2 instances
