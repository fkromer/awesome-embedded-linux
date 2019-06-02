# awesome-embedded-linux

> A curated list of awesome Embedded Linux resources.

Embedded Linux: Operating systems based on the Linux kernel used in embedded systems such as consumer electronics, in-vehicle infotainment, networking equipment, machine control, industrial automation, navigation equipment, mobile devices, medical instruments, etc.

## Contents

- [Build systems](#build-systems)
- [Distributions](#distributions)
- [Hypervisors](#hypervisors)
- [Kernel patches](#kernel-patches)
- [Kernel modules](#kernel-modules)

## Build systems

- [buildroot](https://www.buildroot.org/).
- [Debos](https://github.com/go-debos/debos) - Debian OS builder.
- [ELBE](https://elbe-rfs.org/) - Debian based E.mbedded L.inux B.uild E.nvironment.
- [Isar](https://github.com/ilbers/isar) - Integration System for Automated Root filesystem generation (Debian).
- [LFS](http://www.linuxfromscratch.org/) - Linux system from source code.
- [LTIB](http://savannah.nongnu.org/projects/ltib) - Unmaintained?.
- [mkroot](https://github.com/landley/mkroot).
- [NARD](http://www.arbetsmyra.dyndns.org/nard/) - Specific to Raspberry Pi (compute modules).
- [OpenADK](https://www.openadk.org/).
- [OpenBricks](https://github.com/OpenBricks/openbricks).
- [OpenEmbedded](http://www.openembedded.org) - Build system used in the [Yocto Project](https://www.yoctoproject.org/).
- [OpenWrt](https://openwrt.org/).
- [PTXdist](https://www.ptxdist.org).

## Distributions

- [Android](https://www.android.com/versions/pie-9-0/).
- [Android (Go edition)](https://www.android.com/versions/go-edition/).
- [Ångström](http://www.angstrom-distribution.org/).
- [Arch Linux ARM](https://archlinuxarm.org/).
- [Embedded Gentoo](https://wiki.gentoo.org/wiki/Project:Embedded).
- [SnapGear Embedded Linux](http://www.snapgear.org/).
- [STLinux](https://www.st.com/en/development-tools/stlinux.html) - Linux for STMicroelectronics ARM or ST40 embedded processors.
- [Wind River Linux](https://www.windriver.com/products/linux/).
- [Aboriginal Linux](http://landley.net/aboriginal/) - DISCONTINUED.
- [Embdebian (Embedded Debian](http://www.emdebian.org/) - DISCONTINUED.
- [Ubuntu Core](https://www.ubuntu.com/core).
- [ELinOS](https://www.sysgo.com/products/elinos-embedded-linux).
- [Sailfish OS](https://sailfishos.org/).

## Hypervisors

- [Cross-OS](https://www.mapusoft.com/cross-os-hypervisor/) - Hypervisor used in the military domain.
- [Crudible](https://starlab.io/crucible-product/) - Hypervisor for defense systems.
- [Jailhouse](https://github.com/siemens/jailhouse) - Linux-based partitioning hypervisor.

## Kernel patches

- [PREEMPT_RT patch](https://rt.wiki.kernel.org/index.php/Main_Page) - "Controlling a laser with Linux is crazy, but everyone in this room is crazy in his own way. So if you want to use Linux to control an industrial welding laser, I have no problem with you using PREEMPT_RT." -- Linus Torvalds.

## Kernel modules

- [AppArmor](https://www.kernel.org/doc/html/v4.15/admin-guide/LSM/apparmor.html) - Linux Security Module that provides MAC style security extension for the Linux kernel.
- [LoadPin](https://www.kernel.org/doc/html/v4.15/admin-guide/LSM/LoadPin.html) - Linux Security Module that ensures all kernel-loaded files (modules, firmware, etc) all originate from the same filesystem, with the expectation that such a filesystem is backed by a read-only device
- [SELinux](https://www.kernel.org/doc/html/v4.15/admin-guide/LSM/SELinux.html) - Linux Security Module
- [SMACK](https://www.kernel.org/doc/html/v4.15/admin-guide/LSM/Smack.html) - Linux Security Module providing mandatory access control that includes simplicity in its primary design goals.
 - [TOMOYO](https://www.kernel.org/doc/html/v4.15/admin-guide/LSM/tomoyo.html) - Linux Security Module adding name-based MAC to the Linux kernel.
 - [Yama](https://www.kernel.org/doc/html/v4.15/admin-guide/LSM/Yama.html) - inux Security Module that collects system-wide DAC security protections that are not handled by the core kernel itself.
