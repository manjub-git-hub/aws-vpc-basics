# AWS VPC Basics – Subnets, Route Tables & Security Groups

## Overview
This project demonstrates a basic implementation of **Amazon Virtual Private Cloud (VPC)**.  
The objective is to understand core VPC components such as subnets, route tables, internet gateways, and security groups by creating a custom VPC.

## AWS Services Used
- Amazon VPC

## Project Implementation

### Custom VPC
- Created a custom VPC with IPv4 CIDR block `10.0.0.0/16`
- Used default tenancy
- Left the default VPC untouched as per AWS best practices

### Subnets
- Created a **Public Subnet** with CIDR `10.0.1.0/24`
- Created a **Private Subnet** with CIDR `10.0.2.0/24`
- Associated subnets with appropriate route tables

### Internet Gateway
- Created and attached an Internet Gateway
