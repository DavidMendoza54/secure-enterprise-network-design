# Secure Enterprise Network Design

## Overview
This project is a reconstructed cybersecurity architecture case study based on an academic network design project. The goal was to design a secure enterprise network that protects internal systems while maintaining availability for public-facing services and cloud-based resources.

The design focuses on network segmentation, firewall placement, access control, cloud service integration, backup planning, secure communication paths, and defense-in-depth principles.

## Network Diagram

![Secure Enterprise Network Diagram](Diagrams/Secure-Enterprise-Network.png)

## Objectives
- Design a secure and reliable enterprise network architecture
- Protect internal systems, users, servers, and sensitive data
- Maintain availability for public-facing and cloud-based services
- Reduce lateral movement through network segmentation
- Separate guest Wi-Fi, printers, users, servers, and management systems
- Support remote site connectivity and business continuity
- Apply access control and defense-in-depth security principles

## Design Approach
For this project, I approached the network design from the perspective of protecting internal business systems while still allowing users to access cloud services, public-facing resources, printers, and remote site connections.

The main security concern was limiting unnecessary exposure between the internet, cloud services, public-facing systems, internal users, servers, printers, guest Wi-Fi, remote sites, and administrative systems. To reduce risk, the environment was separated into different network zones based on purpose and risk level.

Public-facing systems are separated from internal resources, guest Wi-Fi is isolated from business systems, printers are placed in their own segment, and administrative tools are separated into a management network. This helps reduce the chance that one compromised device or service could expose the rest of the environment.

## Security Design Decisions
| Design Decision | Reason |
| --- | --- |
|Separate public-facing services from internal systems|Reduces the chance of an exposed service leading directly to sensitive internal resources.|
|Segment users, servers, printers, guest Wi-Fi, and management systems|Limits lateral movement and separates systems based on risk and purpose.|
|Restrict administrative access to a management network|Protects high-privilege systems from unnecessary exposure.|
|Place firewall controls between network zones|Allows traffic to be filtered and limited based on business need.|
|Include cloud services and backup platforms|Supports productivity, identity services, email, recovery, and business continuity.|
|Document remote site connections|Helps support secure communication and troubleshooting across multiple locations.|

## Security Concepts Used
- Network Segmentation
- Defense-in-Depth
- Firewall Placement
- Access Control
- DMZ Architecture
- Guest Network Isolation
- Management Network Separation
- Cloud Service Integration
- Backup and Recovery Planning
- Risk Management
- Business Continuity
- Secure Network Design

## Lessons Learned
This project helped me better understand that secure network design is not only about connecting systems, but about controlling how systems communicate.

I learned how segmentation, access control, firewall placement, and documentation work together to reduce risk and support reliable operations. If this design were expanded into a real environment, I would add centralized logging, vulnerability scanning, security monitoring, and identity-based access controls to improve visibility and response capabilities.

## Project Files
- `/diagrams` - Network topology and architecture diagrams
- `/documentation` - Written security architecture and project notes

# secure-enterprise-network-design
This project is a reconstructed academic cybersecurity architecture case study.
