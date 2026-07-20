# Linux Fundamentals

## Introduction

Linux is an open-source operating system commonly used in cybersecurity and server environments.

## File System Navigation

| Command | Description |
|----------|-------------|
| pwd | Show current directory |
| ls | List files and folders |
| cd | Change directory |

Examples:

```bash
pwd
ls
cd Documents
```

## File Permissions

Permission Types:

- r = Read
- w = Write
- x = Execute

Commands:

```bash
chmod 755 file.txt
chown user file.txt
```

## Package Management

Update Package List:

```bash
sudo apt update
```

Upgrade Packages:

```bash
sudo apt upgrade
```

Install Package:

```bash
sudo apt install nmap
```

## Networking Commands

```bash
ifconfig
ip addr
ping google.com
netstat -tulpn
traceroute google.com
```

## Conclusion

Linux skills are essential for system administration and penetration testing.
