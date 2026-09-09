# Day 17 Commands

1. `nano ~/.bashrc` — This opens the `.bashrc` file in Nano so I can add or change shell configurations for my user.

2. `source ~/.bashrc` — It reloads the `.bashrc` file in the current shell so changes can take effect immediately without opening a new terminal.

3. `cat ~/.bash_profile` — This displays the contents of the `.bash_profile` file, which can contain commands that run when a login shell starts.

4. `sudo nano /etc/environment` — This opens the system-wide environment configuration file for editing with administrator privileges.

5. `sudo nano /etc/bash.bashrc` — This opens the system-wide Bash configuration file, affecting Bash shells according to the system's configuration.

6. `alias name='command'` — This creates a shortcut name for a command, making frequently used commands quicker to run.

7. `unalias name` — This removes an existing alias from the current shell session.

8. `type command` — It shows how the shell interprets a command, such as whether it is an alias, builtin, function, or executable.

9. `which command` — It shows the path of the executable that would normally run when the command is entered.

10. `whereis command` — It searches for locations related to a command, including its binary, source, and manual page files when available.
