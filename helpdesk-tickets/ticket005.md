## Ticket 005 — Employees Cannot Connect to Ubuntu Server After Restart

**Priority:** P2 (High)

**Issue:** Multiple employees reported they could not connect to the Linux server using SSH after the server restarted.

**First Checks**

* Verified SSH service status using `systemctl status ssh`.
* Reviewed SSH logs using `journalctl -u ssh -n 20`.
* Confirmed SSH was listening on port 22 using `ss -tln`.

**Action Taken**

* Restarted the SSH service using `sudo systemctl restart ssh`.
* Confirmed the service returned to the **active (running)** state.
* Tested remote SSH connectivity from Windows PowerShell.

**Status:** Resolved.

**Resolution:** Employees successfully connected to the Ubuntu server after the SSH service was restarted.
