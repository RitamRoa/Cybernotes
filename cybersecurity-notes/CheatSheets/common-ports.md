# Common Ports

This document provides a quick reference for common ports and their associated services, organized by protocol.

## TCP Ports

- **Port 20**
  - **Service:** FTP Data Transfer
  - **Description:** Used for transferring files in FTP sessions.

- **Port 21**
  - **Service:** FTP Control
  - **Description:** Used for sending commands in FTP sessions.

- **Port 22**
  - **Service:** SSH
  - **Description:** Secure Shell for secure remote login and command execution.
  - **Tip:** Always use key-based authentication for enhanced security.

- **Port 25**
  - **Service:** SMTP
  - **Description:** Simple Mail Transfer Protocol for sending emails.

- **Port 80**
  - **Service:** HTTP
  - **Description:** Hypertext Transfer Protocol for web traffic.

- **Port 443**
  - **Service:** HTTPS
  - **Description:** Secure version of HTTP, used for secure web traffic.

## UDP Ports

- **Port 53**
  - **Service:** DNS
  - **Description:** Domain Name System for resolving domain names to IP addresses.

- **Port 67**
  - **Service:** DHCP Server
  - **Description:** Dynamic Host Configuration Protocol for assigning IP addresses.

- **Port 68**
  - **Service:** DHCP Client
  - **Description:** Used by clients to receive IP addresses from a DHCP server.

- **Port 123**
  - **Service:** NTP
  - **Description:** Network Time Protocol for synchronizing clocks over a network.

## Tips for Using Common Ports

- Always verify the service running on a port using tools like `nmap`.
- Be cautious when exposing services on common ports to the internet; consider using firewalls and VPNs for added security.
- Regularly update and patch services running on these ports to mitigate vulnerabilities.