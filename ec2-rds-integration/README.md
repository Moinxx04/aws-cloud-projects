# EC2 and RDS Integration

## Overview
This project demonstrates connecting a **private EC2 instance** to an **Amazon RDS MySQL database**.

## Architecture
- Public EC2 → SSH access
- Private EC2 → Application server
- RDS → MySQL database
- NAT Gateway → Internet access for private EC2

## What I did
- Created a VPC with public & private subnets
- Launched EC2 instances in correct subnets
- Created an RDS MySQL database
- Connected EC2 to RDS securely using security groups

## AWS Services Used
- Amazon EC2
- Amazon RDS (MySQL)
- VPC
- Subnets
- NAT Gateway
- Security Groups

## Outcome
Private EC2 successfully connected to RDS without exposing database publicly.

## Key Learning
- Difference between public and private resources
- Secure database access using security groups
- Real-world cloud architecture
