# Lab 01C — Install Ubuntu Server 24.04 LTS

## Objective

Install Ubuntu Server 24.04 LTS inside Oracle VirtualBox and prepare it for Linux administration labs.

## Environment

- Host OS: Windows 10 Home
- VirtualBox Version: Latest
- VM Name: NW-Ubuntu-Server
- RAM: 2048 MB
- CPU: 1 Processor
- Disk: 25 GB (VDI)

## Installation Choices

| Setting | Value |
|---------|-------|
| Language | English |
| Keyboard | English (US) |
| Installation | Ubuntu Server |
| Storage | Guided - Entire Disk |
| Server Name | nw-server01 |
| Username | femi |
| OpenSSH Server | Installed |

Confirmed the VM's memory and network settings before installation:

![VM memory allocation settings](../screenshots/ubuntu-memory-settings.PNG)

![VM network adapter settings](../screenshots/ubuntu-network-settings.PNG)

## Installation and First Login

After completing the installer, the system rebooted to the login prompt:

![Ubuntu Server login prompt after install](../screenshots/ubuntu-login.PNG)

Logged in successfully for the first time:

![First successful login to Ubuntu Server](../screenshots/ubuntu-first-login.PNG)

Confirmed the server hostname was set correctly:

![Setting the server hostname](../screenshots/ubuntu-hostname-ctl.PNG)

## First Commands Executed

```bash
whoami
hostname
pwd
ls
sudo apt update
sudo apt upgrade -y
```

Ran the update and upgrade to bring the system current:

![Running apt update and upgrade](../screenshots/ubuntu-apt-update.PNG)

Confirmed OpenSSH was installed and running, enabling future remote access:

![Confirming OpenSSH service is running](../screenshots/ubuntu-openssh-running.PNG)

## Results

Successfully installed Ubuntu Server and completed the first login.

## Skills Learned

- Linux installation
- Creating users
- Hostname configuration
- Command line login
- Updating packages
- Installing OpenSSH