## Ticket 003 — Finance Employee Cannot Access Finance Folder

**Priority:** P2 (High)

**Issue:** Sarah from Finance received "Permission denied" when trying to access the Finance shared folder on the Linux server.

**First Checks**

* Verified Sarah's user account exists.
* Verified Sarah's group membership using `groups sarah`.
* Checked folder ownership using `ls -ld Finance`.

**Action Taken**

* Added Sarah to the `finance` group using `usermod -aG finance sarah`.
* Verified folder group ownership using `chown`.
* Applied `chmod 770` to the Finance folder.

**Status:** Resolved.

**Resolution:** Sarah successfully accessed the Finance shared folder after group permissions were updated.
