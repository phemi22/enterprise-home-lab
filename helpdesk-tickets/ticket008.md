## Ticket 008 — Finance Employee Cannot Access Shared Network Drive

**Priority:** P2 (High)

**Issue:** Finance employee Sarah could not access the Finance shared drive hosted on the Ubuntu Samba server.

**First Checks**

* Verified Samba service status.
* Verified Sarah's Linux group membership.
* Verified Sarah's Samba account was enabled.
* Verified Finance share permissions in `smb.conf`.

**Action Taken**

* Enabled Sarah's Samba account using `sudo smbpasswd -e sarah`.
* Restarted Samba services.
* Verified firewall allowed Samba traffic.
* Tested connection from Windows File Explorer.

**Status:** Resolved.

**Resolution:** Sarah successfully accessed the Finance shared drive from Windows.
