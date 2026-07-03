Question 3 explanation

- ln original.txt hardlink.txt: This created a hard link that shared the same inode as the original file.
- ln -s original.txt symlink.txt: This created a symbolic link that stored the path to the target rather than the file contents.
- ls -li and stat: These commands showed inode numbers and link counts, making the difference between hard and symbolic links visible.
- rm original.txt: This removed the original file name, and the hard link still worked because the inode remained available.
- cat symlink.txt: This failed after the original file was deleted because the symlink target no longer existed.
