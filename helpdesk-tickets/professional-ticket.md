## Ticket 001 — Virtual Machine Could Not Run Ubuntu

**Priority:** P3

**Issue:** Ubuntu virtual machine could not start because virtualization was disabled in firmware.

**First Checks:**

* Checked Task Manager → CPU Performance.
* Verified `systeminfo` Hyper-V requirements.

**Action Taken:**

* Enabled Intel Virtualization Technology (VT-x) in HP BIOS.
* Verified virtualization status in Task Manager.
* Installed Oracle VirtualBox.
* Created Ubuntu Server virtual machine.

**Status:** Resolved.

**Resolution:** Ubuntu Server VM successfully booted after enabling virtualization.
