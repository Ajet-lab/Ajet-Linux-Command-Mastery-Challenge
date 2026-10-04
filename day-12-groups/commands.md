# Day 12 Commands

1. `groupadd groupname` — It creates a new group that can be used to organize users and manage shared access.

2. `groupdel groupname` — It deletes an existing group when it is no longer needed.

3. `gpasswd -a username groupname` — It adds a user to an existing group.

4. `gpasswd -d username groupname` — It removes a user from a group.

5. `getent group groupname` — This displays information about a specific group from the system's group database.

6. `getent passwd username` — This displays information about a specific user from the system's user database.

7. `groups username` — It shows the groups a specified user belongs to.

8. `id -Gn username` — This displays only the names of the groups a user belongs to.

9. `newgrp groupname` — It switches the current active group for the current shell session.

10. `cat /etc/group` — This sisplays the contents of the local group information file.
