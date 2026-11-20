# Linux Security Administration.                                                                                   
## Project Overview
This project documents my beginner practice in Linux security administration using Kali Linux.
## Skills Practiced
### 1. User Management
 * 'whoami' - identify the current Linux user
 * 'cat /etc/passwd'- View local user account information.
 * 'groups'- Display group membership
### 2. Files Permissions
 * 'chmod 640' - Set file permissions.
* 'ls -l' - view files permission and ownership.
### 3. File Ownership
* 'stat' -Inspect files ownership and detailed files information.
## practical Lab
Created a practice directory:
/root/Linux-security-lab
created a test file:
test.txt
changed its permission to:
640
## Tools Used
* Kali Linux
* Linux Terminal
* VitualBox
## Learning Outcome
I learning how Linux manages users, groups, file permissions, and file ownership.
**status:** Beginner practical exercise completed.
## service Management
- Used 'systemctl' to list running Linux services.
- checked the status of the cron services.
- Learned how Linux manages scheduled background tasks.
## Learning Outcome
Learned how to inspect running services and check their operational status.
#  Linux Log Analysis
**status:** completed(Beginner Practical Exercise)
**Focus:** system Administration, Troubleshooting, 'systemd' logging
## Overview
This exercise covers the fundamentals of querying and filtering Linux system logs using 'journalctl' to monitor system health and troubleshoot events.
## Practical Exercise & commands
| Command | Purpose |
| :--- | :--- |
| `journalctl -n 10` | view the 10 most recent system log entries. |
| `journalctl -p warning -n 10` | Filter and inspect the last 10 warning-level messages in a concise format without paging. |
| `journalctl -p err -n 5 --no-pager -o short` | Inspect the 5 most recent error-level messages in a concise format without paging. |
## Learning Outcome 
* **Log Navigation:** Gained hands-on experience querying `systemd` journals efficiently.
*  **Severity filtering:** Learned how to isolate specific priority levels (`warning`, `err`) to cut through routine noise.
*  **Output formatting:** Understood how to use flags like `--no-pager` and `-o short` for quick terminal readability and scripting.
## Evidence
The following screenshots document my practical exercises:
-'linux-error-log-analysis.png'
- `linux-user-management.png`
- `linux-file-permissions.png`
- `linux-user-group-management.png`
- `linux-file-ownership.png`
- `linux-account-security-checks.png`
- `linux-service-management.png`
- `linux-error-log-analysis.png`
## Additional Linux Security Exercises

### 1. System Information
- Used `cat /etc/os-release` to identify the Linux distribution.
- Used `uname -r` to check the Linux kernel version.

### 2. User and Group Management
- Created a group named `securityteam`.
- Created a user named `labuser`.
- Added `labuser` to `securityteam`.
- Verified group membership using `groups`.

### 3. Account Security Checks
- Used `id labuser` to inspect user identity and group information.
- Used `getent passwd labuser` to inspect account information.
- Used `passwd -S labuser` to check password status.

### Additional Learning Outcome
Practised Linux system identification, user and group administration, and basic account security verification.
