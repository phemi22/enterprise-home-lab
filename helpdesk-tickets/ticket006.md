## Ticket 006 — Ubuntu Server Cannot Access Company Website

**Priority:** P2 (High)

**Issue:** Ubuntu server could access the internet but could not resolve the company website.

**First Checks**

* Verified IP address using `ip addr`.
* Verified internet connectivity using `ping -c 4 8.8.8.8`.
* Tested DNS using `nslookup` and `dig`.
* Ran `traceroute` to identify where traffic stopped.

**Action Taken**

* Confirmed DNS resolution issue.
* Verified DNS server configuration.
* Retested website connectivity after DNS resolution succeeded.

**Status:** Resolved.

**Resolution:** Server successfully resolved and accessed the company website after DNS troubleshooting.
