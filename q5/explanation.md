Question 5 explanation

- lsblk: This listed the available block devices and their partitions so the storage layout could be understood.
- mount | head -5: This showed the currently mounted filesystems and their mount points.
- df -h: This reported disk space usage, showing how much capacity was available on each mounted filesystem.
- df -i: This reported inode usage to confirm that the system had not reached inode limits.
- Storage observations: These findings help judge whether the environment has enough space and capacity for a new server deployment.
