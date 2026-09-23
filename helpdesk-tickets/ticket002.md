## Ticket 002 — User Cannot Find Department Files on Linux Server

**Priority:** P3

**Issue:** A user connected to the Linux server but could not locate the Finance department folder.

**First Checks:**

* Verified current directory using `pwd`.
* Listed available folders using `ls`.
* Verified the Finance directory existed inside `/home/femi/Northwind`.

**Action Taken:**

* Navigated to the correct directory using `cd`.
* Verified folder structure with `ls -R`.
* Confirmed the Finance folder contained the required files.

**Status:** Resolved.
