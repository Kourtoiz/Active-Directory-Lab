# Active Directory Lab

## Overview

This project documents my hands-on experience building and managing an Active Directory environment using Windows Server 2022 and VMware Workstation.

## Objectives

- Deploy a Windows Server 2022 Domain Controller
- Configure Active Directory Domain Services (AD DS)
- Create and manage users and groups
- Configure DNS and DHCP
- Join Windows clients to the domain
- Apply Group Policies (GPOs)
- Practice troubleshooting common Active Directory issues

## Lab Environment

### Virtual Machines

| Machine | Operating System | Purpose |
|----------|----------|----------|
| DC01 | Windows Server 2022 | Domain Controller |
| CLIENT01 | Windows 11 | Domain Client |
| CLIENT02 | Windows 11 | Domain Client |

## Technologies Used

- VMware Workstation
- Windows Server 2022
- Active Directory
- DNS
- DHCP
- Group Policy
- Windows 11

## Implemented Tasks

- [x] Install Windows Server 2022
- [x] Configure Static IP
- [x] Install Active Directory Domain Services
- [x] Promote Server to Domain Controller
- [ ] Create Organizational Units
- [ ] Configure Group Policies
- [ ] Configure DHCP
- [ ] Add Additional Clients

## Screenshots

## Domain Controller

![Domain Controller](images/domain-controller.png)

The server was promoted to a Domain Controller using Active Directory Domain Services (AD DS). The domain was configured to manage users, groups, and authentication within the lab environment.

## Lessons Learned

This lab has helped me understand how Active Directory, DNS, users, groups, and domain-joined computers work together in a Windows enterprise environment.
