# Day 10 Commands

1. `find / -perm /4000 2>/dev/null` — This searches the system for files with the SUID permission bit set. It can be useful during a security audit because SUID programs run with the privileges of their owner.

2. `last` — It displays a history of successful user login sessions.

3. `lastlog` — This shows the most recent login information for user accounts. On some newer Linux systems, `lastlog2` may be used instead.

4. `w` — It displays who is currently logged into the system and what they are doing.

5. `who` — It displays the users that are currently logged in.

6. `groups` — It shows the groups that the current user belongs to.

7. `passwd` — This changes a user's password or manages password-related settings.

8. `chage -l username` — It displays password aging and account expiration information for a user.

9. `lastb` — It displays failed login attempts recorded by the system. This may require elevated privileges and depends on the system's logging configuration.

10. `history | grep sudo` — It filters the command history to show commands containing `sudo`, which can help review previously executed administrative commands.
