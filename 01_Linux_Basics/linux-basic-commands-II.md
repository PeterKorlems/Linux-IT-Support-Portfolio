# Linux Basic Commands Lab II

## Objective
Learn and demonstrate essential Linux commands used daily in IT support roles.

## Commands Covered
- whoami
- id
- hostname
- uname -a
- df -h
- du -sh ~/linux_basics_lab
- uptime

## Lab Steps

## Command 12: whoami, id, hostname, uname

### Purpose
Identifies the current user, their permissions, and basic system information.

### Commands Used
```bash
whoami
id
hostname
uname -a
```

#### Explanation
The whoami command displays the username of the currently logged-in user.
The id command shows the user’s UID, GID, and group memberships, which are critical for understanding permissions.
The hostname command identifies the system name on the network.
The uname -a command provides detailed information about the system kernel and architecture.

#### IT Support Relevance
- Confirms the active user when troubleshooting permission issues
- Helps identify whether actions are being performed as the correct user
- Allows quick verification of system identity in multi-server environments
- Useful for diagnosing compatibility or kernel-related issues

## Command 13: df, du, uptime

### Purpose
Checks disk usage, directory size, and system uptime.

### Commands Used
```bash
df -h
du -sh ~/linux_basics_lab
uptime
```
#### Explanation
The df -h command displays available and used disk space on mounted filesystems in a human-readable format.
The du -sh command shows the total size of a specified directory.
The uptime command displays how long the system has been running along with current load averages.

#### IT Support Relevance
- Used to diagnose “disk full” or storage-related user issues
- Helps identify directories consuming excessive disk space
- Provides quick insight into system stability and performance
- Useful for determining whether a system reboot has occurred recently






  
