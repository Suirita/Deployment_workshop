## **Development in Linux**

### _A Practical Workshop for First-Year Students_

- Presented by:
  - SUIRITA Fahd
  - CHABBEH Aymen
  - Ayouby Amazu
- Framed by:
  - ESSARRAJ Fouad

---

### **Workshop Agenda**

1. Linux Basics (45 min)
2. Nginx Installation (45 min)
3. Virtual Machine Installation (45 min)
4. Q&A Session (15 min)

---

## Linux Basics

### **1. Introduction to Linux:**

- What is Linux?
- History and Importance
- Linux vs. Windows vs. macOS

---

## Linux Basics

### **2. Linux Distributions:**

- Popular distros: Ubuntu, Debian, Fedora, Arch
- Choosing the right distro for development

---

## Linux Basics

### **3. Basic Linux Commands:**

- Navigation: ls, cd, pwd
- File operations: cp, mv, rm, touch
- Permissions: chmod, chown

---

## Linux Basics

### **4. Package Management:**

- Debian-based (Ubuntu/Debian): apt-get
- Red Hat-based (Fedora/CentOS): dnf or yum
- Arch Linux: pacman

---

## Linux Basics

### **5. User & Group Management:**

- Adding users: adduser [username]
- Switching users: su [username]
- Granting privileges: sudo

---

## Linux Basics

### **6. Process Management:**

- Listing processes: ps, top, htop
- Killing processes: kill, killall
- Running in background: nohup, &, screen

---

## Nginx Installation

### **1. What is Nginx?**

- Web server vs. application server
- Nginx vs. Apache

---

## Nginx Installation

### **2. Installing Nginx:**

- Update package list: sudo apt update
- Install Nginx: sudo apt install nginx
- Start service: sudo systemctl start nginx

---

## Nginx Installation

### **3. Configuring Nginx:**

- Default config file location: /etc/nginx/nginx.conf
- Hosting a static site
- Virtual hosts

---

## Nginx Installation

### **4. Securing Nginx:**

- UFW firewall rules: sudo ufw allow 'Nginx Full'
- Enabling SSL with Let's Encrypt

---

## Nginx Installation

### **5. Testing & Troubleshooting:**

- Check service status: systemctl status nginx
- View logs: tail -f /var/log/nginx/error.log

---

## Virtual Machine Installation

### **1. What is a Virtual Machine?**

- Definition & Benefits
- Popular VM tools: VirtualBox, VMware, KVM

---

## Virtual Machine Installation

### **2. Installing VirtualBox:**

- Download & Install from virtualbox.org
- Install necessary extensions

---

## Virtual Machine Installation

### **3. Creating a Virtual Machine:**

- Choosing OS (Ubuntu, Debian, etc.)
- Allocating resources (RAM, CPU, Storage)
- Setting up networking

---

## Virtual Machine Installation

### **4. Installing Linux on VM:**

- Mounting ISO file
- Running installation wizard
- First boot and configuration

---

## Summary & Q&A

- Recap of Linux basics
- Installing & configuring Nginx
- Setting up a virtual machine
- Open floor for questions
