# My DevOps Learning Journey at ALTSCHOOL AFRICA 🚀


## 📅 Week 1: Linux & Cloud Foundations

### ☁️ Cloud Basics
- Introduction to Cloud Computing
- Understanding cloud providers and services

### 🖥️ Operting Systems
- What is an Operating System
- Role of OS in managing hardware and software

### 🐧 Linux Fundamentals
- Introduction to Linux
- Setting up Linux OS (Vagrant/Ubuntu)

### 💻 Linux Shell
- Understanding the terminal
- Navigating the Linux environment

### 📂 Linux Commands
- Basic commands (`ls`, `cd`, `pwd`)
- File operations (`cp`, `mv`, `rm`, `mkdir`)
- Text editors (`nano`, `vim`)
- Seeking help (`man`, `--help`)

### 🛠️ Prctical Work
- Created and navigated directories
- Edited files using nano
- Installed packages using `apt`
- Managed files and folders

---
## 📅 Week 2: Linux Deep Dive 🔍

### 👥 Users & Groups
- Understanding users in Linux
- Creating users (`useradd`, `adduser`)
- Switching users (`su`, `sudo`)
- Understanding `/etc/passwd` and `/etc/shadow`

### 👨‍👩‍👧 Managing Groups
- Creating groups (`groupadd`)
- Adding users to groups (`usermod -aG`)
- Viewing groups (`groups`, `id`)
- Group-based access control

### 🔐 File Permissions
- Understanding permissions (`r`, `w`, `x`)
- File ownership (`chown`, `chgrp`)
- Changing permissions (`chmod`)
- Numeric permissions (e.g., `755`, `644`)

### 🔑 SSH (Secure Shell)
- Connecting to remote servers using SSH
- Generating SSH keys (`ssh-keygen`)
- Copying keys (`ssh-copy-id`)
- Password vs key-based authentication

### 🧪 Practical Work
- Created and managed multiple users
- Assigned users to groups
- Modified file permissions and ownership
- Connected to remote servers using SSH keys

### 📚 Further Study & Exercises
- Practiced user and group management scenarios
- Explored permission-based access control
- Strengthened command-line efficiency

## 📅 Week 3: Linux System Management ⚙️

### 🔄 Linux Process Management
- Understanding processes and PID
- Viewing processes (`ps`, `top`, `htop`)
- Managing processes (`kill`, `killall`, `pkill`)
- Background & foreground jobs (`&`, `jobs`, `fg`, `bg`)

### 📁 Linux File System & Storage
- Understanding Linux file system structure (`/`, `/home`, `/var`, `/etc`)
- Disk usage (`df -h`, `du -sh`)
- Virtual storage concepts
- Mounting and unmounting storage (`mount`, `umount`)

### 📦 Application Package Management
- Package managers (`apt`, `dpkg`)
- Installing, updating, removing packages
- Package index update (`apt update`)
- Upgrading system packages (`apt upgrade`)

### 📚 Further Study
- Explored package dependencies
- Understood difference between `apt` and `dpkg`
- Practiced troubleshooting package installation issues

### 🧪 Practical Work
- Monitored running processes
- Killed unwanted processes
- Checked disk usage and storage
- Installed and removed applications using `apt`

### 📝 Assessment 1
- Completed first assessment covering Linux fundamentals


## 📅 Week 4: Version Control & System Services 🔧

### 🧰 Version Control (Git)
- Introduction to Git and version control concepts
- Understanding distributed version control systems

### 🔄 Git Distribution, Commands & Workflow
- Initializing repositories (`git init`)
- Cloning repositories (`git clone`)
- Staging changes (`git add`)
- Committing changes (`git commit`)
- Pushing to remote (`git push`)
- Pulling updates (`git pull`)
- Basic workflow: working directory → staging → commit → remote

### 📖 Git Terms
- Repository (repo)
- Commit
- Branch
- Merge
- Clone
- Remote

### ⚙️ SystemD
- Understanding systemd as a service manager
- Managing services (`systemctl start/stop/restart/status`)
- Enabling and disabling services at boot

### 🌐 Configuring Apache Service
- Installing Apache (`apache2`)
- Managing Apache with systemctl
- Enabling Apache to start on boot
- Restarting and checking service status

### 🔐 CIS Security Benchmark
- Introduction to CIS benchmarks
- Importance of system hardening and security best practices
- Basic system security awareness

### 🔥 Linux Firewall
- Understanding firewall concepts
- Using `ufw` (Uncomplicated Firewall)
- Allowing and denying ports
- Enabling and checking firewall status

### 🧪 Practical Work
- Used Git for version control and pushed to GitHub
- Managed services using systemctl
- Installed and configured Apache server
- Enabled and configured firewall rules

### 🚀 Key Takeaways
- Learned how to track and manage code changes using Git
- Understood Linux service management with systemd
- Gained hands-on experience with web server configuration
- Improved system security awareness with firewall and benchmarks


# 🟦 Week 5: Bash Scripting & Crontab

## 📌 Overview

Learned how to automate tasks in Linux using Bash scripts and schedule them with cron.

---

## 🧠 Key Concepts

* Bash scripting basics
* Variables and user input
* Conditionals (`if`)
* Loops (`for`, `while`)
* Cron job scheduling


## 🚀 Outcome

