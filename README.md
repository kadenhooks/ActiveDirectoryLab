# Active Directory Home Lab

## Description
Homelab documenting the setup and configuration of a Windows Server 2022 Active Directory environment. Covers AD DS, DNS, DHCP, Group Policy, and user/group management.

## Technologies Used
- Windows Server 2022
- Active Directory Domain Services (AD DS)
- DNS & DHCP
- Group Policy (GPO)
- VirtualBox

## Lab Environment
- **Hypervisor:** VirtualBox
- **Domain:** lab.local
- **DC IP:** 192.168.100.10
- **Client IP:** 192.168.100.4

## What I Configured
- Deployed Windows Server 2022 and promoted it to a Domain Controller
- Configured AD DS, DNS, and DHCP roles
- Built an OU structure with department-based organization
- Created domain user accounts and security groups
- Configured and linked Group Policy Objects for password policy and desktop wallpaper
- Domain joined a Windows 11 Enterprise client machine
- Configured DNS forwarding for external internet resolution

## Documentation
- [Setup](01-setup/README.md)
- [AD-DS](02-ad-ds/README.md)
- [DNS & DHCP](03-dns-dhcp/README.md)
- [Group Policy Objects](04-gpo/README.md)
- [Users & Groups](05-users-groups/README.md)



## Status
🟢 Complete
