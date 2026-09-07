# Day 15 Practical Drill — Provisioning a New Team Member

## Objective
Provision a complete new team member account (user, groups, password) and install the three tools they need for their role, in a single documented sequence.

## Team Member
Username: mscloud

## Group
developers

## Tools Installed
- Git
- Curl
- Tree

## Commands Used

```bash
sudo groupadd developers
sudo useradd -m -G developers mscloud
sudo passwd mscloud
sudo apt update
sudo apt install -y git curl tree