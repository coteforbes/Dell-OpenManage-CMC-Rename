# Dell-OpenManage-CMC-Rename
Renames CMC to Match Server name and sets 'iDrac Launch Method' to DNS so CMC's are discovered as names and not IP addresses in Open Manage Enterprise


Since this will only get run once, I just hardcoded the Idrac Password.

This uses a remote linux host with racadm remote tools installed and delegates the commands there, just remove the delete and modify shell command for local racadm use.
