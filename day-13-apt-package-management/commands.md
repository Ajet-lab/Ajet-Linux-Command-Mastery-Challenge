# Day 13 Commands

1. `sudo apt update` — It refreshes the local package list with the latest information from configured software repositories.

2. `sudo apt upgrade` — This upgrades installed packages to newer available versions without unnecessarily removing existing packages.

3. `sudo apt full-upgrade` — This upgrades packages and can remove or install packages when necessary to complete dependency changes.

4. `sudo apt install package_name` — This installs a specified software package and its required dependencies.

5. `sudo apt remove package_name` — It removes an installed package but usually leaves its configuration files behind.

6. `sudo apt purge package_name` — It removes a package along with its configuration files.

7. `sudo apt autoremove` — It removes packages that were automatically installed as dependencies but are no longer needed.

8. `apt search keyword` — It searches the available package list for packages matching a keyword.

9. `apt show package_name` — This displays detailed information about a package, such as its version, description, and dependencies.

10. `dpkg -l` / `dpkg -L package_name` — `dpkg -l` lists installed packages, while `dpkg -L` shows the files installed by a specific package.
