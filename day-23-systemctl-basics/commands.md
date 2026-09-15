# Day 23 Commands — Init Systems & systemctl Basics

1. `systemctl start <service>` — It starts a system service.
2. `systemctl stop <service>` — It stops a running service.
3. `systemctl restart <service>` — It stops and starts a service again.
4. `systemctl reload <service>` — It reloads a service's configuration without fully stopping it.
5. `systemctl enable <service>` — This configures a service to start automatically at boot.
6. `systemctl disable <service>` — It prevents a service from starting automatically at boot.
7. `systemctl enable --now <service>` — This nables a service at boot and starts it immediately.
8. `systemctl status <service>` — This shows the current status and details of a service.
9. `systemctl is-active <service>` — It checks whether a service is currently active.
10. `systemctl is-enabled <service>` — It checks whether a service is enabled to start at boot.
