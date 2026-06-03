# Security Architecture

## Network Segmentation
The network is separated into different security zones to reduce risk, control access, and limit lateral movement. Public-facing systems are isolated from internal resources so that if an internet-facing service is compromised, the attacker does not automatically gain access to sensitive internal systems.

User devices, servers, printers, guest Wi-Fi, and administrative systems should be placed into separate network segments based on their purpose and risk level.

## Access Control
Access is limited using least privilege principles, meaning users and systems should only have access to the resources they need to perform their role. Firewall rules and network policies are used to control communication between zones and reduce unnecessary exposure.

Administrative access should be restricted to trusted devices and monitored closely because admin accounts and management systems are higher-value targets.

## Firewall Placement
Firewalls are positioned between the internet, public-facing services, and internal network zones to inspect, filter, and restrict traffic. This allows the organization to control which systems can communicate with each other and helps prevent unauthorized access.

Firewall rules should be reviewed regularly to remove outdated or unnecessary access.

## Availability
The design supports reliable communication and business continuity by documenting critical systems, network paths, and security controls. Clear documentation helps IT teams troubleshoot issues faster and respond more effectively during outages or security incidents.

## Risk Reduction
This design reduces overall exposure by separating sensitive systems, limiting unnecessary access, and applying layered security controls. Segmentation, access control, firewall filtering, and documentation all work together to improve security posture and support safer day-to-day operations.

If this design were expanded into a real environment, I would also include centralized logging, vulnerability scanning, endpoint protection, and security monitoring to improve visibility and incident response.
