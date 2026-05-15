
# Cisco Secure SSH Management Lab

## 🧩 Overview
This project demonstrates a secure Cisco network setup using SSHv2, ACL filtering, and role-based access control.

## Features
- SSHv2 enabled (secure remote access)
- Telnet disabled
- ACL restricted management access
- Multiple privilege levels (1, 3, 5, 15)
- Secure VTY configuration

## 🖧 Topology
- Router + Switch + 10 PCs (Enterprise Lab Simulation)

## IP Addressing Table
- Roter R1 192.168.10.1/24
- Switch S1 192.168.10.2/24
- PC1 192.168.10.10
          .
          .
          .
- PC10 192.168.10.19

## Roles
- Admin (privilege 15)
- Network Engineer (privilege 15)
- Operator (privilege 5)
- NOC (privilege 3)
- Helpdesk/Auditor (privilege 1)

## Configuration
- Router and switch configuration files are included in '/configs' directory

## Verification Commands
- show ip ssh
- show users
- show privilege
- show running-config | section line vty

## 🛠 Tools
- Cisco Packet Tracer
- Cisco IOS
- SSH / ACL / CLI
- Privilege Levels

## Goal
To simulate a real enterprise-level secure remote management system.

