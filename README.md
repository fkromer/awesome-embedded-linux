# awesome-embedded-linux

> A curated list of awesome Embedded Linux resources.

Embedded Linux: Operating systems based on the Linux kernel used in embedded systems such as consumer electronics, in-vehicle infotainment, networking equipment, machine control, industrial automation, navigation equipment, mobile devices, medical instruments, etc.

## Contents

- [Books](#books)
- [Build systems](#build-systems)
- [Distributions](#distributions)
- [Hypervisors](#hypervisors)
- [Kernel patches](#kernel-patches)
- [Kernel modules](#kernel-modules)
- [Platforms](#platforms)

## Books

### System design

- [Building Embedded Linux Systems](https://elinux.org/Building_Embedded_Linux_Systems) - [Book website](https://www.oreilly.com/library/view/building-embedded-linux/9780596529680/).
- [Embedded Linux Primer](https://elinux.org/Embedded_Linux_Primer) - [Book website](http://www.embeddedlinuxprimer.com/).
- [Embedded Linux System Design and Development](https://elinux.org/Embedded_Linux_System_Design_and_Development) - [Book website](https://www.crcpress.com/Embedded-Linux-System-Design-and-Development/Raghavan-Lad-Neelakandan/p/book/9780849340581).

### System programming

- [Advanced Programming in the UNIX Environment](http://www.apuebook.com)
- [The Linux Programming Interface](https://elinux.org/The_Linux_Programming_Interface_-_by_Michael_Kerrisk) - [Book website](https://nostarch.com/tlpi), [free only version](http://man7.org/tlpi/).
- [Linux System Programming]() - [Book website](https://www.oreilly.com/library/view/linux-system-programming/9781449341527/).
- [Linux Debugging and Performance Tuning: Tips and Tricks](https://elinux.org/Linux_Debugging_and_Performance_Tuning).

### Kernel development

- [Mastering Linux Kernel Development: A kernel developer's reference manual](https://www.packtpub.com/application-development/mastering-linux-kernel-development)

### Device driver development

- [Essential Linux Device Drivers](https://elinux.org/Essential_Linux_Device_Drivers) - [book website](https://www.elinuxdd.com/).
- [Linux Device Drivers](https://elinux.org/Linux_Device_Drivers) - [book website](http://shop.oreilly.com/product/9780596005900.do), [free only version](https://lwn.net/Kernel/LDD3/).
- [Linux Device Drivers Development: Develop customized drivers for embedded Linux](https://www.packtpub.com/networking-and-servers/linux-device-drivers-development).

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

- [Aboriginal Linux](http://landley.net/aboriginal/) - DISCONTINUED.
- [Android](https://www.android.com/versions/pie-9-0/).
- [Android (Go edition)](https://www.android.com/versions/go-edition/).
- [Ångström](http://www.angstrom-distribution.org/).
- [Arch Linux ARM](https://archlinuxarm.org/).
- [ELinOS](https://www.sysgo.com/products/elinos-embedded-linux).
- [Embdebian](http://www.emdebian.org/) - Embedded Debian, DISCONTINUED.
- [Embedded Gentoo](https://wiki.gentoo.org/wiki/Project:Embedded).
- [Moxa Industrial Linux](https://www.moxa.com/en/spotlight/industrial-computing/arm-linux-iiot-edge-gateway-portal/linux)
- [Sailfish OS](https://sailfishos.org/).
- [SnapGear Embedded Linux](http://www.snapgear.org/).
- [STLinux](https://www.st.com/en/development-tools/stlinux.html) - Linux for STMicroelectronics ARM or ST40 embedded processors.
- [Ubuntu Core](https://www.ubuntu.com/core).
- [Wind River Linux](https://www.windriver.com/products/linux/).

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

## Platforms

- [Torizon](https://labs.toradex.com/projects/torizon) - Linux-based software platform providing a preconfigured Yocto-based Linux distribution, bootloader, OTA service and Docker container runtime.
