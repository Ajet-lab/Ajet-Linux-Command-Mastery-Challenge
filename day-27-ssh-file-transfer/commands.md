# Day 27 Commands — Remote Access & File Transfer

1. `ssh <user>@<host>` — It connects to a remote machine securely over SSH.
2. `ssh -p <port> <user>@<host>` — It connects to an SSH server through a specified port.
3. `ssh -i <key> <user>@<host>` — It connects using a specified private SSH key.
4. `ssh-keygen` — This generates an SSH key pair for authentication.
5. `ssh-copy-id <user>@<host>` — This copies a public SSH key to a remote user's authorized keys.
6. `scp <source> <destination>` — This securely copies files between local and remote machines.
7. `sftp <user>@<host>` — It opens an interactive secure file-transfer session.
8. `rsync <source> <destination>` — This synchronizes files and directories between locations.
9. `~/.ssh/config` — It stores SSH connection settings for easier access to remote hosts.
10. `sshd_config` — This contains SSH server settings that can be adjusted to improve security and control remote access.
