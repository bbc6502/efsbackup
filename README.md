# efsbackup
Linux encrypted filesystem backup utilities

Utilities to create, mount, backup, and unmount a luks encrypted BTRFS filesystem on an external drive.

| Utility | Purpose | Example |
| ------- | ------- | ------- |
| efs-mount | Mount a luks encrypted filesystem | efs-mount sda1 |
| efs-backup | Backup to a mounted luks encrypted filesystem | efs-backup sda1 |
| efs-umount | Unmount a luks encrypted filesystem | efs-umount sda1 |
| efs-create | Create a luks encrypted filesystem | efs-create sda1 |
