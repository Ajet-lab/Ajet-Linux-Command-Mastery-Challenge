# Day 09 Commands

1. `md5sum file` — This generates an MD5 checksum that can be used to check whether a file has changed.

2. `sha256sum file` — It generates a SHA-256 checksum for verifying the integrity of a file.

3. `gpg --gen-key` — This starts the process of generating a GPG key pair for encryption and signing.

4. `gpg --encrypt file` — It encrypts a file so its contents cannot be read normally without the required key.

5. `gpg --decrypt file.gpg` — It decrypts a GPG-encrypted file so its original contents can be accessed.

6. `chattr +i file` — It makes a file immutable, preventing it from being modified, deleted, or renamed normally.

7. `lsattr file` — This displays the special attributes set on a file.

8. `ufw enable` — It enables the Uncomplicated Firewall (UFW).

9. `ufw allow port` — It creates a firewall rule allowing traffic through a specified port.

10. `ufw status` — This displays the current `ufw` firewall status and active rules.
