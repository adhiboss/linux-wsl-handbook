# Linux Commands Cheat Sheet

## Navigation
- `pwd` → show current directory
- `ls` → list files
- `ls -la` → list all files with permissions
- `cd <dir>` → change directory
- `cd ..` → go back one level

## File and Folder Management
- `mkdir <name>` → create folder
- `touch <file>` → create empty file
- `cp <src> <dest>` → copy file
- `mv <src> <dest>` → move/rename file
- `rm <file>` → delete file
- `rm -r <folder>` → delete folder recursively

## Viewing Files
- `cat <file>` → print file content
- `less <file>` → view file scrollable
- `head <file>` → first 10 lines
- `tail <file>` → last 10 lines
- `tail -f <file>` → live log view

## Permissions
- `chmod +x file.sh` → make executable
- `chmod 644 file` → rw-r--r--
- `ls -l` → view permissions

## Process Management
- `ps aux` → list processes
- `top` → live process monitor
- `kill <pid>` → kill process
- `kill -9 <pid>` → force kill

## Networking
- `ping google.com` → check connectivity
- `curl <url>` → request URL
- `wget <url>` → download file
- `ip a` → show IP info
- `ss -tulnp` → show open ports and services

## Package Management (Ubuntu)
- `sudo apt update` → update package list
- `sudo apt upgrade` → upgrade packages
- `sudo apt install <pkg>` → install package
- `sudo apt remove <pkg>` → remove package

## Useful
- `history` → command history
- `clear` → clear terminal
- `man <cmd>` → manual page
- `which <cmd>` → command location
