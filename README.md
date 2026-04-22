# Windows Server 2022 Infrastructure Lab

## Overview
Built a Windows Server 2022 lab on VMware with 1 Domain Controller and 1 Windows 10 client to simulate a small enterprise environment.

## Implemented Services
- Active Directory Domain Services (AD DS)
- DNS
- DHCP
- Domain Join
- Group Policy Objects (GPO) - Drive Mapping
- Audit Logging

## Screenshots
### Active Directory Setup
![AD Setup](screenshots/join-domain/join_domain.png)

### DNS Configuration
![DNS Setup](screenshots/dns/DNS.png)

### DHCP Configuration
![DHCP Setup](screenshots/dhcp/DHCP.png)

### Group Policy - Map Drive
![GPO Setup](screenshots/gpo/GPO%20map%20drive.png)

### Event Logs (Audit)
![Audit Logs](screenshots/audit-log/audit.png)

## How to Set Up
1. Install **Windows Server 2022** on a VMware machine.
2. Set up **AD DS**, **DNS**, and **DHCP** as described in the steps.
3. Join a Windows 10 machine to the domain.
4. Apply **GPO** for drive mapping.
5. Enable **Audit Logging** to monitor domain activities.

## Conclusion
This setup simulates a small enterprise environment, enabling centralized management with Active Directory and enhanced security monitoring via auditing.
