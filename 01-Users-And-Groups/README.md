# User and Group Management Lab

## Overview
This lab demonstrates fundamental Ubuntu Linux user and group administration tasks commonly performed by system administrators and SOC analysts.

## Objectives
- Create new users
- Create security groups
- Add users to groups
- Verify group membership
- Practice Linux user administration

---

## Commands Used

### Create Users
```
 sudo adduser analyst1
 sudo adduser analyst2
```
### Verify User Creation
```
 cat /etc/passwd | grep analyst
```
### Create Group
```
 sudo groupadd soc_team
```
### Add Users to Group
```
 sudo usermod -aG soc_team analyst1
 sudo usermod -aG soc_team analyst2
```
### Verify Group Membership
```
 groups analyst1
 groups analyst2
```
---

## Screenshots
### User Creation Verification
- user-group-management-01.png

### Group Membership Verification
- user-group-management-02.png

---

## Skills Demonstrated
- Linux User Management
- Linux Group Management
- Access Control Concepts
- Ubuntu Administration
- Basic System Administration

---

