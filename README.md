# Enterprise Hybrid Identity & Active Directory Lab

## Overview
A local, isolated enterprise lab environment built on Windows Server 2022 using Hyper-V. Designed to simulate an on-premises Active Directory infrastructure, focusing on core identity management, DNS, and secure network segmentation.

## Architecture & Network Topology
- **Hyper-V Virtual Switch:** \Lab-Internal\ (Isolated internal virtual switch preventing direct internet exposure).
- **Host / Gateway IP:** \10.0.0.1\ (Assigned to the host PC's virtual adapter to act as the local gateway).
- **Domain Controller (\DC-01\):** 
  - **Static IP:** \10.0.0.10\
  - **Subnet Mask:** \255.255.255.0\
  - **Default Gateway:** \10.0.0.1\
  - **Preferred DNS:** \127.0.0.1\ (Loopback configuration for local Active Directory domain resolution)

## Core Technologies Covered
- Windows Server 2022 Administration
- Hyper-V Virtualization & Network Isolation
- Active Directory Domain Services (AD DS) & DNS
- IP Addressing, Subnetting, and Unicast/Multicast/Broadcast Protocol Analysis
