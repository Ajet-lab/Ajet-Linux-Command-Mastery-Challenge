# Day 04 Commands

1. `find location/path -name "filename"` — it is used for searching for files or directory using its name.

2. `find location/path -type f/d` — Searches for regular files/directory.

3. `find location/path -size +100M` — Searches for files based on their size. The size value can be adjusted depending on what I am looking for.

4. `find location/path -mtime -5` — Finds files based on when they were last modified. For example, this can find files modified within the last seven days.

5. `find location/path -perm 755` — This searches for files with specific permissions. e-g 664, 644, 755 and so on.

6. `locate filename` — It quickly searches for a file using a database of file locations. here you might need to use `sudo` command if plocate isn't install yet

7. `updatedb` — It updates the database used by `locate` so newer files can be found.

8. `du` — This displays the disk space used by files and directories.

9. `du -sh directory_name` — It shows the total size of a directory in a short, human-readable format.

10. `df -h` — Shows available and used disk space for mounted filesystems in a human-readable format.
