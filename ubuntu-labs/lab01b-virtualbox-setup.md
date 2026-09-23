# Lab 01B — Oracle VirtualBox Setup

## Objective

Install Oracle VirtualBox and create the first Ubuntu Server virtual machine for the Enterprise Home Lab.

## Software

* Oracle VirtualBox
* Windows 10 Home (Host)

## Virtual Machine Configuration

| Setting   | Value               |
| --------- | ------------------- |
| Name      | NW-Ubuntu-Server    |
| Type      | Linux               |
| Version   | Ubuntu (64-bit)     |
| Memory    | 2048 MB             |
| Processor | 1 CPU               |
| Storage   | 25 GB VDI (Dynamic) |
| Network   | NAT                 |

## Screenshots

VM created and visible in VirtualBox Manager:

![VirtualBox Manager showing NW-Ubuntu-Server VM](../screenshots/virtualbox-manager.PNG)

Memory allocation configured:

![VM memory allocation settings](../screenshots/ubuntu-memory-settings.PNG)

Network adapter set to NAT:

![VM network adapter settings](../screenshots/ubuntu-network-settings.PNG)

## Notes

This VM will be used for Linux administration, SSH, networking, logging, and Canonical practice labs.