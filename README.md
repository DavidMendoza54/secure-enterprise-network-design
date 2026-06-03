
# Secure Enterprise Network Design

## Overview
This project is a reconstructed cybersecurity architecture case study based on an academic network design project. The goal was to design a secure enterprise network that protects internal systems while maintaining availability for public-facing services.

The design focuses on network segmentation, firewall placement, access control, secure communication paths, and defense-in-depth principles to reduce risk and improve overall security.

## Network Diagram

![Secure Enterprise Network Diagram](Diagrams/Secure-Enterprise-Network.png)

## Objectives
- Design a secure and reliable enterprise network architecture
- Protect internal systems and sensitive data from unauthorized access
- Maintain availability for public-facing services
- Reduce lateral movement through network segmentation
- Apply access control and defense-in-depth principles
- Support business continuity through clear documentation

## Design Approach
For this project, I approached the network design from the perspective of protecting internal business systems while still allowing public-facing services to remain available.

The main security concern was limiting unnecessary exposure between the internet, public services, internal users, servers, and administrative systems. To reduce risk, I separated the environment into different security zones and placed controls between those zones.

Public-facing services were separated from internal resources, user devices were separated from servers and administrative systems, and management access was treated as a higher-risk function that should be restricted and monitored.

## Security Design Decisions
| Design Decision | Reason |
|Separate public-facing services from internal systems|Reduces the chance of a compromised public service exposing internal resources|
|Use segmented network zones|Limits lateral movement and separates different types of systems|
|Restrict administrative access|Protects high-privilege systems from unnecessary exposure|
|Place firewall controls between zones|Allows traffic to be filtered and limited based on business need|
|Document network paths and critical systems|Supports troubleshooting, incident response, and business continuity|

## Architecture Summary
The proposed network separates systems into security zones, including a public-facing area, internal network, server environment, and management segment. This structure helps limit unauthorized access and reduce lateral movement if one area is compromised.

## Security Concepts Used
- Network Segmentation
- Defense-in-Depth
- Firewall Placement
- Access Control
- DMZ Architecture
- Risk Management
- Secure Network Design
- Business Continuity

## Lessons Learned
This project helped me better understand that secure network design is not only about connecting systems, but about controlling how systems communicate.

I learned how segmentation, access control, firewall placement, and documentation work together to reduce risk and support reliable operations. If this design were expanded into a real environment, I would add centralized logging, vulnerability scanning, security monitoring, and identity-based access controls to improve visibility and response capabilities.

## Project Files
- `/diagrams` - Network topology and architecture diagrams
- `/documentation` - Written security architecture and project notes

# secure-enterprise-network-design
Project for my resume. 

