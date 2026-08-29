# Day 06 Commands

1. `ls -l` — It displays detailed file information, the file permission string, owner, group, size, and modification time.

2. `chmod` (relative `+/-`) — Adds or removes specific permissions without changing the other permissions.

3. `chmod` (assignment `=`) — =This sets the exact permissions specified for the selected user, group, or others.

4. `chmod 755 file` — It gives the owner full permissions and gives the group and others read and execute permissions.

5. `chmod 644 file` — It gives the owner read and write permissions while giving the group and others read-only access.

6. `chmod 600 file` — It gives the owner read and write permissions while removing access for the group and others.

7. `chmod -R` — This applies the selected permission change recursively to a directory and everything inside it.

8. `umask` — It shows the current default permission mask used when creating new files and directories.

9. `umask -S` — This displays the current umask in a symbolic format that is easier to read.

10. `stat -c '%A %U %G' file` — This displays the file's permission string, owner, and group in a concise format.
