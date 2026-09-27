# Lab 07 — Ubuntu Package Management

## Objective

Learn how to install, update, remove, and troubleshoot software packages on Ubuntu Server.

## Commands Practiced

```bash
sudo apt update
sudo apt upgrade -y

sudo apt install tree -y
tree ~/Northwind

apt search nginx
apt show tree

apt list --installed
apt list --installed | grep tree

sudo apt remove tree -y
sudo apt install tree -y

sudo apt autoremove -y
sudo apt clean

grep "install tree" /var/log/dpkg.log

curl --version
sudo apt --fix-broken install
```

## Skills Learned

* Refresh package repositories.
* Install software.
* Upgrade installed packages.
* Search repositories.
* View package information.
* Remove software safely.
* Clean unused packages.
* Repair broken package installations.

## Screenshots

* Package update.
* Package upgrade.
* Installing tree.
* Tree command output.
* Installed package list.
