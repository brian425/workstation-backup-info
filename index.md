# Proxmox Workstation Backups

Proxmox Workstation Backups is a personal, single-owner tool that automatically backs up the owner's own Proxmox workstation data to the owner's own Google Drive account.

## What it does

Backups run automatically on a schedule. Each backup is encrypted on the owner's own machine before it is uploaded, so the files stored in Google Drive are encrypted backup archives and are not readable without the owner's encryption key. The encryption key is kept by the owner and is never published or uploaded.

## Recovery verification

Backups are only useful if they can be restored. The owner periodically verifies recovery by checking that stored backups can be downloaded, decrypted, and restored successfully, so problems are found before they matter.

## Who uses it

This tool is for the owner's personal use only. It is not offered to other people, it has no other users, and it does not collect data from anyone else.

## Privacy

Read the [privacy policy](https://brian425.github.io/workstation-backup-info/privacy.html) for details about Google Drive access and how backup data is handled.

This page is informational only. It contains no credentials, no backup data, and no private files.
