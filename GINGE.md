
---

# GINGE #

---


<i>Special thanks goes to the author of GINGE, Notaz, for providing GINGE source code.</i>

Taken from the [GINGE](http://notaz.gp2x.de/ginge.php) website.

<i>
Ginge is an application that can run many GP2X F100/F200, Wiz games and programs on other ARM Linux platforms. Currently it's closed source and runs on Pandora and Wiz itself.<br>
<br>
It is not a full hardware emulator like MAME, PicoDrive or similar, it does not emulate the CPU. It can be considered as compatibility layer similar to Wine on PC Linux, however it does emulate small portion of MMSP2 and Pollux system-on-chips. It operates by hooking certain system calls and using realtime patching of code that accesses memory mapped hardware directly.</i>

ZGrom comes with the ginge static loader binary (`/usr/bin/ginge_sloader`). With this loader you can run most statically compiled GP2X binaries. Further information about GINGE can be found in it's readme file which is located in `/usr/share/ginge/` directory of the ZGrom rootfs.

---

**Zaurus - GP2X GINGE keymap**

---



GP2X keys in GINGE are mapped to zaurus keys in the following manner:

<a href='http://imgur.com/KRvgW'><img src='http://i.imgur.com/KRvgW.jpg' alt='' title='Hosted by imgur.com' /></a>

Note that the Zaurus D-pad is also mapped to GP2X movement buttons.


GINGE also has a "killswitch" button that will try to instantly kill the
running GP2X application. This key is mapped to the X (Cancel) button on the zaurus.