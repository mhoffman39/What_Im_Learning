# Getting Inside the Virtual Machine with EC2 and VPC

## EC2
Virtual machine that runs software of your choice

Elastic IP
Load balancers
Auto Scaling Groups
## VPC
Virtual private cloud

Separates resources from user to user on AWS

Each resource on the VPC has its own private IP address

VPC is free! (up to 5)

## Creating a Virtual Private Cloud (VPC)

![Architecture](./architecture.png)

**Security Group** - defines allowed incoming/outgoing IP addresses and ports. Kind of like a mini-firewall.

VPCs use **routing tables** to configure routing destinations for traffic coming out of the VPC

Network Access Control List - acts as an IP filtering table

Subnet - an isolated area inside a Virtual Private Cloud with its own CIDR block, routing table, and NACL. Each VPC can have multiple subnets. An instance must be inside a subnet.