Gained hands-on experience automating tasks and scheduling jobs in Linux.

---

# 🟦 Week 6: Configuration Management – Ansible

## 📌 Overview

Learned how to automate system configuration and deployment using Ansible.

---

## 🧠 Key Concepts

* Introduction to Ansible
* Agentless architecture (SSH-based)
* Inventory files
* Ad-hoc commands
* Playbooks and YAML syntax

---

## 🛠 Practice

* Ran Ansible ad-hoc commands
* Created simple playbooks
* Managed remote servers via SSH

---

## 📊 Assessment

* Completed **Assessment 2** on Ansible fundamentals and usage

---

## 🚀 Outcome

Gained hands-on experience in automating configuration and managing servers using Ansible.

---

# 🟦 Week 7: Internet, Protocols & OSI Model

## 📌 Overview

Learned how the internet works, how devices communicate using protocols, and how data flows through the OSI model.

---

## 🧠 Key Concepts

* Internet basics (DNS, IP, packets)
* Client–server communication
* Network protocols (HTTP, HTTPS, TCP, UDP)
* OSI 7-layer model

---

## 🌐 How the Internet Works

* Domain names are resolved to IP addresses using DNS
* Data is sent as packets across networks
* Servers process requests and return responses

---

## 🔌 Protocols

* **HTTP/HTTPS** – web communication
* **TCP** – reliable data transfer
* **UDP** – fast but unreliable
* **IP** – addressing and routing

---

## 🧱 OSI Model (7 Layers)

1. Application
2. Presentation
3. Session
4. Transport
5. Network
6. Data Link
7. Physical

---

## 🚀 Outcome

Gained a solid understanding of how internet communication works and how data moves across networks.

---


### MY PERSONAL PROJECT ON ANSIBLE-ROLE ###
# 🟦 Ansible Nginx Role-Based Web Server Setup

## 📌 Overview

This project demonstrates how to configure a web server using Ansible with an **industry-standard role-based structure**.

It installs Nginx, deploys a dynamic HTML page using Jinja2 templates, and manages services using handlers.

---

## 🧠 Features

* Role-based Ansible structure
* Automated Nginx installation and configuration
* Dynamic HTML deployment using templates
* Service management with handlers
* Reusable and scalable infrastructure setup

---

## 📂 Project Structure

```bash
ansible-project/
│
├── inventory.ini
├── playbook.yml
└── roles/
    └── webserver/
        ├── tasks/
        │   └── main.yml
        ├── handlers/
        │   └── main.yml
        ├── templates/
        │   └── index.j2
        ├── files/
        ├── vars/
        │   └── main.yml
        └── defaults/
            └── main.yml
```

---

## 🛠 Setup Instructions

### 1. Install Ansible

```bash
sudo apt update
sudo apt install ansible -y
```

---

### 2. Create Role Structure

```bash
ansible-galaxy init roles/webserver
```

---

### 3. Configure Default Variables

Edit:

```bash
roles/webserver/defaults/main.yml
```

```yaml
page_title: "My Ansible Server"
heading1: "🚀 Deployed with Ansible"
heading2: "Welcome to my server"
heading3: "Configured using Ansible roles"
```

---

### 4. Create HTML Template

Edit:

```bash
roles/webserver/templates/index.j2
```

```html
<!DOCTYPE html>
<html>
<head>
    <title>{{ page_title }}</title>
</head>
<body>
    <h1>{{ heading1 }}</h1>
    <h2>{{ heading2 }}</h2>
    <h3>{{ heading3 }}</h3>
</body>
</html>
```

---

### 5. Define Tasks

Edit:

```bash
roles/webserver/tasks/main.yml
```

```yaml
- name: Update apt cache
  apt:
    update_cache: yes

- name: Install nginx
  apt:
    name: nginx
    state: present

- name: Start nginx
  service:
    name: nginx
    state: started
    enabled: yes

- name: Deploy HTML template
  template:
    src: index.j2
    dest: /var/www/html/index.html
  notify: restart nginx
```

---

### 6. Configure Handlers

Edit:

```bash
roles/webserver/handlers/main.yml
```

```yaml
- name: restart nginx
  service:
    name: nginx
    state: restarted
```

---

### 7. Create Main Playbook

```bash
nano playbook.yml
```

```yaml
- name: Configure Web Server
  hosts: web
  become: yes

  roles:
    - webserver
```

---

### 8. Configure Inventory

```ini
#[web]
your-server-ip ansible_user=root ansible_ssh_private_key_file=~/.ssh/id_rsa
```

---

### 9. Run the Playbook

```bash
ansible-playbook -i inventory.ini playbook.yml
```

---

## 🌐 Result

After execution, open:

```
http://my-server-ip
```

You should see a dynamically generated web page deployed via Ansible.

---

## 🎯 What This Project Demonstrates

* Infrastructure as Code (IaC) using Ansible
* Role-based configuration management
* Template-driven deployments
* Service automation and orchestration

---

## 🔥 These are the Future Improvements i will be making

* Add firewall configuration (UFW role)
* Support multiple environments (dev/prod)
* Integrate CI/CD pipeline
* Add monitoring and logging

---

## 🚀 My One-Line Summary

> This project uses Ansible roles to automate Nginx installation and deploy a dynamic web page in a clean, reusable DevOps structure.

---

