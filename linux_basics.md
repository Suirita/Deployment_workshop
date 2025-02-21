# 1️⃣ Introduction to Linux  

## What is Linux? 🐧

Linux is an open-source, Unix-like operating system that powers everything from servers and supercomputers to smartphones and embedded systems. It is known for its stability, security, and flexibility and is widely used in software development, networking, and cybersecurity.


🔹 Key Features of Linux

- Open-source : The source code is freely available, allowing anyone to modify and distribute it.
- Multi-user & Multi-tasking : Supports multiple users and processes running at the same time.
- Highly Secure : Features built-in permissions, firewalls, and encryption.
- Customizable : Comes in different distributions (distros) like Ubuntu, Fedora, Arch, and Debian.
- Lightweight & Efficient : Can run on old or minimal hardware, making it ideal for embedded systems.
- Command Line Interface (CLI) : Offers powerful control via terminal commands

## History and evolution  

- 1969 – Unix was created at AT&T Bell Labs.
- 1987 – Minix, a Unix-like OS, was developed for education.
- 1991 – Linus Torvalds built the Linux kernel and released it as open-source.
- 1992 – Linux adopted the GNU GPL, allowing free distribution.
- 1990s–2000s – Growth of Linux distributions (Debian, Red Hat, Ubuntu).
- Today – Linux powers servers, supercomputers, Android, cloud computing, and IoT.

## Why use Linux? (Open-source, security, customization, etc.)  

✅ Free & Open-source – No licensing costs
✅ Secure & Reliable – Less prone to viruses and malware
✅ Highly Customizable – Tailor it to your needs
✅ Performance & Speed – Used in high-performance computing
✅ Great for Developers – Supports multiple programming languages

## Linux distributions (Ubuntu, Debian, Fedora, Arch, etc.)  

🔹 Popular Linux Distros & Their Uses  

| **Distro**   | **Best For** | **Package Manager** |
|-------------|-------------|------------------|
| **Ubuntu** 🟠  | Beginners, general use | `apt` (Debian-based) |
| **Debian** 🔴  | Stability, servers | `apt` |
| **Fedora** 🔵  | Cutting-edge features, developers | `dnf` (Red Hat-based) |
| **Arch Linux** 🟢  | Advanced users, customization | `pacman` |
| **Linux Mint** 🌱  | Windows-like experience, ease of use | `apt` |
| **Kali Linux** 🏴  | Cybersecurity, penetration testing | `apt` |
| **CentOS / Rocky Linux** 🏢  | Enterprise, servers | `dnf` |
| **openSUSE** 🟣  | Developers, system admins | `zypper` |
| **Manjaro** 🌿  | Arch-based, beginner-friendly | `pacman` |

# 2️⃣ Setting Up Linux  

## Installing Linux (Live USB, dual boot, VM)  


You can install Linux in different ways depending on your needs:  

- **Live USB:** Run Linux without installation by booting from a USB drive.  
- **Dual Boot:** Install Linux alongside Windows/macOS for switching between OSes.  
- **Virtual Machine (VM):** Use software like VirtualBox or VMware to run Linux inside another OS.  

## 🔹 Navigating the Linux File System  

Linux organizes files in a hierarchical structure. Key directories include:  

- `/home/` – User files and personal directories  
- `/etc/` – System configuration files  
- `/bin/` – Essential system binaries (commands)  
- `/var/` – Logs and variable data  
- `/mnt/` – Mounted file systems (USB, drives)  
- `/root/` – Home directory for the root user  


## Understanding the Linux desktop environment (GNOME, KDE, XFCE, etc.)  

Linux offers multiple desktop environments (DEs), each with a unique look and feel:

- GNOME – Modern, minimal, used in Ubuntu & Fedora
- KDE Plasma – Highly customizable, Windows-like
- XFCE – Lightweight, good for older PCs
- LXQt – Ultra-lightweight, fast performance
- Cinnamon – Windows-like, used in Linux Mint

# 3️⃣ Essential Linux Commands (CLI Basics)  


Linux's **Command Line Interface (CLI)** is a powerful way to interact with your system. Here are some of the most commonly used commands:  

## 🔹 File Management  

- `ls` – List files in the current directory  
- `cd` – Change directory  
- `mkdir` – Create a new directory  
- `rm` – Remove files or directories  
- `cp` – Copy files or directories  
- `mv` – Move or rename files or directories  

## 🔹 Viewing Files  

- `cat` – Display the contents of a file  
- `less` – View file contents one page at a time  
- `head` – Show the first 10 lines of a file  
- `tail` – Show the last 10 lines of a file  

## 🔹 User Management  

- `whoami` – Show your current username  
- `id` – Display user and group information  
- `passwd` – Change your password  
- `adduser` – Add a new user  
- `deluser` – Remove a user  

## 🔹 Process Management  

- `ps` – List current processes  
- `kill` – Terminate a process by ID  
- `top` – Show running processes with resource usage  
- `htop` – An interactive process viewer (if installed)  

## 🔹 Networking Basics  

- `ping` – Test network connection to a server or IP  
- `ifconfig` – Display or configure network interfaces  
- `wget` – Download files from the internet  
- `curl` – Transfer data from or to a server  

## 🔹 Package Management  

- `apt` (Debian-based) – Install, update, and remove packages  
- `dnf` (Fedora/RHEL-based) – Package manager for Red Hat systems  
- `yum` (Older RHEL-based) – Package manager for Red Hat systems  
- `snap` – Install software packages via Snap Store  
- `flatpak` – Install software packages via Flatpak  
