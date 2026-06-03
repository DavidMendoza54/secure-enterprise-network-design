# Security Architecture

## Network Segmentation
The network is separated into different zones to reduce risk and limit lateral movement. Public-facing systems are separated from internal resources, while administrative access is restricted to a management segment.

## Access Control
Access is limited based on business need and least privilege principles. Firewall rules and network policies control communication between zones.

## Firewall Placement
Firewalls are positioned between the internet, public-facing services, and internal systems to inspect and restrict traffic.

## Availability
The design supports reliable communication and business continuity by documenting critical systems, communication paths, and security controls.

## Risk Reduction
This design reduces exposure by separating sensitive systems, limiting unnecessary access, and applying layered security controls.