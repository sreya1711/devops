# 🚀 DevOps Hands-On Learning Repository

Welcome to my **DevOps learning journey**!  
This repository contains all exercises, commands, and screenshots from **Day 1 → Day 6**, showing step-by-step hands-on practice with Linux, Docker, Jenkins, AWS, Terraform, and Ansible.

---

## 📅 Day-wise Summary

### **🌱 Day 1: Linux Commands and Basics**
- Learned basic Linux commands for directories and files:
  - `pwd`, `ls`, `cd`, `mkdir`, `rmdir`
  - `touch`, `vim`, `cat`, `cp`, `mv`, `rm`
- Wildcards: `*.txt`, `file?.txt`
- Package management:
  - `sudo apt update`, `sudo apt upgrade -y`
- SSH basics:
  - `sudo apt install openssh-server`, `sudo systemctl start ssh`
- Other useful commands:
  - `chmod +x script.sh`, `ping`, `top`, `ip a`, `tail -f file.txt`
- ✅ Saved commands in `day1/day1.txt` and screenshots in `day1/screenshots/`

---

### **💻 Day 2: Linux Practice & Documentation**
- Practiced commands from Day 1 in real scenarios
- Created `day2.txt` with outputs
- Added **screenshots** for reference
- Learned to organize commands and document terminal work

---

### **🐳 Day 3: Docker & Nginx**
- Installed Docker:
  - `sudo apt install docker.io -y`
  - Started and enabled Docker service
- Ran Nginx container:
  - `sudo docker run -d -p 8080:80 nginx`
  - Checked running containers: `docker ps`
- Created a custom `index.html` and mounted it:
  - `-v ~/mynginx:/usr/share/nginx/html`
- Verified deployment in browser: `http://localhost:8081`
- ✅ Saved commands in `day3/day3.txt` and screenshots in `day3/screenshots/`

---

### **🛠 Day 4: Jenkins Installation & Build Triggers**
- Installed Jenkins:
  - Installed Java JDK: `sudo apt install openjdk-17-jdk -y`
  - Installed Jenkins via repository
  - Started and enabled Jenkins service
- Configured Freestyle Jenkins job:
  - Connected to GitHub repository
  - Added build step: `echo "Build Triggered Successfully"`
- Configured **GitHub webhook** for automatic builds
- Learned SCM triggers: Poll SCM vs GitHub hook
- ✅ Saved commands in `day4/day4.txt` and screenshots in `day4/screenshots/`

---

### **☁️ Day 5: AWS, EC2, IAM & Terraform**
- Created AWS account & IAM user for programmatic access
- Launched EC2 instances (Windows & Ubuntu)
- Connected to Ubuntu via SSH
- Installed Apache server and created custom webpage
- Installed AWS CLI and configured credentials
- Installed Terraform and created infrastructure as code
- Ran Terraform commands:
  - `terraform init`, `terraform plan`, `terraform apply`, `terraform destroy`
- ✅ Saved commands in `day5/day5.txt` and screenshots in `day5/screenshots/`

---

### **🔧 Day 6: Ansible on Ubuntu**
- Installed Ansible:
  ```bash
  sudo apt update
  sudo apt install ansible -y

---

🚀 Continuous Integration, Continuous Delivery, Continuous Improvement — DevOps is not just tools, it’s culture, speed ⚡, and reliability ✅

---
