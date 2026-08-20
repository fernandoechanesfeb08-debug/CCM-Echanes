# Laboratory Activity 1 — Mission 1: Welcome to the Cloud

**Name:** Fernando Echanes
**Username:** fechanes
**Course:** CCM101 – Cloud Computing

## Mission Overview

As a newly onboarded Junior Cloud Infrastructure Engineer Trainee at
CloudNova Technologies, this mission introduces the foundational skills
every cloud engineer needs: working inside a Linux environment,
documenting work professionally, and maintaining a version-controlled
portfolio on GitHub.

## Objectives

- Access a cloud-based Linux environment using KillerCoda.
- Explore and navigate the Linux operating system.
- Gather basic system information.
- Organize files and directories using Linux commands.
- Create and maintain a professional GitHub repository.
- Document technical work using Markdown.
- Demonstrate proper documentation practices used by cloud professionals.

## Activities Performed

1. Launched an Ubuntu 24.04 Linux Playground on KillerCoda.
2. Created a new user `fechanes` with Bash, a home directory, and sudo
   privileges, then logged into that account.
3. Recorded current username, working directory, and hostname.
4. Investigated the environment (distro, kernel, CPU, memory, disk space)
   and documented findings in `system-information.md`.
5. Built a workspace folder structure (`Documents`, `Notes`, `Reports`,
   `Screenshots`) inside the home directory and created `about-me.md`
   inside `Notes`.
6. Created the public GitHub repository `CCM101-fechanes` with the
   required folder structure.
7. Documented this mission in this `README.md`.
8. Captured and organized evidence screenshots.
9. Committed and pushed all work to GitHub.

## Linux Commands Used

| Command | Purpose |
|---|---|
| `sudo adduser fechanes` | Create the new user account |
| `sudo usermod -aG sudo fechanes` | Grant sudo privileges |
| `su - fechanes` | Log in to the new user account |
| `whoami` | Show current username |
| `pwd` | Show current working directory |
| `hostname` | Show system hostname |
| `cat /etc/os-release` | Show Linux distribution |
| `uname -r` | Show kernel version |
| `lscpu` | Show CPU information |
| `free -h` | Show total memory |
| `df -h` | Show available disk space |
| `mkdir` | Build workspace folders |
| `nano` | Create and edit markdown files |
| `ls`, `cat` | Verify and view created files |
| `mv`, `rm` | Rename/remove files and folders |

## Skills Learned

- Creating and managing Linux user accounts with sudo access.
- Navigating the Linux filesystem and gathering system diagnostics.
- Organizing a clean, professional folder structure.
- Writing technical documentation in Markdown.
- Structuring and maintaining a GitHub portfolio repository.
- Following a consistent commit-and-push workflow.
