<div align = "center">
<!--TBD  <img src = "https://raw.githubusercontent.com/kojq/run/main/LOGO.svg" width = 240/>-->

# Kiaien Linux
</div>

## About

Lay the foundation of a pragmatic Linux distribution.

The name is under reconsideration. The license is being decided.

## Usage

See [Warnings](#warnings).

Use the latest ISO release. [Ventoy](https://github.com/ventoy/Ventoy) is a suggested bootable USB solution.

Alternatively, fork or clone the repository to make changes, and [Build](#build).

## Community

Feel free to join the Discord server [here](https://discord.gg/hgGxdbvC).

## Activity

#### Current Status

Passive Development

#### Status Reason

Changes primarily consist of trivial adjustments.

#### Possible Status

- Active Development
- Passive Development (strictly allows mostly minor changes)
- Active Maintenance (strictly allows mostly issues and pull requests)
- Passive Maintenance (strictly considers mostly issues and pull requests)
- Archived

#### Dispute Status

If activity is not seen in this repository after 60 days, the project has gone on hiatus.

If activity is not seen in this repository after 90 days, the project has likely concluded.

The project should be archived if development has concluded. An issue can be rasied to archive the repository in this case.

## TODO

- the OS protects itself from any modification, as none is allowed
- it will self-repair in the event of change
- it always functions as intended
- every system file and file group hashed for damage detection and repair (idea tbd)
- package manager is designed for atomic upgrades and offline installs after parallel download with diff (understand swupd, pacman, rpm-ostree, transactional-update for fundamental concepts)
- designed to install from various repositories based on flags or implicit structure
- lowercase switches (flags as one) for efficient use
- easy rollback for user packages (we will separate the user and system packages and let them coexist, tbd how)

## Warnings

- The project does not currently exist

## Features

- ISA: RISC-V
- kernel: latest stable
- filesystem: btrfs with optimal compression balance
- security: Secure Boot, TPM 2.0, etc
- boot manager: rEFInd
- initramfs generating: booster
- init: systemd
- swap: zram
- elevated privilege: doas
- fstab, tmpfs

## Limitations

- The premise will remain exactly as described in [About](#about)
- Sensible suggestions to change the premise are welcome if assistance will be provided

## Build

There are currently no build instructions.

## Contribution

Disrespect is not tolerated. A contribution is welcome if it does not violate [Limitations](#limitations).

## License

Licensing is subject to change at the discretion of [kojq](https://github.com/kojq).

## Credits

This is placeholder text.
<!--The *Magnolia grandiflora* SVG is under CC0. It is based on the *[Magnolia flower flor](https://www.openclipart.org/detail/306895/magnolia-flower-flor)* SVG, [uploaded](https://www.openclipart.org/download/306895/1537228771.svg) on September 17, 2018, 11:59 p.m. by artist Betel Leclerc on Openclipart.-->

## Accessibility

This markdown file is meant to be practical, consistent, and comprehensive. Please reach out with an issue or via [Community](#community) for suggestions.
