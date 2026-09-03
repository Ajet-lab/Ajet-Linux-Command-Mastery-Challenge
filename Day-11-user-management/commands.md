# Day 11 Commands
**All the commands are to be preceeded with `sudo` when using them except you're in the `root` directory**

1. `useradd username` — It creates a new user account with default settings. Depending on the system configuration, it may not automatically create a home directory.

2. `useradd -m username` — It creates a new user account and also creates a home directory for that user.

3. `useradd -m -s /bin/bash username` — It creates a user with a home directory and sets their login shell to Bash.

4. `adduser username` — It creates a new user interactively. On Debian/Ubuntu systems, it is generally more user-friendly because it guides you through account setup.

5. `passwd username` — This sets or changes the password for the specified user.

6. `usermod -aG group username` — It adds an existing user to an additional group without removing their existing group memberships.

7. `usermod -s /bin/bash username` — This changes the login shell for an existing user.

8. `usermod -l new_username old_username` — This changes an existing user's login name.

9. `userdel username` — It deletes a user account but would leave the user's home directory and files behind.

10. `userdel -r username` — It deletes a user account along with their home directory and associated mail its files.
