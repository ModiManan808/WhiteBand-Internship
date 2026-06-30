# Linux Task 02: Users, Groups & File Permissions

## Objective
The objective of this task is to understand Linux user management, group administration, file ownership, and permission mechanisms. The task also explores Linux security concepts such as the Principle of Least Privilege.

## Topics Covered

### Part A: Understanding Users
- Identified the current user.
- Explored UID and GID.
- Examined the `/etc/passwd` file.

### Part B: Users & Groups
- Created groups:
  - interns
  - cyberteam
- Created users:
  - student1
  - student2
  - student3
- Added users to appropriate groups.

### Part C: File Ownership
- Created project directory:
  - `CyberSecurity_Project`
- Created files:
  - `report.txt`
  - `notes.txt`
  - `credentials.txt`
- Changed ownership using `chown`.

### Part D: File Permissions
Modified file permissions using:
```bash
chmod 444 security_policy.txt
chmod 664 security_policy.txt
chmod 777 security_policy.txt
