# Security Architecture

## Network Segmentation

The network is separated into different security zones to reduce risk and limit lateral movement. Public-facing systems are separated from internal resources, while user devices, servers, printers, guest Wi-Fi, and administrative systems are placed into separate network segments based on their purpose and risk level.

This design helps prevent one compromised system or network area from automatically exposing the rest of the environment.

## Access Control

Access is limited based on business need and least privilege principles. Firewall rules and network policies control communication between zones so that only approved traffic is allowed.

Administrative access is restricted to a management segment because admin workstations, monitoring tools, and infrastructure management systems are higher-value targets.

## Firewall Placement

Firewalls are positioned between the internet, public-facing services, cloud services, and internal network zones to inspect and restrict traffic.

This allows the organization to control communication between public systems, internal users, servers, guest Wi-Fi, printers, and remote sites.

## Cloud and Backup Integration

The design includes cloud-based services such as Microsoft 365, identity services, email, and backup platforms. These services support productivity, authentication, email security, and business continuity.

Backup services help protect important data and support recovery in the event of accidental deletion, system failure, or a security incident.

## Availability

The design supports reliable communication and business continuity by documenting critical systems, communication paths, remote site connections, and security controls.

Clear documentation helps IT teams troubleshoot issues faster and respond more effectively during outages or security incidents.

## Risk Reduction

This design reduces exposure by separating sensitive systems, limiting unnecessary access, and applying layered security controls.

Segmentation, access control, firewall filtering, cloud backup, and documentation work together to improve security posture and support safer day-to-day operations.
