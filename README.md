<div align = "center">

# Kiaien Linux

This file is intended to be accessible, practical, consistent, and comprehensive. Please reach out with an issue or via [Community](#community) for suggestions.
</div>

## Community

Disrespect is not tolerated. Feel free to [join the Discord server](https://discord.gg/peezNh4pS4).

## Warnings

- The project does not currently exist

## Usage

Use the latest ISO release. [Ventoy](https://github.com/ventoy/Ventoy) is a suggested bootable USB solution.

Alternatively, fork or clone the repository to make changes, and [Build](#build).

## Features

- ISA: RISC-V
- kernel: latest stable
- filesystem: ssdfs for NVMe ZNS SSDs or btrfs with optimal compression balance
- security: Secure Boot, TPM 2.0, etc
- boot manager: rEFInd
- initramfs generating: booster
- init: systemd
- swap: zram
- elevated privilege: doas
- network manager: NetworkManager
- desktop environment: COSMIC or GNOME
- fstab, tmpfs
- uutils instead of coreutils
- exa or lsd instead of ls
- helix instead of vim
- account: by default, encourages password, doas access, and no root or administrator access
- account: changes can be made during the install process
- account: enforce lack of doas access to result in root access to prevent potential lockout (needs citation)

## Build

There are currently no build instructions.

## Credits

This is placeholder text.
<!--The *Magnolia grandiflora* SVG is under CC0. It is based on the *[Magnolia flower flor](https://www.openclipart.org/detail/306895/magnolia-flower-flor)* SVG, [uploaded](https://www.openclipart.org/download/306895/1537228771.svg) on September 17, 2018, 11:59 p.m. by artist Betel Leclerc on Openclipart.-->

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

## License

Licensing is subject to change at the discretion of [kojq](https://github.com/kojq).
