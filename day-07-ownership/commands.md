# Day 07 Commands

1. `chown user file` — It changes the owner of a file or directory.

2. `chown user:group file` — It changes both the owner and group of a file or directory.

3. `chown -R user:group directory` — It changes ownership recursively for a directory and everything inside it.

4. `chgrp group file` — It changes the group ownership of a file or directory.

5. `chmod u+s file` — This adds the SUID bit, allowing a program to run with the permissions of its file owner.

6. `chmod g+s file` — This adds the SGID bit. On files it affects execution, while on directories it can make new files inherit the directory's group.

7. `chmod +t directory` — It adds the sticky bit, restricting deletion of files in a shared directory to their owners or privileged users.

8. `find /path -perm /4000` — It searches for files that have the SUID permission bit set.

9. `getfacl file` — This displays the Access Control List (ACL) and shows additional permissions assigned to a file or directory.

10. `setfacl -m user:username:permissions file` — It's use to adds or modifies an ACL entry to give a specific user additional permissions.
