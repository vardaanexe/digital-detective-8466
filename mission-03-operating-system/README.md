# Mission 3 – Operating System

## 1. Task / Objective
The objective of this mission is to understand the operating system, its responsibilities and basic system information using terminal commands.

## 2. Operating System Information

I use a Mac computer with macOS.

| Detail | Information |
|---|---|
| Operating System | macOS |
| macOS Version | 27.2.1 |
| Build Version | 26B131 |
| User Interface | Graphical User Interface (GUI) |
| Command Interface | Terminal (CLI) |

The system information was checked using the `sw_vers` command.

## 3. Current Account

I used the `whoami` command to check the current account name.

The command successfully displayed the logged-in account. Personal account information has been kept private.

## 4. Storage Information

I used the `df -h /` command to check disk storage.

| Detail | Result |
|---|---|
| Total Disk Size | 926 GiB |
| Used Space | 13 GiB |
| Available Space | 823 GiB |
| Capacity Used | 2% |

This command displays information about disk space and available storage.

## 5. Running Processes and PID

I used `ps aux | head -10` to view some running processes.

Examples from my system:

| Process | PID |
|---|---|
| Discord Helper Renderer | 1700 |
| cameracaptured | 736 |
| VS Code Helper Renderer | 2504 |
| WindowServer | 605 |
| coreaudiod | 740 |

PID stands for Process Identifier. It is a unique number assigned to a running process.

## 6. Absolute and Relative Paths

An absolute path gives the complete location of a file or folder.

Example:
`/Users/<username>/Desktop/digital-detective-8466`

A relative path describes a location from the current working directory.

Example:
`mission-03-operating-system/README.md`

I used the `pwd` command to check my current working directory.

## 7. File Permissions

I used the following command:

`ls -l mission-03-operating-system/README.md`

The output showed:

`-rw-r--r--`

Meaning:
- Read (r): Allows reading a file.
- Write (w): Allows modifying a file.
- Execute (x): Allows running a file.

The file owner has read and write permissions, while the group and others have read permission.

## 8. Responsibilities of an Operating System

1. Process Management – Manages running programs and processes.
2. Memory Management – Allocates memory to applications.
3. File Management – Organizes files and folders.
4. Device Management – Controls hardware devices.
5. Security – Protects files and user accounts.

## 9. My Understanding

I learned that an operating system acts as an interface between the user and computer hardware. It manages system resources, running processes, files and devices.

I also learned how to check system information, disk storage, running processes and file permissions using terminal commands.

## 10. Difficulties Faced

Understanding process IDs, file permissions and the difference between absolute and relative paths was challenging.

## 11. How I Resolved Them

I practised different terminal commands and observed their outputs on my Mac. This helped me understand how the operating system manages the computer.

## 12. Evidence / Files

- macOS system information checked using sw_vers.
- Storage information checked using df -h.
- Running processes checked using ps aux.
- File permissions checked using ls -l.
- This README file.

## 13. Commit Details

Commit message: Mission 3 - Operating system documentation