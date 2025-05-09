# Project 1: Simulated Business Network in Cisco Packet Tracer

## Objective
Design and implement a small business network using Cisco Packet Tracer. The network includes VLAN segmentation for three departments, a Layer 3 switch for inter-VLAN routing, and a centralized DHCP server for IP address distribution.

## Devices Used
- Cisco 2960 Switches (3 total): HR, Sales, IT departments
- Cisco 3560 Layer 3 Switch (1): Core Switch
- PCs (6 total): Two per department
- DHCP Server (1): Assigns IP addresses to all devices

## Network Desing

| Department | VLAN ID | IP Range         | Devices             |
|------------|---------|------------------|---------------------|
| HR         | 10      | 192.168.10.0/24  | HR-PC1, HR-PC2      |
| Sales      | 20      | 192.168.20.0/24  | Sales-PC1, Sales-PC2|
| IT         | 30      | 192.168.30.0/24  | IT-PC1, IT-PC2      |
