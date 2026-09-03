# Ubuntu Administration Lab

## Overview

Ubuntu Administration Lab is a hands-on Linux administration project designed to demonstrate essential Ubuntu system administration skills through practical laboratory exercises.

The project covers user management, file permissions, package administration, service management, networking, log analysis, firewall configuration, and system monitoring.

This lab provides practical experience commonly required for Linux Administrators, System Administrators, SOC Analysts, and Cybersecurity professionals.

---

## Project Objectives
- Manage users and groups
- Configure file permissions and ownership
- Install and manage software packages
- Monitor and manage system services
- Configure and troubleshoot networking
- Analyze Linux logs
- Configure firewall rules
- Monitor system resources

---

# Lab Structure

## Lab 01 - Users and Groups

### Description

This lab focuses on creating and managing user accounts and groups in Ubuntu Linux.

### Skills Demonstrated
- User Management
- Group Management
- User Verification
- Group Membership Administration

### Commands Used
```
adduser
groupadd
usermod
id
groups
```
---

## Lab 02 - File Permissions and Ownership

### Description
This lab demonstrates how to manage file permissions and ownership using standard Linux file permission mechanisms.

### Skills Demonstrated
- Permission Management
- File Ownership
- Access Control
- Linux Security Fundamentals

### Commands Used
```
chmod
chown
ls -l
touch
```
---

## Lab 03 - Package Management

### Description

This lab demonstrates software installation, updates, package searches, and package administration using the APT package manager.

### Skills Demonstrated
- Package Installation
- System Updates
- Package Administration
- Software Management

### Commands Used
```
apt update
apt upgrade
apt install
apt search
apt show
```
---

## Lab 04 - Service Management

### Description

This lab demonstrates managing and monitoring Linux services using systemd and systemctl.

### Skills Demonstrated
- Service Administration
- Service Monitoring
- Service Troubleshooting
- Systemd Management

### Commands Used
```
systemctl status
systemctl restart
systemctl is-enabled
systemctl --failed
```
---

## Lab 05 - Network Administration

### Description

This lab demonstrates network configuration verification, connectivity testing, routing analysis, and open port monitoring.

### Skills Demonstrated
- Network Administration
- IP Configuration Analysis
- Connectivity Testing
- Port Monitoring
- Network Troubleshooting

### Commands Used
```
ip a
hostname -I
ping
ip route
ss -tulnp
```
---

## Lab 06 - Log Management

### Description

This lab demonstrates how to analyze and monitor Ubuntu system logs for troubleshooting and security monitoring.

### Skills Demonstrated
- Log Analysis
- Security Monitoring
- Service Troubleshooting
- Authentication Log Review

### Commands Used
```
journalctl
journalctl -u ssh
tail
cat /var/log/auth.log
```
---

## Lab 07 - Firewall Management

### Description

This lab demonstrates Linux firewall administration using the UFW (Uncomplicated Firewall) utility.

### Skills Demonstrated
- Firewall Administration
- Port Management
- Access Control
- Host Security

### Commands Used
```
ufw status
ufw enable
ufw allow ssh
ufw allow 80/tcp
ufw status numbered
```
---

## Lab 08 - System Monitoring

### Description

This lab demonstrates monitoring CPU, memory, storage, and overall system health.

### Skills Demonstrated
- Performance Monitoring
- Resource Monitoring
- Capacity Management
- System Administration

### Commands Used
```
top
free -h
df -h
uptime
```
---

# Project Structure
Ubuntu_Administration_Lab

├── 01-Users-And-Groups
├── 02-File-Permissions
├── 03-Package-Management
├── 04-Service-Management
├── 05-Network-Administration
├── 06-Log-Management
├── 07-Firewall-Management
├── 08-System-Monitoring
├── screenshots
├── README.md
└── LICENSE

---

# Screenshots

Practical screenshots are included for each lab task and demonstrate the successful completion of all exercises.

See:
screenshots/

---

# Skills Demonstrated
- Ubuntu Linux Administration
- Linux Fundamentals
- User and Group Management
- Permission Management
- Package Management
- Service Administration
- Network Administration
- Log Analysis
- Firewall Configuration
- System Monitoring
- Linux Troubleshooting
- Security Administration

---

# Technologies Used
- Ubuntu Linux
- Systemd
- UFW Firewall
- APT Package Manager
- Linux Command Line

---

# Learning Outcomes

After completing this project, the following competencies were demonstrated:
- Managing Ubuntu Linux systems
- Configuring users and permissions
- Installing and maintaining software packages
- Managing Linux services
- Troubleshooting network issues
- Monitoring and analyzing logs
- Configuring firewall rules
- Monitoring system performance
- Applying Linux administration best practices

---

# Author

Mahmoud Ayman Noureddine

Cybersecurity Engineer | Linux Administrator | SOC & Blue Team 

---

# License
This project is licensed under the MIT License.
