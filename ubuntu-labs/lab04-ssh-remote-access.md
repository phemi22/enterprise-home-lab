# Lab 04 - SSH Remote Access to Ubuntu Server

## Objective

Configure and test SSH remote access from Windows PowerShell to Ubuntu Server running in VirtualBox.

## Commands Practiced

- hostname -I
- systemctl status ssh
- systemctl enable ssh
- systemctl restart ssh
- ss -tln
- hostnamectl
- whoami
- who
- uptime
- exit

## Windows Command

ssh -p 2222 femi@127.0.0.1

## Port Forwarding

## Setting         Value

Protocol        TCP

Host Port       2222

Guest Port      22

## Skills Learned

- Finding Linux IP addresses.
- Verifying SSH service.
- Connecting remotely from Windows.
- Restarting Linux services.
- Understanding SSH port forwarding.

## Screenshots

- Ubuntu IP address.
- SSH service running.
- Windows SSH connection.
- Hostname information.