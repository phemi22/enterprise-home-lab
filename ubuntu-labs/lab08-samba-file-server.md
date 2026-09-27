# Lab 08 — Samba File Server

## Objective

Configure Ubuntu Server as a Windows-compatible file server using Samba.

## Commands Practiced

```bash
sudo apt install samba -y

sudo mkdir -p /srv/samba/Finance
sudo mkdir -p /srv/samba/HR
sudo mkdir -p /srv/samba/Engineering
sudo mkdir -p /srv/samba/IT

sudo chown
sudo chmod

sudo nano /etc/samba/smb.conf

sudo smbpasswd -a username
sudo smbpasswd -e username

sudo systemctl restart smbd
sudo systemctl restart nmbd

sudo ufw allow Samba

hostname -I

testparm
```

## Skills Learned

* Installing Samba.
* Creating SMB shares.
* Configuring smb.conf.
* Creating Samba users.
* Restarting Samba services.
* Testing Windows network shares.
* Troubleshooting Samba configuration.

## Screenshots

* Samba installation.
* Samba configuration.
* Samba service running.
* Windows network connection.
* Finance share.
