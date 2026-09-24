## Ticket 004 — User Cannot Connect to Linux Server Using SSH

**Priority:** P2 (High)

**Issue:** User could not connect to the Ubuntu server remotely using SSH.

**First Checks**

* Verified the SSH service status using `systemctl status ssh`.
* Verified the server IP address using `hostname -I`.
* Checked whether SSH was listening on port 22 using `ss -tln`.
* Verified VirtualBox NAT port forwarding configuration.

**Action Taken**

* Started and enabled the SSH service.
* Configured NAT port forwarding (Host Port 2222 → Guest Port 22).
* Connected successfully using Windows PowerShell.

**Status:** Resolved.

**Resolution:** User successfully connected to the Ubuntu server remotely using SSH.
