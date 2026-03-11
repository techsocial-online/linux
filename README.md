# linux

# 🛣️ Linux Mastery Roadmap

A step-by-step guide from absolute basics to kernel internals and production system skills. Use this as your learning journal, reference, and public knowledge sharing for cloud/platform engineering and RHCSA preparation.

---

## 1️⃣ Basic Usage & Command-line Essentials

- Choosing and installing a Linux distro (Ubuntu, CentOS, Fedora, etc.)
- Dual boot & virtualization options
- Shell basics: Bash, Zsh
- Navigating directories (`ls`, `cd`, `pwd`, `tree`)
- File operations: create, copy, move, delete (`cp`, `mv`, `rm`, `mkdir`, `touch`)
- Viewing files (`cat`, `less`, `more`, `head`, `tail`)
- Editing files: nano/vim basics
- File searches (`find`, `locate`, `grep`)
- Pipes and redirection (`|`, `>`, `<`, `>>`, `tee`)
- Command history and shortcuts
- Getting help: `man`, `info`, `--help`

---

## 2️⃣ Filesystem & Permissions

- Linux filesystem layout (`/home`, `/etc`, `/var`, `/tmp`, `/bin`, `/usr`, `/opt`, `/srv`, `/proc`, `/sys`)
- Path navigation: absolute vs relative
- File types: regular, directory, symbolic links, device files
- File permissions: read/write/execute, octal and symbolic notation
- Ownership: users/groups, `chown`, `chgrp`
- Default permissions: umask
- ACLs (Access Control Lists)
- Links: hard vs soft (`ln`, `ln -s`)
- Disk space management (`df`, `du`, `ls -lS`)
- Mounting/unmounting filesystems

---

## 3️⃣ User, Group & Process Management

- Adding/removing users (`useradd`, `userdel`, `passwd`)
- Adding/removing groups (`groupadd`, `groupdel`)
- Modifying users/groups (`usermod`)
- Managing user profiles
- Sudo and privilege escalation
- Process concepts: PID, parent/child, job/foreground/background
- Listing processes (`ps`, `top`, `htop`, `pgrep`)
- Controlling processes (`kill`, `pkill`, `killall`, `nice`, `renice`)
- Job control (`jobs`, `bg`, `fg`, `disown`, `nohup`)
- Service control (`systemctl`, `service`, `init`, `chkconfig`)

---

## 4️⃣ Networking Fundamentals

- Interface management (`ip`, `ifconfig`, `nmcli`, `NetworkManager`)
- Viewing/setting IP addresses & routes
- Hostname configuration
- Common tools: `ping`, `traceroute`, `netstat`, `ss`, `curl`, `wget`, `dig`, `nslookup`
- Network diagnostics and troubleshooting (latency, DNS, MTU)
- Configuring static and dynamic IPs
- Firewall basics (`firewalld`, `iptables`)
- SSH basics and configuration
- SCP/SFTP usage for file transfer

---

## 5️⃣ Package Management & Software Installation

- Package manager basics: APT (Debian/Ubuntu), YUM/DNF/RPM (RHEL/Fedora/CentOS)
- Installing, upgrading, removing packages
- Viewing installed packages and package info
- Managing repositories and sources
- Building packages from source (make, gcc, tar)
- Handling dependencies & conflicts
- System update & maintenance (`apt update`, `yum update`)

---

## 6️⃣ Shell Scripting & Automation

- Shell scripting basics: shebang, variables, quoting
- Control structures: if, case, for, while loops
- Functions & error handling
- Exit codes and debugging
- Writing scripts for file and text automation
- Scheduling tasks: `cron`, `at`, `anacron`
- Useful tools: `grep`, `sed`, `awk`, `cut`, `sort`, `uniq`, `wc`
- Parsing command-line arguments
- Script best practices and security

---

## 7️⃣ System Services, Logging & Troubleshooting

- Boot process overview: BIOS/UEFI, GRUB, systemd
- Managing system services: enable, disable, status, restart
- systemd targets, units, timers
- Viewing and managing logs: `journalctl`, `/var/log/*`
- Log rotation and archival
- Diagnosing boot/init problems
- Common error messages and recovery
- Analyzing system state and resource usage
- Rescue and recovery modes

---

## 8️⃣ Security & Hardening

- User authentication and password policies
- SSH key management, port and configuration hardening
- Firewall configuration (`firewalld`, `iptables`, `ufw`)
- SELinux/AppArmor basics and context management
- File permissions, ownership, access control
- Regular updates, vulnerability patching
- Sudoers file configuration
- Detecting and handling security incidents
- Intrusion detection tools and basics

---

## 9️⃣ Storage & Filesystem Management

- Disk partitioning tools (`fdisk`, `gdisk`, `parted`)
- Formatting filesystems (`mkfs`, `mkswap`)
- Logical Volume Management (LVM): create/extend/reduce/backup
- Mounting/unmounting partitions and devices
- Swap management: add/remove swap
- RAID basics and management tools
- Checking and repairing filesystems (`fsck`, `tune2fs`)
- Disk quota management

---

## 🔟 Performance Monitoring & Optimization

- CPU, memory, disk, network monitoring (`top`, `htop`, `vmstat`, `iostat`, `sar`)
- Network IO monitoring (`iftop`, `iptraf`, `nethogs`)
- Process profiling, system bottlenecks
- Benchmarking tools and strategies
- Performance tuning: kernel/sysctl parameters
- Troubleshooting slowdowns and resource contention
- Log-based root cause analysis

---

## 1️⃣1️⃣ Kernel Internals & Advanced Debugging

- Kernel architecture: modules, monolithic vs microkernel
- Scheduling, process management, memory management, paging
- Kernel boot and loading
- System calls and their tracing (`strace`, `ltrace`)
- Kernel parameter tuning (`sysctl`)
- Kernel logs and debugging (`dmesg`)
- Kernel upgrades and custom builds
- Kernel crash recovery and analysis
- Performance profiling (`perf`, `systemtap`)

---

## 1️⃣2️⃣ Production Systems & Cloud Engineering

- Containers: Docker basics, images, volumes, networking
- Linux namespaces, cgroups, and their use in containers
- Configuration management tools (Ansible, Puppet, Chef)
- CI/CD pipelines in Linux (Jenkins, GitHub Actions)
- Prod troubleshooting and recovery
- High availability (HA) concepts, clustering
- Backup and disaster recovery methods
- Linux and cloud platforms (AWS, GCP, Azure): VM provisioning, networking, security

---

## 📝 How To Use This Roadmap
- Progress level-by-level or deep-dive into specific topics
- Expand each section with notes, commands, exercises, and practical scenarios
- Use this as your personal study journal and reference
- Share publicly to help others learn!

---

**Consistent hands-on practice is key. This roadmap will take you from basic commands to production-level Linux and cloud engineering mastery.**

Happy learning!
