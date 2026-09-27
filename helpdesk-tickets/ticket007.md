## Ticket 007 — Employee Cannot Install Required Software on Ubuntu Server

**Priority:** P3

**Issue:** Employee could not install a required package because package information was outdated.

**First Checks**

* Verified internet connectivity.
* Refreshed package repository using `sudo apt update`.
* Checked package availability using `apt search`.

**Action Taken**

* Updated package repositories.
* Installed the required package (`tree`) using `sudo apt install tree -y`.
* Verified successful installation.

**Status:** Resolved.

**Resolution:** Employee successfully installed and used the required software package.
