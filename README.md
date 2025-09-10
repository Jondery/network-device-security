# Network Device Security Labs

This repository contains Cisco Packet Tracer labs that demonstrate how to secure and harden network devices against unauthorized access and common threats.  

## Objectives
1. Learn and apply best practices for **network device hardening**.  
2. Configure **secure remote access** using SSH.  
3. Implement **DHCP snooping** to protect against rogue DHCP servers.  
4. Use **Access Control Lists (ACLs)** to filter and control traffic.  
5. Configure **NTP** for accurate time synchronization.  
6. Implement **AAA (Authentication, Authorization, Accounting)** for centralized security.  

## Labs Included
1. **Device Hardening**  
   - Disable unused services and ports.  
   - Set strong passwords and encrypt them.  
   - Configure login banners for legal/security warnings.  

2. **Configuring SSH**  
   - Generate RSA keys and configure SSH on routers/switches.  
   - Restrict Telnet and enforce SSH-only access.  

3. **DHCP Snooping**  
   - Enable DHCP snooping on switches.  
   - Prevent unauthorized/rogue DHCP servers from providing IP addresses.  

4. **Filtering Traffic with ACLs**  
   - Configure standard and extended ACLs.  
   - Control traffic based on IP, protocol, and port numbers.  
   - Apply ACLs to interfaces in inbound/outbound directions.  

5. **Configuring NTP (Network Time Protocol)**  
   - Set up NTP client on routers/switches.  
   - Synchronize time across network devices.  

6. **Configuring AAA**  
   - Implement local AAA for user authentication.  
   - Configure AAA with RADIUS/TACACS+ (if supported).  
   - Apply different privilege levels for user roles.  

## Key Learnings
- Network device hardening is the first step in securing IT infrastructure.  
- SSH provides encrypted and secure remote access compared to Telnet.  
- DHCP snooping and ACLs help prevent network attacks and unauthorized access.  
- Accurate time via NTP is essential for logs, authentication, and troubleshooting.  
- AAA ensures centralized authentication and granular access control.  
