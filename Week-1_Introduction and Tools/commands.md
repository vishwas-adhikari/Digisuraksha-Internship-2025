# 🐧 Commonly Used Linux Commands

Welcome! This document is a curated collection of frequently used **Linux terminal commands** that are essential for working with linux and command shell . These commands help with navigating directories, managing files, inspecting system performance, networking, and more.

> 📌 **Note:** Most of these commands are universal, but a few are specific to Debian-based distributions like Ubuntu.

---

##  File & Directory Management

Basic file and folder operations to interact with the filesystem.

| Command | Description |
|--------|-------------|
| `ls` | Lists files and directories in the current location. |
| `ls -l` | Lists in long format with details like permissions, owner, size, and date. |
| `ls -a` | Includes hidden files (those starting with a dot). |
| `pwd` | Prints the full path of the current working directory. |
| `cd <dir>` | Changes to the specified directory. |
| `cd ..` | Moves up one level in the directory structure. |
| `mkdir <dir>` | Creates a new directory. |
| `rmdir <dir>` | Removes an empty directory. |
| `rm -r <dir>` | Recursively deletes a directory and its contents. |
| `touch <file>` | Creates a new empty file (or updates timestamp if it exists). |
| `cp <src> <dest>` | Copies files or directories from source to destination. |
| `mv <src> <dest>` | Moves or renames files or directories. |
| `rm <file>` | Deletes a file. |

---

##  File Viewing & Editing

Read or modify files directly from the terminal.

| Command | Description |
|--------|-------------|
| `cat <file>` | Displays contents of a file in one go. |
| `less <file>` | Opens file in a scrollable view (press `q` to quit). |
| `more <file>` | Similar to `less`, but scrolls one screen at a time. |
| `head <file>` | Shows the first 10 lines of the file. |
| `tail <file>` | Shows the last 10 lines of the file. |
| `nano <file>` | Opens file in Nano text editor (easy to use). |
| `vim <file>` | Opens file in Vim editor (powerful but steeper learning curve). |
| `echo "text"` | Outputs text to the terminal or a file. |

---

## Searching & Finding Files

Locate files or search for content within them.

| Command | Description |
|--------|-------------|
| `find <dir> -name <file>` | Searches for a file within a directory tree. |
| `grep "<text>" <file>` | Searches for a string inside a file. |
| `grep -r "<text>" <dir>` | Recursively searches text in all files under a directory. |
| `locate <file>` | Quickly finds files (requires updated `locate` database). |
| `which <command>` | Shows the full path of an executable command. |

---

##  Package Management (Debian-based Systems)

Install, update, and remove software packages.

| Command | Description |
|--------|-------------|
| `sudo apt update` | Updates the local package index. |
| `sudo apt upgrade` | Upgrades all installed packages to the latest versions. |
| `sudo apt install <pkg>` | Installs a new package. |
| `sudo apt remove <pkg>` | Removes an installed package. |
| `dpkg -i <pkg.deb>` | Installs a `.deb` package manually. |

---

##  System Information & Monitoring

Monitor performance and system health.

| Command | Description |
|--------|-------------|
| `top` | Displays real-time process usage and resource consumption. |
| `htop` | Enhanced version of `top` (requires installation). |
| `free -h` | Displays memory usage in a human-readable format. |
| `df -h` | Shows disk space usage by mounted filesystems. |
| `uname -a` | Displays system architecture, kernel version, etc. |
| `uptime` | Shows how long the system has been running. |
| `whoami` | Displays the current logged-in user. |
| `id` | Shows user ID and group ID information. |
| `ps aux` | Lists all currently running processes. |

---

## Permissions & Ownership

Manage access rights for files and directories.

| Command | Description |
|--------|-------------|
| `chmod <perm> <file>` | Changes permission (e.g., `chmod 755 file.sh`). |
| `chown <user>:<group> <file>` | Changes ownership of a file or directory. |
| `ls -l` | Displays permissions, ownership, and more in long listing format. |

---

## Networking & Internet

Commands related to connectivity and networking.

| Command | Description |
|--------|-------------|
| `ping <host>` | Tests network connection to a server. |
| `curl <url>` | Transfers data from or to a server (fetch API/data). |
| `wget <url>` | Downloads files from the internet. |
| `ifconfig` | Displays IP address and network interfaces (older systems). |
| `ip a` | Shows IP addresses and interfaces (recommended modern alternative). |
| `netstat -tuln` | Shows listening ports and services. |
| `ss -tuln` | Faster alternative to `netstat`. |

---

## Archiving & Compression

Compress or extract files and directories.

| Command | Description |
|--------|-------------|
| `tar -cvf file.tar dir/` | Creates a tar archive from a directory. |
| `tar -xvf file.tar` | Extracts contents from a tar archive. |
| `gzip <file>` | Compresses a file using GZIP. |
| `gunzip <file.gz>` | Decompresses a `.gz` file. |
| `zip file.zip file1 file2` | Compresses multiple files into a `.zip`. |
| `unzip file.zip` | Extracts files from a `.zip` archive. |

---

## Other helpful commands 

Other helpful commands used frequently in scripts and terminals.

| Command | Description |
|--------|-------------|
| `history` | Shows a list of previously used commands. |
| `alias ll='ls -l'` | Creates an alias for a command. |
| `clear` | Clears the terminal screen. |
| `reboot` | Reboots the system. |
| `shutdown now` | Immediately shuts down the system. |
| `man <command>` | Opens the manual page for a command. |
| `exit` | Exits the current terminal session. |

---


