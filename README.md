What is xf86-input-wacom?
-------------------------

The Linux Wacom Project manages the drivers, libraries, and documentation for
configuring and running Wacom tablets under the Linux operating system. The
project consist of the Wacom Kernel driver ([input-wacom](https://github.com/linuxwacom/input-wacom)),
this X driver (xf86-input-wacom) and
[libwacom](https://github.com/linuxwacom/libwacom). Our drivers are
included in most major Linux distributions and provide out-of-the box support
for a wide variety of Wacom tablets and component devices.

Given this, you will only need this driver if you have a newer Wacom device,
are running an older operating system, or need a bugfix. If one of these situations applies to you,
[install xf86-input-wacom from source](https://github.com/linuxwacom/xf86-input-wacom/wiki/Building-The-Driver)
by following the instructions in our wiki.

Other systems:
--------------
The driver also builds on FreeBSD and DragonFly BSD, where it reads tablets
through the kernel's evdev interface. It needs the `evdev-proto` and
`libudev-devd` packages there. `isdv4-serial-inputattach`, its udev rules
and its systemd unit are only built on Linux.

Developers:
-----------
For developers and others needing additional information please see the
[wiki](https://github.com/linuxwacom/xf86-input-wacom/wiki).
