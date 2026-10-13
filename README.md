# XGC SWITCH BUNDLE:



# Atmosphère

Atmosphère is a work-in-progress customized firmware for the Nintendo Switch.

The upstream Atmosphère project is developed independently by its maintainers and contributors. For official source code, documentation, support, compatibility information, and releases, visit:

- [Atmosphère GitHub repository](https://github.com/Atmosphere-NX/Atmosphere)
- [Atmosphère releases](https://github.com/Atmosphere-NX/Atmosphere/releases)

## Components

Atmosphère consists of multiple components, each of which replaces or modifies a different component of the system:

- **Fusée:** First-stage loader responsible for loading and validating stage 2, customized TrustZone, package2, kernel/FIRM sysmodules, and required patches. This replaces functionality normally handled by Package1loader/NX Bootloader.
- **Exosphère:** Customized TrustZone component used to run a customized Secure Monitor.
- **Thermosphère:** EL2 EmuNAND support, including backing up and using virtualized or redirected NAND images.
- **Stratosphère:** Custom sysmodules used to extend the kernel, provide features, and hook important system actions.
- **Troposphère:** Application-level Horizon OS patches used to implement custom firmware features.

## Licensing

Atmosphère is licensed under the terms of the GPLv2, subject to project-specific exemptions.

A copy of the license is available in the [LICENSE](LICENSE) file.

### Exemption

- [Nintendo](https://github.com/Nintendo) is exempt from GPLv2 licensing and may, at its option, license source code authored for the Atmosphère project under the Zero-Clause BSD license.

## Credits

Atmosphère is developed and maintained by **SciresM**, **TuxSH**, **hexkyz**, and **fincs**.

In no particular order, credit is also given to:

- **switchbrew** for the [libnx](https://github.com/switchbrew/libnx) project and extensive [Nintendo Switch documentation, research, and tool development](http://switchbrew.org).
- **devkitPro** for the [devkitA64](https://devkitpro.org/) toolchain and libnx support.
- **ReSwitched Team** for additional [documentation, research, and tool development](https://reswitched.github.io/) related to Nintendo Switch development.
- **ChaN** for the [FatFs](http://elm-chan.org/fsw/ff/00index_e.html) module.
- **Marcus Geelnard** for the [bcl-1.2.0](https://sourceforge.net/projects/bcl/files/bcl/bcl-1.2.0) library.
- **naehrwert** and **st4rk** for the original [hekate](https://github.com/nwert/hekate) project and its hardware-initialization codebase.
- **CTCaer** for the continued [hekate](https://github.com/CTCaer/hekate) fork and the [minerva_tc](https://github.com/CTCaer/minerva_tc) project.
- **m4xw** for development of the [emuMMC](https://github.com/m4xw/emummc) project.
- **Riley** for suggesting “Atmosphere” as the Horizon OS reimplementation and customization project name.
- **hedgeberg** for research and hardware testing.
- **lioncash** for code cleanup and general improvements.
- **jaames** for designing and providing Atmosphère graphical resources.
- Everyone who submitted entries for the Atmosphère [splash design contest](https://github.com/Atmosphere-NX/Atmosphere-splashes).
- All contributors to the [Atmosphère repository](https://github.com/Atmosphere-NX/Atmosphere).

---
