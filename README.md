# Network Security SOC Lab 

## Description
This project simulates a secure, virtualized network environment using **pfSense** for firewall and network security management and **Windows Server 2022** for Active Directory services. The setup includes configuring network adapters for NAT and internal communications, integrating security tools like **Sysmon** and **CrowdSec**, and practicing real-world network administration tasks within a Security Operations Center (SOC) simulation.
 
## Environments Used
- **Hyper-V**: Used for virtual machine management and network setup.
  **Virtual Machines Created:**
      screenshot


## Configuration and Tools
### pfSense
- Setup with NAT to manage network traffic and two internal adapters for isolated network segments.
- Configured firewall rules and VPN for secure remote access.

### Windows Server 2022
- Installed and configured Active Directory to manage user accounts and security policies.
- Used Microsoft’s media creation tool to create installation support and ISO.

### Microsoft Workstation
- A separate virtual machine was set up using Microsoft Workstation ISO to simulate an end-user environment within the SOC. This workstation allowed for the deployment and testing of security policies and tools from the perspective of a regular user.

### Sysmon
- Installed on the Windows Server to enhance Windows event logs with detailed system monitoring data.
- Utilized an XML configuration file for Sysmon, focusing on capturing security-relevant events like process creations and network connections.

### CrowdSec
- Deployed as an additional security layer, utilizing behavior analysis to detect and mitigate threats.
- Integrated with pfSense for real-time security monitoring and response.

## Technical Details and Explanations
need to explain stuff to remember them as well

## Project Outcomes
This project provided practical experience in network security, system administration, and the use of advanced monitoring tools. It highlighted the implementation of pfSense as a versatile firewall solution, the management of a Windows Server environment with Active Directory, and the integration of security tools like Sysmon and CrowdSec to enhance network defense capabilities.

## Acknowledgments
Special thanks to the LetsDefend platform for providing the course materials that guided the setup and configuration processes, despite the original instructions being tailored for VirtualBox. The extra practice of configuring the environment in Hyper-V added valuable learning experiences.
