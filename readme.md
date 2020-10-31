# Awesome Embedded Linux [![Awesome](https://awesome.re/badge.svg)](https://github.com/sindresorhus/awesome#readme)

<div align="center"><img width="500" src="embedded_tux.png" alt="Awesome Embedded Linux"></div>

> A curated list of awesome Embedded Linux resources.

Embedded Linux: Operating systems based on the Linux kernel used in embedded systems such as consumer electronics, in-vehicle infotainment, networking equipment, machine control, industrial automation, navigation equipment, mobile devices, medical instruments, etc.

## Contents

- [Bootloaders](#bootloaders)
- [Build systems](#build-systems)
- [Container runtimes](#container-runtimes)
- [Container orchestration systems](#container-orchestration-systems)
- [Databases](#databases)
- [Display servers](#display-servers)
- [Distributions](#distributions)
- [Host-based Intrusion Detection Systems](#host-based-intrusion-detection-systems)
- [Hypervisors](#hypervisors)
- [Init systems](#init-systems)
- [Kernel patches](#kernel-patches)
- [Kernel modules](#kernel-modules)
- [Kubernetes](#kubernetes)
- [Kubernetes Edge Computing Platforms](#kubernetes-edge-computing-platforms)
- [OTA software updates](#ota-software-updates)
- [Platforms](#platforms)
- [Process control systems](#process-control-systems)
- [SSH servers](#ssh-servers)
- [Web servers](#web-servers)
- [Zero configuration networking](#zero-configuration-networking)
- [Books](#books)
- [Presentations](#presentations)
- [Trainings](#trainings)

## Bootloaders

- [barebox](https://www.barebox.org/) - A bootloader (initially named U-Boot v2) designed for embedded systems.
- [coreboot](https://www.coreboot.org/) - Extended firmware platform that delivers a lightning fast and secure boot experience on modern computers and embedded systems.
- [libreboot](https://libreboot.org/) - coreboot distribution with proprietary software removed.
- [RedBoot](http://ecos.sourceware.org/redboot/) - Complete bootstrap environment for embedded systems.
- [U-Boot](https://www.denx.de/wiki/U-Boot) - The Universal Bootloader.

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
- [OpenEmbedded](http://www.openembedded.org/wiki/Main_Page) - Build system used in the [Yocto Project](https://www.yoctoproject.org/).
- [OpenWrt](https://openwrt.org/).
- [picl-k3os-image-generator](https://github.com/sgielen/picl-k3os-image-generator) - Generates images for k3os compatible with various armv8/aarch64/arm64 devices.
- [PTXdist](https://www.ptxdist.org).

## Container runtimes

- [containerd](https://containerd.io/) - An industry-standard container runtime with an emphasis on simplicity, robustness and portability.
- [cri-o](https://cri-o.io/) - Lightweight Container Runtime for Kubernetes.
- [Docker Engine](https://www.docker.com/products/container-runtime) - The Industry-Leading Container Runtime.
- [frakti](https://github.com/kubernetes/frakti) - The hypervisor-based container runtime for Kubernetes.
- [runC](https://github.com/opencontainers/runc) - CLI tool for spawning and running containers according to the OCI specification.

## Container orchestration systems

- [Kubernetes](https://kubernetes.io/) - System for automating deployment, scaling, and management of containerized applications.
- [Nomad](https://www.nomadproject.io/) - Easy-to-use, flexible, and performant workload orchestrator that can deploy a mix of microservice, batch, containerized, and non-containerized applications.
- [okd](https://www.okd.io/) - OKD provides a complete open source container application platform which powers OpenShift (Kubernetes Distribution).
- [OpenShift](https://www.openshift.com/) - A hybrid cloud, enterprise Kubernetes platform to build and deliver better applications faster. Can be run on ARM as well (Kubernetes Distribution).
- [Rancher](https://rancher.com/) - From datacenter to cloud to the edge, Rancher lets you deliver Kubernetes-as-a-Service (Kubernetes Distribution).

## Databases

- [MongoDB Mobile](https://www.mongodb.com/products/mobile) - NoSQL MongoDB as embedded database for embedded devices (embedded, document-oriented).
- [Raima Database Manager](https://raima.com/raima-database-manager/) - Embedded, cross-platform, small-footprint, in-memory database developed for the IoT and the edge market (embedded, SQL).
- [SQLite](https://www.sqlite.org) - Defacto standard embedded SQL database for mobile phones (embedded, SQL).

## Display Servers

- [Enlightenment](http://www.enlightenment.org/) - (wayland, BSD).
- [Mazecompositor](https://github.com/capisce/mazecompositor) -  A 3D qtwayland compositor (wayland, MIT).
- [Mir](https://mir-server.io/) - The fast, open and secure display server for any device (wayland, GPL).
- [SWAY](https://swaywm.org/) - Tiling Wayland compositor (wayland, MIT).
- [Weston](https://github.com/wayland-project/weston) - Wayland project reference compositor (wayland, MIT).

## Distributions

### Traditional Distributions

- [Aboriginal Linux](http://landley.net/aboriginal/) - DISCONTINUED.
- [Android](https://www.android.com/versions/pie-9-0/).
- [Android (Go edition)](https://www.android.com/versions/go-edition/).
- [Ångström](http://www.angstrom-distribution.org/).
- [Arch Linux ARM](https://archlinuxarm.org/).
- [Clear Linux OS](https://clearlinux.org/) - Open source, rolling release Linux distribution optimized for performance and security, from the Cloud to the Edge, designed for customization, and manageability.
- [ELinOS](https://www.sysgo.com/products/elinos-embedded-linux).
- [Embdebian](http://www.emdebian.org/) - Embedded Debian, DISCONTINUED.
- [Embedded Gentoo](https://wiki.gentoo.org/wiki/Project:Embedded).
- [GoboLinux](https://gobolinux.org/) - Linux distribution redefining the entire filesystem hierarchy (no need for package database) which [runs on ARM](https://github.com/gobolinux/Documentation/wiki/GoboLinux-Embedded).
- [LinRT](https://www.linrt.com/wiki/linrt-bsp-wiki/) - Embedded Linux distribution that uses the FSL Community Yocto Project layers with LinRT proprietary layers for Phytec’s SOMs and Single Board Computers.
- [Mentor Embedded Linux Flex OS](https://www.mentor.com/embedded-software/linux/mel-flex-os/) - Highly customizable and flexible embedded Linux distribution based on the Yocto Project.
- [Mentor Embedded Linux Omni OS](https://www.mentor.com/embedded-software/linux/mel-omni-os/) - Enterprise class binary embedded Linux distribution based on Debian.
- [Moxa Industrial Linux](https://www.moxa.com/en/spotlight/industrial-computing/arm-linux-iiot-edge-gateway-portal/linux)
- [OpenSTLinux](https://www.st.com/en/embedded-software/stm32-mpu-openstlinux-distribution.html) - Yocto Project based Linux Distribution for STM32 multi-core microprocessors (MPU).
- [Sailfish OS](https://sailfishos.org/).
- [SnapGear Embedded Linux](http://www.snapgear.org/).
- [STLinux](https://www.st.com/en/development-tools/stlinux.html) - Linux for STMicroelectronics ARM or ST40 embedded processors.
- [Ubuntu Core](https://www.ubuntu.com/core).
- [Wind River Linux](https://www.windriver.com/products/linux/).

### Container Orchestration Distributions

- [k3os](https://k3os.io/) - Linux distribution designed to remove as much OS maintenance as possible in a Kubernetes cluster. It is specifically designed to only have what is needed to run k3s.
- [Photon OS](https://vmware.github.io/photon/) - Open source, minimal Linux container host that is optimized for cloud-native applications, cloud platforms and VMware infrastructure but runs on ARM as well. Supports Docker (container runtime) as well as Mesons and Kubernetes (container orchestration).
- [Talos](https://www.talos.dev/) - Talos is a modern OS designed to be secure, immutable, and minimal. Its purpose is to host Kubernetes clusters, so it is tightly integrated with Kubernetes. 

### Container Runtime Distributions

- [BalenaOS (formerly ResinOS)](https://www.balena.io/os/) - Operating System tailored for containers, designed for reliability, proven in production. Meant to be used with [OpenBalena](https://www.balena.io/open/) to deploy and manage connected devices and with [BalenaCloud](https://www.balena.io/cloud/) for deploying IoT applications.
- [CoreOS Container Linux](https://coreos.com/os/docs/latest/) - A container-focused OS that's designed for painless management in large clusters.
- [Fedora CoreOS](https://coreos.fedoraproject.org/) - Combines the best of CoreOS Container Linux and Fedora Atomic Host: Automatically updating, minimal, monolithic, container-focused operating system, designed for clusters but also operable standalone, optimized for Kubernetes but also great without it.
- [Linux microPlatform](https://foundries.io/products/#linux) - A minimal Linux distribution built using OpenEmbedded/Yocto providing OTA software updates and a container-based application runtime.
- [Oryx Linux](https://www.toganlabs.com/oryx-linux/) - Long-term maintenance oriented distribution providing a lightweight container runtime engine OryxCMD and Mender integration.
- [OSv](http://osv.io/) - OSv is the versatile modular unikernel designed to run unmodified Linux applications securely on micro-VMs in the cloud or on on-premise bare metal servers.
- [RancherOS](https://rancher.com/rancher-os) - A lightweight, secure Linux distribution, built from containers to run containers well.
- [Torizon](https://labs.toradex.com/projects/torizon) - Linux-based software platform providing a preconfigured Yocto-based Linux distribution, bootloader, OTA service and Docker container runtime.

## Host-based Intrusion Detection Systems

- [AIDE](https://aide.github.io/) - Advanced Intrusion Detection Environment, a file and directory integrity checker.
- [afick](http://afick.sourceforge.net/) - Another File Integrity Checker, monitors changes on the file system and detects intrusions.
- [chrootkit](http://www.chkrootkit.org/) - Checks for rootkits.
- [Open Source Tripwire](https://github.com/Tripwire/tripwire-open-source) - Security and data integrity tool for monitoring and alerting on file & directory changes.
- [OSSEC](https://www.ossec.net/) - The World’s Most Widely Used Host-based Intrusion Detection System.
- [rkhunter](http://rkhunter.sourceforge.net/) - A rootkit hunter.
- [SAMHAIN](https://la-samhna.de/samhain/) - Provides file integrity checking and log file monitoring/analysis, as well as rootkit detection, port monitoring, detection of rogue SUID executables, and hidden processes. 

## Hypervisors

- [ACRN](https://projectacrn.org/) - A flexible, lightweight reference hypervisor, built with real-time and safety-criticality in mind, optimized to streamline embedded development through an open source platform (type 1, bare metal).
- [Cross-OS Hypervisor](https://www.mapusoft.com/cross-os-hypervisor/) - Hypervisor used in the military domain (type 1, bare metal).
- [Crudible Embedded Hypervisor](https://starlab.io/crucible-product/) - Hypervisor for defense systems (type 1, bare metal).
- [Jailhouse](https://github.com/siemens/jailhouse) - Linux-based partitioning hypervisor.
- [L4Re Runtime Environment](https://l4re.org/) - Operating system framework built on top of the Fiasco microkernel and providing user-level infrastructure that includes services (program loading, memory management, virtual machine management, etc.).
- [LxWin](https://www.acontis.com/ja/lxwin.html) - (type 1, bare metal).
- [LynxSecure](https://info.lynx.com/products/lynxsecure-programmable-processor-partitioning-system) - Least privilege real-time separation kernel hypervisor (type 1, bare metal).
- [PikeOS](https://www.sysgo.com/products/pikeos-hypervisor) - Currently (Jan 2019) the only hypervisor worldwide that holds a Common Criteria certification EAL 3+ for its separation performance (type 1, bare metal).
- [QNX Hypervisor](https://blackberry.qnx.com/en/products/hypervisor/index) - (type 1, bare metal).
- [RTS Hypervisor](https://www.real-time-systems.com/product-highlights.html) - (type 1, bare metal).
- [Xen Project Hypervisor](https://xenproject.org/) - (type 1, bare metal).

## Init systems

- [dumb-init](https://github.com/Yelp/dumb-init) - A minimal init system for Linux containers.
- [finit](http://troglobit.com/projects/finit/) - Fast init for Linux systems.
- [minit](http://www.fefe.de/minit/) - A small yet feature-complete init.
- [OpenRC](https://github.com/OpenRC/openrc) - Dependency-based init system that works with the system-provided init program.
- [runit](http://smarden.org/runit/) - A UNIX init scheme with service supervision.
- [systemd](https://github.com/systemd/systemd) - The systemd System and Service Manager.
- [upstart](http://upstart.ubuntu.com/) - Event-based init system.

## Kernel patches

- [PREEMPT_RT patch](https://rt.wiki.kernel.org/index.php/Main_Page) - "Controlling a laser with Linux is crazy, but everyone in this room is crazy in his own way. So if you want to use Linux to control an industrial welding laser, I have no problem with you using PREEMPT_RT." -- Linus Torvalds.

## Kernel modules

- [AppArmor](https://www.kernel.org/doc/html/v4.15/admin-guide/LSM/apparmor.html) - Linux Security Module that provides MAC style security extension for the Linux kernel.
- [LoadPin](https://www.kernel.org/doc/html/v4.15/admin-guide/LSM/LoadPin.html) - Linux Security Module that ensures all kernel-loaded files (modules, firmware, etc) all originate from the same filesystem, with the expectation that such a filesystem is backed by a read-only device.
- [SELinux](https://www.kernel.org/doc/html/v4.15/admin-guide/LSM/SELinux.html) - Linux Security Module.
- [SMACK](https://www.kernel.org/doc/html/v4.15/admin-guide/LSM/Smack.html) - Linux Security Module providing mandatory access control that includes simplicity in its primary design goals.
- [TOMOYO](https://www.kernel.org/doc/html/v4.15/admin-guide/LSM/tomoyo.html) - Linux Security Module adding name-based MAC to the Linux kernel.
- [Yama](https://www.kernel.org/doc/html/v4.15/admin-guide/LSM/Yama.html) - Linux Security Module that collects system-wide DAC security protections that are not handled by the core kernel itself.

## Kubernetes 

- Ubuntu Core/Server (snap)
  - [microk8s](https://github.com/ubuntu/microk8s) - MicroK8s is a small, fast, single-package Kubernetes for developers, IoT and edge.

## Kubernetes Edge Computing Platforms

- [KubeEdge](https://kubeedge.io/en/) - KubeEdge is built upon Kubernetes and extends native containerized application orchestration and device management to hosts at the Edge.

## OTA software updates

- [HERE OTA Connect](https://www.here.com/products/automotive/ota-technology) - Over-the-air software updates for the automotive industry.
- [libostree](https://ostree.readthedocs.io) - Both a shared library and suite of command line tools that combines a "git-like" model for committing and downloading bootable filesystem trees, along with a layer for deploying them and managing the bootloader configuration.
- [Mender](https://mender.io/) - Open source client-server update manager.
- [RAUC](https://rauc.io/) - Lightweight update client that runs on your Embedded Linux device and reliably controls the procedure of updating your device with a new firmware revision.

## Platforms

- [RZ/G Linux Platform](https://www.renesas.com/eu/en/products/rzg-linux-platform.html)

## Process control systems

- [daemontools](http://cr.yp.to/daemontools.html) - Collection of tools for managing services.
- [M/Monit](https://mmonit.com/) - Can monitor and manage distributed computer systems (including their processes), conduct automatic maintenance and repair and execute meaningful causal actions in error situations.
- [s6](https://skarnet.org/software/s6/) - Suite of programs to allow process supervision (a.k.a service supervision).
- [Supervisor](http://supervisord.org/) - A client/server system that allows its users to monitor and control a number of processes.
- [watchdogd](https://github.com/troglobit/watchdogd) - Advanced System & Process Supervisor for (embedded) Linux.

## SSH servers

- [dropbear](https://matt.ucc.asn.au/dropbear/dropbear.html) - A relatively small SSH server and client particularly useful for "embedded"-type Linux.
- [sshd](https://www.ssh.com/ssh/sshd/) - Popular OpenSSH server.
- [TinySSH](https://tinyssh.org/) - Minimalistic SSH server which implements only a subset of SSHv2 features.
- [wolfSSH](https://www.wolfssl.com/products/wolfssh/) - Lightweight SSHv2 server library written in ANSI C and targeted for embedded, RTOS, and resource-constrained environments.

## Web servers

- [Apache](http://httpd.apache.org/) - httpd.
- [Barracuda](https://realtimelogic.com/products/barracuda-web-server/) - Optimized for deeply embedded devices in remote-monitoring and control-management applications.
- [Cherokee](http://cherokee-project.com/) - .
- [Hiawatha](https://www.hiawatha-webserver.org/) - An advanced and secure webserver for Unix.
- [lighttpd](https://www.lighttpd.net/) - Designed and optimized for high performance environments and for every server that is suffering load problems.
- [Monkey](http://monkey-project.com/) - Monkey is a lightweight and scalable Web Server with a strong focus on Embedded devices.
- [nginx](http://nginx.org/) - Web server and reverse proxy server with a strong focus on high concurrency, performance and low memory usage.
- [nostromo](http://www.nazgul.ch/dev_nostromo.html) - nhttpd is a simple, fast and secure HTTP server.
- [sthttpd](https://github.com/blueness/sthttpd) - A simple, small, portable, fast, and secure HTTP server.

## Zero configuration networking

- [Avahi](http://avahi.org/) - Service Discovery for Linux using mDNS/DNS-SD.
- [JmDNS](http://jmdns.sourceforge.net/) - Java implementation of multi-cast DNS and can be used for service registration and discovery in local area networks.

## Books

### System design

- [Building Embedded Linux Systems](https://elinux.org/Building_Embedded_Linux_Systems) - [Book website](https://www.oreilly.com/library/view/building-embedded-linux/9780596529680/).
- [Embedded Linux Primer](https://elinux.org/Embedded_Linux_Primer) - [Book website](http://www.embeddedlinuxprimer.com/).
- [Embedded Linux System Design and Development](https://elinux.org/Embedded_Linux_System_Design_and_Development) - [Book website](https://www.crcpress.com/Embedded-Linux-System-Design-and-Development/Raghavan-Lad-Neelakandan/p/book/9780849340581).
- [Linux for Embedded and Real-time Applications](https://www.elsevier.com/books/linux-for-embedded-and-real-time-applications/abbott/978-0-12-811277-9).
- [Pro Linux Embedded Systems](https://www.springer.com/de/book/9781430272274).

### System programming

- [Advanced Programming in the UNIX Environment](http://www.apuebook.com)
- [The Linux Programming Interface](https://elinux.org/The_Linux_Programming_Interface_-_by_Michael_Kerrisk) - [Book website](https://nostarch.com/tlpi), [free only version](http://man7.org/tlpi/).
- [Linux System Programming](https://www.oreilly.com/library/view/linux-system-programming/9781449341527/).
- [Linux Debugging and Performance Tuning: Tips and Tricks](https://elinux.org/Linux_Debugging_and_Performance_Tuning).

### Kernel development

- [Mastering Linux Kernel Development: A kernel developer's reference manual](https://www.packtpub.com/application-development/mastering-linux-kernel-development)

### Device driver development

- [Essential Linux Device Drivers](https://elinux.org/Essential_Linux_Device_Drivers) - [book website](https://www.elinuxdd.com/).
- [Linux Device Drivers](https://elinux.org/Linux_Device_Drivers) - [book website](http://shop.oreilly.com/product/9780596005900.do), [free only version](https://lwn.net/Kernel/LDD3/).
- [Linux Device Drivers Development: Develop customized drivers for embedded Linux](https://www.packtpub.com/networking-and-servers/linux-device-drivers-development).

## Presentations

- Embedded Linux Conference + OpenIoT Summit Europe 2018 [slides](https://events.linuxfoundation.org/events/elc-openiot-europe-2018/program/slides/) / [video playlist](https://www.youtube.com/playlist?list=PLbzoR-pLrL6qThA7SAbhVfuMbjZsJX1CY)
- Embedded Linux Conference + OpenIoT Summit North America 2018 [video playlist](https://www.youtube.com/watch?v=wirx1SwMlbA&list=PLbzoR-pLrL6qAnHzPdrTxwCUWPja5KnOq)
- Embedded Linux Conference + OpenIoT Summit Europe 2017 [video playlist](https://www.youtube.com/playlist?list=PLbzoR-pLrL6pISWAq-1cXP4_UZAyRtesk)
- Embedded Linux Conference + OpenIoT Summit North America 2017 [video playlist](https://www.youtube.com/playlist?list=PLbzoR-pLrL6pSlkQDW7RpnNLuxPq6WVUR)
- Embedded Linux Conference + OpenIoT Summit Europe 2016 [video playlist](https://www.youtube.com/playlist?list=PLbzoR-pLrL6pRFP6SOywVJWdEHlmQE51q)
- Embedded Linux Conference Europe 2015 [video playlist](https://www.youtube.com/playlist?list=PLGeM09tlguZTP9-9nMQNGiT_2PPFay0Cs)
- Embedded Linux Conference North America 2015 [video playlist](https://www.youtube.com/playlist?list=PLGeM09tlguZTPUxEvsQiDgX0XDjfOL6oR)
- Embedded Linux Conference Europe 2014 [slides](https://elinux.org/ELC_Europe_2014_Presentations)
- Embedded Linux Conference North America 2014 video playlist [slides](https://elinux.org/ELC_2014_Presentations) / [video playlist](https://www.youtube.com/playlist?list=PL_xRWvMmKDbLAOMqMDovw-4F9fEYmf15s)
- Embedded Linux Conference Europe 2013 [slides](https://elinux.org/ELC_Europe_2013_Presentations) / [video playlist](https://www.youtube.com/playlist?list=PLbzoR-pLrL6oxnDyb7IvnNOOBur7z_8tE)
- Embedded Linux Conference North America 2013 [video playlist](https://www.youtube.com/playlist?list=PLbzoR-pLrL6reuY8eZ9S1PRofvdp9O16w)
- Embedded Linux Conference Europe 2012 [slides](https://elinux.org/ELC_Europe_2012_Presentations)
- Embedded Linux Conference North America 2012 [slides](https://elinux.org/ELC_2012_Presentations)
- Embedded Linux Conference Europe 2011 [slides](https://elinux.org/ELC_Europe_2011_Presentations)
- Embedded Linux Conference North America 2011 [slides](https://elinux.org/ELC_2011_Presentations)
- Embedded Linux Conference Europe 2010 [slides](https://elinux.org/ELC_Europe_2010_Presentations)
- Embedded Linux Conference North America 2010 [slides](https://elinux.org/ELC_2010_Presentations)
- Embedded Linux Conference Europe 2009 [slides](https://elinux.org/ELC_Europe_2009_Presentations)
- Embedded Linux Conference North America 2009 [slides](https://elinux.org/ELC_2009_Presentations)
- Embedded Linux Conference Europe 2008 [slides](https://elinux.org/ELC_Europe_2008_Presentations)
- Embedded Linux Conference North America 2008 [slides](https://elinux.org/ELC_2008_Presentations)
- Embedded Linux Conference Europe 2007 [slides](https://elinux.org/ELC_Europe_2007_Presentations)
- Embedded Linux Conference North America 2007 [slides](https://elinux.org/ELC_2007_Presentations)
- Embedded Linux Conference 2006 [slides](https://elinux.org/ELC_2006_Presentations)

## Trainings

### System

- [Embedded Android (2net)](http://www.2net.co.uk/training/embedded-android).
- [Embedded Android + Automotive (2net)](http://www.2net.co.uk/training/embedded-android-automotive).
- [Embedded Linux Trainging (bootlin)](https://bootlin.com/training/embedded-linux/) - Free slides and lab material, paid sessions.
- [Linux Basics (Linutronix)](https://linutronix.de/en/schulung/linux_anfaenger.php) - From Bootloader to System.
- [Mastering embedded Linux (2net)](http://www.2net.co.uk/training/fast-track-to-embedded-linux).

### Build systems

- [Debian Distribution (Linutronix)](https://linutronix.de/en/schulung/debian_distro.php) - An introduction to ELBE.
- [Embedded Linux development with Buildroot training (bootlin)](https://bootlin.com/training/buildroot/) - Free slides and lab material, paid sessions.
- [Mastering Yocto Project (2net)](http://www.2net.co.uk/training/yocto-project).
- [Yocto (Linutronix)](https://linutronix.de/en/schulung/yocto.php) - An introduction to Yocto.
- [Yocto Project and OpenEmbedded development training (bootlin)](https://bootlin.com/training/yocto/) - Free slides and lab material, paid sessions.

### System programming

- [System programming for embedded Linux (2net)](http://www.2net.co.uk/training/system-programming-linux).

### Kernel and device driver development

- [Embedded Linux device drivers (2net)](http://www.2net.co.uk/training/embedded-linux-device-drivers).
- [Linux kernel and driver development training (bootlin)](https://bootlin.com/training/kernel/) - Free slides and lab material, paid sessions.

### Security

- [Security (Linutronix)](https://linutronix.de/en/schulung/security.php) - Embedded security.

### Misc

- [Displaying and rendering graphics with Linux (bootlin)](https://bootlin.com/training/graphics/) - Free slides and lab material, paid sessions.
- [Fastboot (Linutronix)](https://linutronix.de/en/schulung/fastboot.php) - Boot Linux within One Second.
- [Linux Advanced (Linutronix)](https://linutronix.de/en/schulung/linux_advanced.php) - Scheduling mechanisms, real-time, multicore, CPU isolation, IPC development, best practices of application development.
- [Realtime (Linutronix)](https://linutronix.de/en/schulung/realtime_and_more.php) - Linux and Realtime (Preempt-RT).
- [Tracing & Debug (Linutronix)](https://linutronix.de/en/schulung/tracing_and_more.php) - Detailed insight into the Linux Tracing Infrastructure and its powerful features.

## License

[![License: CC BY-NC-SA 4.0](https://img.shields.io/badge/License-CC%20BY--NC--SA%204.0-lightgrey.svg)](https://creativecommons.org/licenses/by-nc-sa/4.0/)
