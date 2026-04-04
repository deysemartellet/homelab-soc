# Errors and Fixes

## Disk Full Error (VirtualBox)

**Error:**
VERR_DISK_FULL

**Fix:**
- Freed space on host machine (~60GB available)
- Restarted installation

---

## ISO / Installation Issues

**Problem:**
Corrupted ISO caused installation errors (SQUASHFS errors)

**Fix:**
- Downloaded ISO again from a different browser
- Recreated VM

---

## SSH Service Not Starting

**Error:**
ssh.service inactive (dead)

**Fix Attempted:**
- Restarted service
- Checked logs

**Notes:**
Issue likely related to installation inconsistencies

---

## Wazuh OS Compatibility Error

**Error:**
System not supported (Ubuntu 24.04)

**Fix:**
Used:

```bash
sudo bash wazuh-install.sh -a -i

---

## Screen Resolution / Terminal Issues
**Problem:**
Terminal too small/text cut

**Fix:**
- Adjusted terminal size
- Used VirtualBox full screen mode