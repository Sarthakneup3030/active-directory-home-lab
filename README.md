# Active Directory Home Lab

## Overview
This project documents my hands-on Active Directory home lab built using Windows Server and VirtualBox. The goal of this lab is to develop practical IT support and help desk skills commonly used in enterprise environments.

Through this lab, I practiced:
- Active Directory administration
- User and group management
- Password resets and account unlocks
- Group Policy configuration
- Domain joining computers
- Basic network troubleshooting

---

# Lab Environment

## Technologies Used
- Windows Server 2022
- Windows 10
- Oracle VirtualBox
- Active Directory Domain Services (AD DS)
- Group Policy Management
- DNS

---

# Network Configuration

| Device | Role | IP Address |
|---|---|---|
| Server2022 | Domain Controller | 192.168.1.10 |
| Win10Client | Domain Joined PC | 192.168.1.20 |

---

# Active Directory Tasks Completed

## User Management
- Created user accounts
- Reset passwords
- Unlocked locked accounts
- Disabled and enabled users
- Created Organizational Units (OUs)

## Group Management
- Created security groups
- Added and removed users from groups

## Computer Management
- Joined Windows 10 machine to domain
- Renamed computers
- Verified domain connectivity

## Group Policy
- Configured password policies
- Applied desktop restrictions
- Tested Group Policy updates

---

# Screenshots

## Active Directory Users and Computers
![ADUC Screenshot](screenshots/aduc-users.png)

## Group Policy Management
![GPO Screenshot](screenshots/group-policy.png)

## Domain Join Successful
![Domain Join](screenshots/domain-join.png)

---

# Example Help Desk Scenarios

## Ticket #001 - User Account Locked

### Issue
User unable to login after multiple failed password attempts.

### Resolution
- Opened Active Directory Users and Computers
- Located user account
- Unlocked account
- Reset password
- Verified successful login

---

## Ticket #002 - Computer Cannot Join Domain

### Issue
Windows 10 client failed to join domain.

### Troubleshooting Steps
- Verified DNS configuration
- Checked network connectivity
- Confirmed domain controller availability
- Re-attempted domain join

### Resolution
Successfully joined client machine to domain.

---

# Skills Demonstrated
- Active Directory Administration
- Windows Server 2022
- User & Group Management
- IT Troubleshooting
- DNS Configuration
- Group Policy Management
- Documentation
- Virtualization

---

# Future Improvements
- Add PowerShell automation
- Configure DHCP server
- Create file sharing permissions
- Implement Remote Desktop Services
- Explore Microsoft Entra ID integration

---

# Author

## Sarthak Neupane

Aspiring IT Support / Help Desk Technician focused on building practical system administration and troubleshooting skills.
