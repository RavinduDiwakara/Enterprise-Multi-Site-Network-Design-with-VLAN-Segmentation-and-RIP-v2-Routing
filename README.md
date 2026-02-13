# Enterprise-Multi-Site-Network-Design-with-VLAN-Segmentation-and-RIP-v2-Routing
Designed and configured a multi-branch enterprise network using VLAN segmentation, inter-VLAN routing, and RIP v2 dynamic routing in Cisco Packet Tracer.

📌 Project Overview

This project demonstrates the design and configuration of a multi-site enterprise network using Cisco Packet Tracer.

The network includes a Branch office, HQ office, and Web network interconnected using dynamic routing (RIP v2). VLAN segmentation is implemented to logically separate departments, improving security and network management.

This project highlights fundamental networking concepts essential for DevOps and infrastructure engineering roles.

🏗 Network Architecture

The network consists of:

Branch Router and Switch

HQ Router and Switch

Web Router

DHCP Server

DNS Server

Web Server

Multiple VLANs for department segmentation

🔧 Technologies & Concepts Used

IP Subnetting and CIDR

VLAN Configuration (Layer 2 Segmentation)

Inter-VLAN Routing (Router-on-a-Stick)

RIP v2 Dynamic Routing Protocol

DNS Server Configuration

DHCP Configuration

Trunking between Switch and Router

Multi-router topology design

🌐 VLAN Structure
VLAN ID	Department	Default Gateway
10	IT	192.168.10.1
20	HR	192.168.10.129
30	Sales	192.168.10.193
40	DHCP	Configured

HQ VLANs:

VLAN 11 – Management

VLAN 12 – Wireless

🔁 Routing Configuration

RIP Version 2 was configured on:

Branch Router

HQ Router

Web Router

This allows automatic route exchange between networks and enables inter-site communication.

🖥 Services Configured

DNS Server (A record for ict.com)

DHCP Server

Web Server accessible through routing configuration

🎯 Skills Demonstrated

Network Planning & Design

Subnet Calculation

VLAN Implementation

Routing Protocol Configuration

Infrastructure Troubleshooting

Enterprise Network Simulation

🚀 Relevance to DevOps

Understanding networking fundamentals is critical for DevOps engineers, especially when working with:

Cloud Infrastructure (AWS / Azure)

Kubernetes networking

Load Balancers

VPC & Subnet design

CI/CD pipelines in distributed systems

This project strengthens the networking foundation required for modern DevOps practices.
