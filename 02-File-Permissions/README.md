# File Permissions and Ownership Lab

## Overview
This lab demonstrates Linux file permission management and file ownership administration using Ubuntu Linux.

## Objectives
- Create files and directories
- View file permissions
- Modify permissions using chmod
- Change file ownership using chown
- Understand Linux access control concepts

---

## Commands Used

### Create Files
```
 mkdir ~/permissions_lab
 cd ~/permissions_lab
 touch report.txt
 touch security.log
```
### View Permissions
```
 ls -l
```
### Change Permissions
```
 chmod 600 report.txt
 chmod 644 security.log
```
### Change Ownership
```
 sudo chown analyst1 report.txt
```
---

## Screenshots

### Initial File Creation and Permissions
- file-permissions-01.png | 
Displays the files created and their default permissions.

### Modified Permissions Using chmod
- file-permissions-02.png | 
Shows the updated permissions after applying chmod commands.

### Changed File Ownership Using chown
- file-permissions-03.png | 
Demonstrates changing file ownership and verifying the new owner.

---

## Skills Demonstrated
- File Creation
- File Permissions Management
- Ownership Management
- chmod Usage
- chown Usage
- Linux Access Control
- Ubuntu Administration Fundamentals

---
