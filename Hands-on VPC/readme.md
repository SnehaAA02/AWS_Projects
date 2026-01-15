# AWS VPC Networking – Hands-on Projects
This repository documents my first set of AWS networking projects where I built a complete **Virtual Private Cloud (VPC)** architecture from scratch.  
The goal of these projects was to understand **how traffic flows securely between the internet, public resources, and private resources in AWS**.


## What I Learned
Through these projects, I gained practical experience with:

- Designing a secure VPC network
- Separating public and private resources
- Controlling traffic using route tables, security groups, and NACLs
- Deploying EC2 instances in different network layers


## Architecture
<img width="600" height="500" alt="image" src="https://github.com/user-attachments/assets/d27eb4fa-8214-4ff3-9894-21feee9d8a3c" />

This project demonstrates a custom-designed AWS VPC architecture with clear separation between public and private subnets. The setup includes dedicated route tables, network ACLs, and security groups to control traffic flow and enforce layered security. An Internet Gateway enables public access only where required, while private resources remain isolated. EC2 instances deployed in each subnet showcase real-world public-facing and internal workloads.
