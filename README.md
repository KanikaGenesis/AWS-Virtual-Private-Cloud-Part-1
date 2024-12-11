# AWS Virtual Private Cloud (VPC) Project Series - Part 1

Welcome to Part 1 of the AWS VPC Project Series! This repository documents the initial steps to create and configure a Virtual Private Cloud (VPC) using AWS services.  

## Overview  

A Virtual Private Cloud (VPC) is an isolated section of AWS cloud infrastructure that ensures private and secure hosting of resources. This project walks you through the setup and basic configurations needed for a fully functional VPC.  

## Features Covered  

- Setting up a VPC with an IPv4 CIDR block  
- Creating and configuring public and private subnets  
- Attaching an Internet Gateway and configuring route tables  
- Setting up security groups and network ACLs  
- Launching public and private EC2 instances  
- Testing connectivity between servers and to the internet  

## Prerequisites  

- AWS account  
- Basic understanding of networking concepts  
- AWS CLI or access to the AWS Management Console  

## Steps in this Guide  

1. **VPC Creation**  
   - Define a CIDR block  
   - Understand default VPCs and subnets  

2. **Subnet Configuration**  
   - Create and label subnets (public/private)  
   - Set unique CIDR blocks for each subnet  

3. **Internet Gateway**  
   - Attach an Internet Gateway to the VPC  
   - Configure route tables to establish internet connectivity  

4. **Security Setup**  
   - Create and associate security groups  
   - Define inbound and outbound rules  

5. **Network ACLs**  
   - Configure default and custom network ACLs for subnets  

6. **Launching Resources**  
   - Deploy EC2 instances in public and private subnets  
   - Set up SSH keys for direct access  

7. **Connectivity Testing**  
   - Use tools like `ping` and `curl` to verify internal and external communication  

## Testing and Troubleshooting  

- Verify server connectivity using `ping` and `curl` commands  
- Troubleshoot errors by reviewing route table and ACL configurations  

## Resources  

- [AWS Documentation on VPCs](https://docs.aws.amazon.com/vpc/latest/userguide/what-is-amazon-vpc.html)  
- [NextWork.org](http://www.nextwork.org)  

## Connect with me 

**Kanika Mathur**  
- [GitHub Profile](https://github.com/KanikaGenesis)  
- [LinkedIn](https://www.linkedin.com/in/kanika-mathur-083080121)  

---

