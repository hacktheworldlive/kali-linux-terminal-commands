# kali-linux-commands

# Kali Linux Terminal Commands

## Basic File and Directory Management
- `ls -la` — List all files, including hidden ones, with detailed information.
- `cd /path/to/directory` — Change to a specific directory.
- `pwd` — Print the current working directory.
- `mkdir directory_name` — Create a new directory.
- `rm filename` — Remove a file.
- `rm -r directory_name` — Remove a directory and its contents.
- `cp source destination` — Copy files or directories.
- `mv old_name new_name` — Move or rename a file or directory.
- `touch filename` — Create an empty file.

## System Information and Management
- `uname -a` — Display system information.
- `df -h` — Show disk usage in human-readable format.
- `free -m` — Display memory usage in megabytes.
- `ps aux` — List all running processes.
- `top` — Display real-time system stats (CPU, RAM, etc.).
- `htop` — Enhanced version of top (requires installation).
- `whoami` — Display the current username.

## Networking Commands
- `ifconfig` — Display network configuration.
- `iwconfig` — Show wireless network interface information.
- `ping 8.8.8.8` — Test connectivity by sending ICMP echo requests.
- `traceroute google.com` — Trace the route packets take to a network host.
- `netstat -tuln` — Show active network connections and listening ports.
- `nmap -sP 192.168.1.0/24` — Scan a network for active devices.
- `tcpdump -i eth0` — Capture network traffic on the eth0 interface.

## Package Management
- `apt-get update` — Update package lists.
- `apt-get upgrade` — Upgrade all packages to the latest version.
- `apt-get install package_name` — Install a specific package.
- `apt-get remove package_name` — Remove a specific package.
- `dpkg -i package.deb` — Install a .deb package.

## User Management
- `adduser username` — Add a new user.
- `passwd username` — Change the password for a user.
- `usermod -aG sudo username` — Add a user to the sudo group.
- `deluser username` — Delete a user.

## Disk Management
- `fdisk -l` — List all disk partitions.
- `mkfs.ext4 /dev/sda1` — Format a partition with the ext4 filesystem.
- `mount /dev/sda1 /mnt` — Mount a partition to a directory.
- `umount /mnt` — Unmount a partition.

## Service Management
- `systemctl start service_name` — Start a service.
- `systemctl stop service_name` — Stop a service.
- `systemctl restart service_name` — Restart a service.
- `systemctl status service_name` — Check the status of a service.

## Security Tools (Kali-Specific)
- `airmon-ng start wlan0` — Enable monitor mode on a wireless interface.
- `aircrack-ng -b BSSID -w wordlist.txt capture_file.cap` — Crack Wi-Fi password using a wordlist.
- `nmap -A target_ip` — Perform a detailed scan on a target.
- `sqlmap -u "http://example.com/vulnerable.php?id=1" --dbs` — Detect SQL injection vulnerabilities.
- `msfconsole` — Start Metasploit Framework console.

## Miscellaneous Commands
- `echo "text" > file.txt` — Write text to a file.
- `cat file.txt` — Display the contents of a file.
- `grep "search_term" file.txt` — Search for a term in a file.
- `find / -name filename` — Search for a file by name.
- `history` — Display the command history.
- `clear` — Clear the terminal screen.
