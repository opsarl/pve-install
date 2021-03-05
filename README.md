# pve-install

This is our in house installer for proxmox
Removes subscription dialogs, sets up repositories and replaces branding. Tested on PVE 6.3.3.

## Install

1. Connect to node via SSH
2. Run

```bash
# as root
wget -qO - https://raw.githubusercontent.com/opsarl/pve-install/master/patch.sh | bash
```
