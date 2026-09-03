# Firewall Management Lab

## Overview
This lab demonstrates firewall administration and network access control in Ubuntu Linux using the UFW (Uncomplicated Firewall) utility.

The lab covers firewall status verification, rule creation, port management, and access control configuration.

---

## Objectives
- Check firewall status
- Enable firewall protection
- Configure firewall rules
- Allow secure network services
- Manage open ports
- Practice Ubuntu security administration

---

## Lab Tasks

### Task 1: Check Firewall Status

#### Command
```
 sudo ufw status
```
#### Purpose
Displays the current firewall status and active rules.

---

### Task 2: Enable Firewall

#### Command
```
 sudo ufw enable
```
#### Purpose
Enables firewall protection.

---

### Task 3: Allow SSH Connections

#### Command
```
 sudo ufw allow ssh
```
#### Purpose
Allows SSH remote access through the firewall.

---

### Task 4: Display Firewall Rules

#### Command
```
 sudo ufw status numbered
```
#### Purpose
Displays configured firewall rules with numbering.

---

### Task 5: Allow HTTP Traffic

#### Command
```
 sudo ufw allow 80/tcp
```
#### Purpose
Allows inbound HTTP traffic on TCP port 80.

---

## Skills Demonstrated
- Firewall Administration
- Access Control
- UFW Management
- Port Management
- Security Hardening
- Network Security
- Ubuntu System Administration

---

## Commands Used
```
 sudo ufw status
 sudo ufw enable
 sudo ufw allow ssh
 sudo ufw status numbered
 sudo ufw allow 80/tcp
```
---

## Screenshots

### Firewall Status
- firewall-management-01.png

### Enable Firewall
- firewall-management-02.png

### Allow SSH
- firewall-management-03.png

### Firewall Rules
- firewall-management-04.png

### Allow HTTP Traffic
- firewall-management-05.png

---

## Learning Outcomes

After completing this lab, the following skills were demonstrated:
- Configuring UFW firewall
- Managing network access
- Creating firewall rules
- Allowing required services
- Managing open ports
- Performing Ubuntu security administration tasks
