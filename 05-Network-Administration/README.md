
# Network Administration Lab

## Overview
This lab demonstrates fundamental network administration and troubleshooting tasks in Ubuntu Linux.

The lab covers network interface inspection, IP address verification, connectivity testing, routing table analysis, and open port identification.

---

## Objectives
- Display network interfaces
- Verify IP address configuration
- Test network connectivity
- Examine routing tables
- Identify listening ports and services
- Practice basic network troubleshooting

---

## Lab Tasks

### Task 1: Display Network Interfaces

#### Command
```
 ip a
```
#### Description
Displays all available network interfaces and their configuration, including IP addresses and interface status.

---

### Task 2: Verify IP Address

#### Command
```
 hostname -I
```
#### Description
Displays the IPv4 addresses assigned to the system.

---

### Task 3: Test Network Connectivity

#### Command
```
 ping -c 4 8.8.8.8
```
#### Description
Sends ICMP echo requests to Google's public DNS server to verify internet connectivity.

---

### Task 4: Display Routing Table

#### Command
```
 ip route
```
#### Description
Displays the system routing table and default gateway configuration.

---

### Task 5: Display Open Ports and Services

#### Command
```
 sudo ss -tulnp
```
#### Description
Lists open TCP and UDP ports along with associated services and process information.

---

## Skills Demonstrated
- Network Interface Management
- IP Address Verification
- Connectivity Testing
- Routing Table Analysis
- Port Monitoring
- Service Inspection
- Linux Network Troubleshooting
- Ubuntu Network Administration

---

## Commands Used
```
 ip a
 hostname -I
 ping -c 4 8.8.8.8
 ip route
 sudo ss -tulnp
```
---

## Screenshots

### Network Interface Information
- network-administration-01.png

### IP Address Verification
- network-administration-02.png

### Connectivity Test
- network-administration-03.png

### Routing Table Analysis
- network-administration-04.png

### Open Ports and Services
- network-administration-05.png

---

## Learning Outcomes
After completing this lab, the following skills were demonstrated:
- Inspecting network interfaces
- Verifying network configuration
- Testing internet connectivity
- Understanding routing tables
- Monitoring listening network ports
- Performing basic Ubuntu network administration tasks
