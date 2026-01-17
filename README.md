# Windows-Server-2025-HomeLab
A hands on Home Lab Environment Featuring Windows Server 2025, Active Directory Domain Services, and Network Troubleshooting.

# Windows Server 2025 Home Lab Implementation

## Project Overview
This project demonstrates the deployment and configuration of an enterprise-grade home lab environment. It focuses on modern system administration tasks using Windows Server 2025.

## Technology Stack
* **Hypervisor:** VMware Workstation
* **Server OS:** Windows Server 2025 (Standard Edition)
* **Client OS:** Windows 10/11 Pro
* **Services:** Active Directory Domain Services (AD DS), DNS, DHCP

## Network Topology


## Implementation Phases
### 1. Hypervisor Configuration
* Allocated 4GB RAM, 2 vCPUs, and 60GB Storage for the Domain Controller.
* Configured a "Host-Only" or "NAT" virtual network to isolate the lab environment.

### 2. Active Directory Setup
* Promoted Server to Domain Controller (DC) for the domain `venky.local`.
* Created **Organizational Units (OUs)** for HR, Finance, and IT.
* Implemented User Management:
    * Created department-specific user accounts.
    * Configured "Password must be changed at next logon" policy.

### 3. Troubleshooting & Networking
* Verified DNS connectivity via `nslookup`.
* Successfully joined a Windows Client VM to the `venky.local` domain.
