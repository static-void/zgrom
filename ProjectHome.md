
---

## Introduction ##

---


ZGrom is a gaming oriented distribution for Sharp Zaurus PDA devices. It's a console based distribution built around the [Gmenu2X](http://mtorromeo.github.com/gmenu2x/) SDL GUI.
ZGrom has a wide selection of quality emulators, game engines and apps. Currently, ZGrom only supports the following Zaurus models:

  * C-1000 - Akita
  * C-3000 - Spitz
  * C-3100 - Borzoi
  * C-3200 - Terrier

ZGrom comes with [GINGE](http://notaz.gp2x.de/ginge.php). In a nutshell, GINGE enables
ZGrom users to run unmodified [GP2X](http://en.wikipedia.org/wiki/GP2X) binaries. Some of the emulators and game engines that come with ZGrom are plain, unmodified GP2X binaries that execute on Zaurus devices via the GINGE static loader.

ZGrom is mostly built with the [OpenEmbedded](http://openembedded.org) build system.

Please read the wiki pages for further information on various parts and aspects of ZGrom.


---

## How to install ##

---


ZGrom **requires** [kexecboot](http://kexecboot.org) for booting.
Kexecboot installation instructions can be found [here](KexecbootInstallation.md).

**After you install kexecboot:**

Currently, ZGrom doesn't support installation onto the internal NAND flash of Zaurus devices.
It can be installed on MMC/SD/SDHC/CF cards (EXT2 and EXT3 filesystems are supported).

To install ZGrom you need to:

  1. Download the ZGrom rootfs tarball.
  1. Unpack the rootfs tarball into your MMC/SD/CF card.
  1. Download the kernel for your Zaurus model.
  1. Place the kernel **zImage** file into the `/boot` folder of the rootfs
  1. Enjoy ZGrom :)