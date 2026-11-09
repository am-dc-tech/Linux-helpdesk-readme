# 🐧 Linux Help Desk Quick Reference

Basic Linux commands for day-to-day help desk support.

---

## Navigation

| Command | Description |
|---|---|
| `pwd` | Show current directory |
| `ls -lh` | List files with details |
| `cd /path` | Change directory |
| `cd ..` | Go up one level |

---

## Files & Folders

| Command | Description |
|---|---|
| `cp file.txt /tmp/` | Copy a file |
| `mv old.txt new.txt` | Move or rename a file |
| `rm file.txt` | Delete a file |
| `mkdir foldername` | Create a folder |
| `find / -name "file.txt"` | Search for a file |

---

## Viewing Files

| Command | Description |
|---|---|
| `cat file.txt` | Print file contents |
| `tail -f /var/log/syslog` | Watch a log live |
| `grep "error" file.txt` | Search for text in a file |
| `less file.txt` | Scroll through a file |

---

## Users & Passwords

| Command | Description |
|---|---|
| `whoami` | Show current user |
| `sudo adduser jsmith` | Create a new user |
| `sudo passwd jsmith` | Reset a user's password |
| `sudo usermod -aG sudo jsmith` | Add user to sudo group |
| `id jsmith` | Show user info and groups |

---

## System Info

| Command | Description |
|---|---|
| `uname -a` | OS and kernel version |
| `uptime` | How long system has been running |
| `df -h` | Disk space usage |
| `free -h` | RAM usage |
| `hostname -I` | Show IP address |

---

## Processes

| Command | Description |
|---|---|
| `ps aux` | List running processes |
| `kill 1234` | Kill a process by PID |
| `pkill firefox` | Kill a process by name |

---

## Services (systemd)

| Command | Description |
|---|---|
| `systemctl status ssh` | Check service status |
| `sudo systemctl restart ssh` | Restart a service |
| `sudo systemctl start apache2` | Start a service |
| `sudo systemctl stop apache2` | Stop a service |

---

## Networking

| Command | Description |
|---|---|
| `ping google.com` | Test connectivity |
| `ip a` | Show network interfaces and IPs |
| `ssh user@192.168.1.10` | Connect to remote machine |

---

## Package Management

```bash
sudo apt update            # Refresh package list
sudo apt install <package> # Install a package
sudo apt remove <package>  # Remove a package
```

---

> 💡 **Tips:** Use `Tab` to autocomplete, `↑` to repeat last command, `man <command>` for help.
