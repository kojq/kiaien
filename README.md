# kiaien
Lay the foundation of a pragmatic Linux distribution.

https://en.wiktionary.org/wiki

The name is under reconsideration.

The license is being decided and will likely be MPL 2.0.

Any media will be our own.

init: systemd

initramfs generating: booster

fs: btrfs with (optimal heuristically determined) compression

ZRAM rather than swap

Sign for Secure Boot

fstab, tmpfs

NVIDIA MOK

x86_64 v3, x86_64 v4, and RISC-V (unlikely, maybe ARM?)

Main goals
- the OS protects itself from any modification, as none is allowed
- it will self-repair in the event of change
- it always functions as intended
- every system file and file group hashed for damage detection and repair (idea tbd)
- package manager is designed for atomic upgrades and offline installs after download 
- designed to install from various repositories based on flags or implicit structure
- lowercase switches (flags as one) for efficient use
- easy rollback for user packages (we will separate the user and system packages and let them coexist, tbd how)
