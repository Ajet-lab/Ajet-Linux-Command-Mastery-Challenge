# Day 05 Commands

1. `tree` — It displays files and directories in a tree-like structure, making it easier to understand how they are organized.

2. `tree -L number` — This shows the directory tree up to a particular depth.

3. `ln source link_name` — This create like a duplicate for a file, but the unique but of it is when you edit one it reflect on the other file automatically.

4. `ln -s source link_name` — It creates like a shortcut/symbolic link that points to another file or directory.

5. `readlink link_name` — This shows the path that a symbolic link points to.

6. `realpath path` — It displays the full absolute path of a file or directory.

7. `basename /path/to/file` — It extracts the final part of a path, this could be a file or directory name.

8. `dirname /path/to/file` — Extracts the directory portion of a path.

9. `pushd directory` / `popd` — `pushd` moves to a directory while saving the current location, and `popd` returns to the previously saved location. this do something similar to `cd -`

10. `ls -lt` — It lists files in long format and sorts them by modification time, here the newest file come first.
