# AWS PublicIP-PrivateIP-ElasticIP

![AWS](https://img.shields.io/badge/AWS-Cloud-orange)
![EC2](https://img.shields.io/badge/Service-EC2-blue)
![VPC](https://img.shields.io/badge/Service-VPC-purple)
![Networking](https://img.shields.io/badge/Topic-IP_Addressing-green)

---

## Project Description

This lab demonstrates the concept of **IP addressing in AWS Cloud** using Amazon EC2 instances.  
The project focuses on understanding how AWS assigns and manages **Public IP**, **Private IP**, and **Elastic IP** addresses for cloud resources.
The objective is to learn the difference between dynamic and static IP allocation and how Elastic IP ensures consistent external connectivity.

---

## AWS Services Used

- Amazon EC2
- Elastic IP

---
## Phase 1 — EC2 Instance Creation

### Instance Created

![Instance Created](screenshots/phase1-instance/Instance-Created.png)

### SSH Login

![SSH Login](screenshots/phase1-instance/SSH-Login.png)

---

## Phase 2 — Public IP Change After Restart

### Instance Stopped

![Instance Stopped](screenshots/phase2-public-ip/Instance-Stopped.png)

### Public IP After Restart

![Public IP After Restart](screenshots/phase2-public-ip/PublicIP-after-InstanceRestart.png)

---

## Phase 3 — Elastic IP Configuration

### Elastic IP Allocation

Allocated a static public IP from AWS.

![Elastic Allocation](screenshots/phase3-elastic-ip/ElasticIP-allocated.png)

### Elastic IP Association

Associated Elastic IP with EC2 instance to maintain a permanent public endpoint.

![Elastic Association](screenshots/phase3-elastic-ip/Instance-with-elasticIP.png)

### Elastic IP Disassociation

![Disassociate IP](screenshots/phase3-elastic-ip/DissassociateIP.png)

### Release Elastic IP 

![Release Elastic IP](screenshots/phase3-elastic-ip/Release-ElasticIP.png)

### After Removing ElasticIP

![IP After Elastic IP](screenshots/phase3-elastic-ip/IP-after-elasticIP.png)

---

## IP Address Concepts

### Public IP
- Automatically assigned by AWS
- Used for internet communication
- Changes when instance stops and starts

### Private IP
- Used within AWS VPC network
- Enables internal communication between resources
- Remains constant for the instance

### Elastic IP
- Static public IP provided by AWS
- Persists across instance restarts
- Can be reassigned to another instance

---
## Author

**G Gayathri**  
AWS Cloud Learner
