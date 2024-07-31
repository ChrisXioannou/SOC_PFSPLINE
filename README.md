# Network Security Lab with pfSense and Active Directory

## Description
This project simulates a secure, virtualized network environment using **pfSense** for firewall and network security management and **Windows Server 2022** for Active Directory services. The setup includes configuring network adapters for NAT and internal communications, integrating security tools like **Sysmon** and **CrowdSec**, and practicing real-world network administration tasks.

## Environments Used
- **pfSense**: Installed on a Hyper-V virtual machine, configured with NAT and two internal network adapters.
- **Windows Server 2022**: Deployed as a virtual machine, serving as a Domain Controller with Active Directory.
- **Hyper-V**: Used for virtual machine management and network setup.

## Configuration and Tools
### pfSense
- Setup with NAT to manage network traffic and two internal adapters for isolated network segments.
- Configured firewall rules and VPN for secure remote access.

### Windows Server 2022
- Installed and configured Active Directory to manage user accounts and security policies.
- Used Microsoft’s media creation tool to create installation support and ISO.

### Sysmon
- Installed on the Windows Server to enhance Windows event logs with detailed system monitoring data.
- Utilized an XML configuration file for Sysmon, focusing on capturing security-relevant events like process creations and network connections.

### CrowdSec
- Deployed as an additional security layer, utilizing behavior analysis to detect and mitigate threats.
- Integrated with pfSense for real-time security monitoring and response.

## Technical Details and Explanations
### pfSense Configuration
- Set up as the network's primary firewall and gateway, controlling traffic flow and enforcing security policies.
- Utilized for setting up VPNs, managing NAT, and separating network traffic into different security zones (LAN, DMZ).

### Active Directory (AD) on Windows Server 2022
- Configured to manage domain services, user authentication, and authorization within the network.
- Implemented Group Policies to control user and computer configurations.

### Sysmon
- Enhanced the visibility of system activities, crucial for detecting anomalous behavior and security incidents.

### CrowdSec
- Described as a collaborative security tool that uses data from other users to provide automated responses to threats, effectively functioning as a community-driven IDS/IPS system.

## Project Outcomes
This project provided practical experience in network security, system administration, and the use of advanced monitoring tools. It highlighted the implementation of pfSense as a versatile firewall solution, the management of a Windows Server environment with Active Directory, and the integration of security tools like Sysmon and CrowdSec to enhance network defense capabilities.

## Acknowledgments
Special thanks to the LetsDefend platform for providing the course materials that guided the setup and configuration processes, despite the original instructions being tailored for VirtualBox. The extra practice of configuring the environment in Hyper-V added valuable learning experiences.
