# Lab 01 - Users and Groups

## Objective
Learn how to manage users and groups in Ubuntu Linux.

## Tasks

### Create a User
```
 sudo adduser analyst
```
### Verify User Information
```
 id analyst
```

### Create a Group
```
 sudo groupadd soc_team
```

### Add User to Group
```
 sudo usermod -aG soc_team analyst
```

### Verify Group Membership
```
 groups analyst
```

## Skills Demonstrated
- User Management
- Group Management
- User Verification
- Group Membership Administration

## Screenshot
See:
screenshots/user-group-management.png
