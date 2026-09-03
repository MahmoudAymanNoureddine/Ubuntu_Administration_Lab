# File Permissions and Ownership Lab

## Overview
This lab demonstrates Linux file permission management and file ownership administration.

## Objectives
- Create files and directories
- View file permissions
- Modify permissions using chmod
- Change file ownership using chown
- Understand Linux access control

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
## Skills Demonstrated
- File Permissions
- Ownership Management
- Access Control
- Linux Security Fundamentals


