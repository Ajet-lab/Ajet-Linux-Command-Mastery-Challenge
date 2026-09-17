# Day 25 Commands — Process & Service Checkpoint

1. `ps aux | grep <process>` — This searches the process list for a specific process.
2. `systemctl status <service>` — It checks the current status of a service.
3. `journalctl -u <service> --since today` — This shows today's logs for a specific service.
4. `kill -0 <PID>` — It checks whether a process exists without actually terminating it.
5. `uptime` — This shows how long the system has been running and its load averages.
6. `free -h` — It displays memory usage in a human-readable format.
7. `vmstat` — It reports information about processes, memory, paging, and CPU activity.
8. `iostat` — It displays CPU and input/output statistics.
9. `watch <command>` — This repeatedly runs a command and displays updated output.
10. `crontab -e / crontab -l` — It edits or lists scheduled cron jobs for the current user.
