# ServerOS Configuration & Lab Submissions

Welcome to the **ServerOS** repository. This repository houses laboratory assignments, system configurations, and grading verification logs for server administration and networking coursework.

**Student ID:** 6705140029  
**Student Name:** Kyaw San  
**Repository Owner:** KyawSan  

---

## Repository Structure

```text
ServerOS/
├── dhcp/       # DHCP server configuration & assignment verification logs
└── lab1/       # Linux user management, permissions, & SSH service verification

Lab Summaries

1. Linux System Administration (/lab1)

Contains system audit logs and permission checks generated for Linux account management and SSH security baseline verification.

    User & Group Account Management: Verification of user (olga264) and group (research) permissions.

    File Permissions: Specific file mode checks (700) on /home/olga264/report_4032.txt.

    SSH Baseline Security: Audit logs for OpenSSH configuration settings and binary SHA-256 integrity hash (46a5c6e5...).

2. DHCP Server Configuration (/dhcp)

Contains the configuration files and verification records for the ISC DHCP Server (isc-dhcp-server).

    Network Scope: 192.168.160.0/24

    Subnet Router: 192.168.160.1

    DHCP Address Pool: 192.168.160.97 – 192.168.160.197

    Static Host Reservation: 192.168.160.204 assigned to MAC 52:54:00:52:47:c0

    Default Lease Duration: 21,600 seconds (6 hours)

    How to Validate Configurations

    To verify the DHCP server configuration syntax locally:

    dhcpd -t -cf /etc/dhcp/dhcpd.conf

