# Day 24 Commands — Deeper Service Management & Logs

1. `systemctl list-units --type=service` — This lists currently loaded service units.
2. `systemctl list-units --state=failed` — This lists service units that have failed.
3. `systemctl daemon-reload` — This reloads systemd configuration files after changes.
4. `journalctl` — It displays logs collected by the systemd journal.
5. `journalctl -f` — It follows new journal entries in real time.
6. `journalctl -u <service>` — This shows logs for a specific service.
7. `journalctl --since <time>` — This shows logs from a specified time onward.
8. `journalctl -p err` — It displays log entries with error priority.
9. `tail -f /var/log/syslog` — This follows new entries added to the system log.
10. `tail -f /var/log/auth.log` — This follows authentication-related log entries in real time.
