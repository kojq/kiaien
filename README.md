# kiaien
Lay the foundation of a pragmatic Linux distribution.

https://en.wiktionary.org/wiki

The name is under reconsideration.

The license is being decided, and MPL 2.0 is being considered.

## RISC-V and latest x64
- kernel: latest stable
- filesystem: btrfs with optimal compression balance
- security: Secure Boot, TPM 2.0, etc
- boot manager: rEFInd
- initramfs generating: booster
- init: systemd
- swap: zram

- fstab, tmpfs

## Main goals
- the OS protects itself from any modification, as none is allowed
- it will self-repair in the event of change
- it always functions as intended
- every system file and file group hashed for damage detection and repair (idea tbd)
- package manager is designed for atomic upgrades and offline installs after parallel download with diff (understand swupd, pacman, rpm-ostree, transactional-update for fundamental concepts)
- designed to install from various repositories based on flags or implicit structure
- lowercase switches (flags as one) for efficient use
- easy rollback for user packages (we will separate the user and system packages and let them coexist, tbd how)
