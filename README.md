Windows IT Support & Troubleshooting Lab

Author: Ayodeji Ojo
Project Area: IT Support | Desktop Support | Systems Administration
Focus: Tier 1–2 Enterprise IT Support

1. Project Overview

This project documents practical Windows IT support exercises, enterprise troubleshooting procedures, incident management workflows, and basic PowerShell administration.

The objective is to demonstrate structured troubleshooting, technical documentation, incident resolution, and end-user support capabilities.

2. Technical Skills Demonstrated

Windows 10/11 troubleshooting

Hardware and software diagnostics

Microsoft 365 troubleshooting

Network connectivity diagnostics

DNS and DHCP troubleshooting

User account and access troubleshooting

IT incident documentation

Service Desk and ITSM processes

PowerShell fundamentals

Root Cause Analysis (RCA)

3. Lab Environment

Component

Environment

Operating System

Windows 11

Shell

Windows PowerShell

Network

Simulated LAN

Support Level

Tier 1–2

Documentation

Markdown

ITSM Methodology

Incident, Problem and Change Management

4. Practical Troubleshooting Scenarios

Scenario 1: User Cannot Connect to the Internet

Symptoms: User reports no internet connectivity.

Troubleshooting procedure:

Verify physical or wireless connectivity.

Check IP configuration using ipconfig /all.

Test the default gateway using ping.

Test external connectivity.

Check DNS resolution using nslookup.

Document findings and resolution.

Commands:

ipconfig /all
ping 8.8.8.8
nslookup microsoft.com

Scenario 2: DNS Resolution Failure

Symptoms: User can connect to the network but cannot access websites using domain names.

Troubleshooting commands:

ipconfig /flushdns
nslookup microsoft.com

Objective: Identify DNS resolution issues and document corrective actions.

Scenario 3: Slow Windows Computer

Symptoms: Computer experiences slow startup and application performance.

Troubleshooting procedure:

Review Task Manager performance.

Check CPU, memory and disk utilization.

Review startup applications.

Check available disk space.

Review Windows Event Viewer.

Document findings.

Scenario 4: Microsoft 365 Sign-in Problems

Symptoms: User cannot sign in to Microsoft 365 applications.

Troubleshooting procedure:

Verify internet connectivity.

Confirm account and sign-in details.

Check service availability.

Review authentication and MFA issues.

Escalate suspected account or tenant-level issues.

Scenario 5: Windows System File Integrity

Objective: Demonstrate basic Windows system file diagnostics.

Commands:

sfc /scannow
DISM /Online /Cleanup-Image /RestoreHealth

Run these commands in an elevated PowerShell or Command Prompt session where appropriate.

5. PowerShell Exercises

Planned exercises:

Retrieve computer system information.

Identify operating system details.

Retrieve IP configuration.

List running services.

Generate basic system inventory reports.

6. Incident Documentation Example

Field

Example

Incident ID

INC-001

Priority

P3 - Medium

Category

Network

Issue

Internet connectivity failure

Impact

Single user

Diagnosis

DNS resolution failure

Resolution

DNS configuration investigated and corrected

Status

Resolved (simulated scenario)

7. Learning Outcomes

This project demonstrates:

Structured technical troubleshooting.

Incident lifecycle documentation.

Enterprise IT support methodology.

Windows administration fundamentals.

Basic PowerShell capabilities.

Root Cause Analysis and escalation practices.

8. Disclaimer

All scenarios and incident records in this repository are educational simulations. No confidential employer, customer, or organizational information is included.

Author: Ayodeji Ojo
GitHub: https://github.com/methodsereunclutched-source
