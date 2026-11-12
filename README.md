# Virtual_Enterprise_Lab

## Overview

This project documents the design and implementation of a virtual enterprise environment built using VMware Workstation, Windows Server, Windows 11, Ubuntu Server, Alpine Linux, Docker, and Nginx.

The environment was developed to gain hands-on experience with systems administration, networking, virtualization, Active Directory, Linux administration, routing, and network security.

## Technologies Used

- VMware Workstation
- Windows Server
- Active Directory
- DNS
- Group Policy
- SMB File Shares
- Windows 11
- Ubuntu Server
- Alpine Linux
- Docker
- Nginx
- iptables
- Linux Routing
- Subnetting
- Network Segmentation

## Network Design

| Network | Subnet |
|----------|----------|
| IT | 10.0.10.0/24 |
| HR | 10.0.20.0/24 |
| Accounting | 10.0.30.0/24 |
| Servers | 10.0.99.0/24 |

## Infrastructure

### Domain Controller

- Active Directory Domain Services
- DNS
- Group Policy
- File Shares

### Router

Ubuntu-based router providing:

- Inter-subnet routing
- NAT
- Firewall policies
- Network segmentation

### Services Server

- Docker
- Nginx
- Linux services

## Key Accomplishments

- Built a segmented enterprise network
- Implemented Active Directory and Group Policy
- Configured DNS and SMB file shares
- Created role-based access controls
- Implemented firewall-based network segmentation
- Resolved Kerberos, DNS, and GPO authentication issues
