# Day 08: Privilege Escalation & Identity

## Phase 2 - Permissions, Ownership & Security | Day 8 of 30

## Commands covered today

See [commands.md](./commands.md) for all 10 commands with their correct syntax and my own explanation of what each one does and when I would use it.

## What I practiced

Today I practiced running commands with elevated privileges, switching between users, and checking my current user and identity. I also explored `sudoers` through `visudo` and practiced running commands as specific users.

## What surprised me

What surprised me was how many different ways Linux provides to work with elevated privileges and switch users, instead of simply logging in directly as root.

I thought once you're a root user you should be able to run any command without authentication or getting error like `Permission dinied` but to my suprise we still need to to use `sudo` for you to get expected results.

## Evidence

Screenshot or terminal transcript of the drill in [evidence/](./evidence/).

## Related

Previous day: [Day 07 - Ownership & Special Bits](../day-07-ownership/)
