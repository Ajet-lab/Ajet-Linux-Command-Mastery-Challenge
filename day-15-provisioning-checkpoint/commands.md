# Day 15 Commands

1. `id username` — It displays the user ID, primary group, and other groups associated with a specific user.

2. `getent passwd username` — It retrieves information about a user from the system's configured user database.

3. `sudo useradd -m -G groupname username` — This creates a user with a home directory and adds them to a specified supplementary group.

4. `sudo passwd username` — It sets or changes the password for a specified user.

5. `apt list --installed` — It displays packages currently installed on the system.

6. `apt list --upgradable` — It shows installed packages that have newer versions available.

7. `sudo apt update && sudo apt install -y package_name` — It refreshes package information and, if successful, installs a package without asking for confirmation.

8. `dpkg -l | grep keyword` — This filters the installed package list to find packages matching a specific keyword.

9. `sudo apt autoremove` — It removes automatically installed dependency packages that are no longer needed.

10. `history` — It displays previously executed commands in the current shell history.
