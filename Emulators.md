
---

<h1>Emulators</h1>

---




---


## GPFCE ##

---

GPFCE is a NES emulator.
  * GP2X native binary
  * Runs fullspeed with fullscreen scaling, 44100HZ sound at 0 frameskip

**Menu keybindings:**

  * O,L.ALT - Launch Rom
  * I,L.CTRL - Previous menu / Return to game

You can use left/right movement keys to page scroll the rom list.

**Emu keybindings:**

  * NES B - I,L.CTRL
  * TURBO NES B - 0,X
  * NES A - O,L.ALT
  * TURBO NES A - 9,Z
  * NES SELECT - MINUS
  * NES START - SPACE
  * SAVE STATE - Fn + SHOULDER CANCEL BUTTON
  * LOAD STATE - Fn + SHOULDER OK BUTTON
  * GO TO MENU - VOL.UP+VOL.DOWN (V+B keys)

More information about this emu can be found [here](http://wiki.gp2x.org/wiki/GPFCE).

---

## DrPocketSnes ##

---

DrPocketSnes is a SNES emulator. It's a zaurus port of DrPocketSnes v6.4.4 with some patches backported from v6.5.0 and v7.2.0.

  * Native Zaurus port
  * Built for speed, comes with pure arm assembly cpu cores
  * Most games run above 30 fps with 44100HZ sound

**Menu keybindings:**

  * Select item/enter menu/select rom - I,Z
  * Exit current menu - 0,S

**Emu keybindings:**

  * SNES A - A,9
  * SNES B - Z,I
  * SNES X - S,0
  * SNES Y - X,O
  * SNES L - SHOULDER CANCEL BUTTON
  * SNES R - SHOULDER OK BUTTON
  * SNES START - SPACE
  * SNES SELECT - MINUS
  * BACK TO MENU - BACKSPACE

DrPocketSnes has full save state support. However, it currently has no keybindings for saving/loading states. Saving/loading states can be done from the menu.

---

## OhBoy ##

---

OhBoy is a Game Boy/Game Boy Color emulator.

  * Native Zaurus binary, no changes to source code
  * Runs fullspeed with 44100HZ sound at 0 frameskip
  * Comes with a nice selection of screen scalers and filters

**Menu keybindings:**

  * Select item/enter menu/select rom - ENTER,O
  * Exit current menu - ESCAPE,I

**Emu keybindings:**

  * GAME BOY B - Z,I
  * GAME BOY A - X,O
  * GAME BOY START - SPACE
  * GAME BOY SELECT - MINUS
  * BACK TO MENU - BACKSPACE
  * SELECT SAVE STATE SLOT 1 - 4
  * SELECT SAVE STATE SLOT 2 - 5
  * SELECT SAVE STATE SLOT 3 - 6
  * SELECT SAVE STATE SLOT 4 - 7
  * SELECT SAVE STATE SLOT 5 - 8
  * SAVE STATE - CALENDAR KEY
  * LOAD STATE - MENU KEY

Please note that OhBoy will not show any visual cue when switching save state slots.


---

## GpSP ##

---

GpSP is a Game Boy Advance emulator.

  * Native Zaurus port
  * Most games run fullspeed with fullscreen scaling and 44100HZ sound

**Menu keybindings:**
  * Select item/enter menu/select rom - ENTER,9,0,I,O
  * Exit current menu - ESCAPE

**Emu keybindings:**

  * GBA B - L.CTRL,9,I
  * GBA A - L.ALT,0,O
  * GBA L - SHOULDER CANCEL BUTTON
  * GBA R - SHOULDER OK BUTTON
  * GBA START - SPACE
  * GBA SELECT - MINUS
  * BACK TO MENU - BACKSPACE
  * SAVE STATE - CALENDAR KEY
  * LOAD STATE - MENU KEY

GpSP requires a proper gba bios file. The one you need has the following
md5sum: `a860e8c0b6d573d191e4ec7db1b1e4f6`. The file is often named `gba_bios.bin`.

**Known bugs:**
  * Severe screen flicker when loading save states - Just enter/exit the menu and it will go away.
  * Garbled game screen snapshot in menu - not fixed yet.


---

## PicoDrive ##

---


PicoDrive is a Sega Genesis/Mega-CD/32X/SMS emulator.

  * Native GP2X binary
  * **all** Genesis and SMS games run fullspeed with 44100HZ sound, fullscreen scaling and 0 frameskip
  * Some 32X games will stutter and Mega-CD games will sometimes stutter during FMV sequences

**Menu keybindings:**

  * Select item/enter menu/select rom - L.ALT,O
  * Exit current menu - L.CTRL,I

**Emu keybindings:**

  * SEGA A - 9,Z
  * SEGA B - I,L.CTRL
  * SEGA C - O,L.ALT
  * SEGA START - SPACE
  * BACK TO MENU - MINUS

PicoDrive is a **very** advanced emulator and has a lot of options. For more information
about it's various options and how to run CD games, please read the readme file.


---

## Temper ##

---

<i> Special thanks goes to the author of Temper, Exophase, for providing Temper's source code.</i>

Temper is a TurboGrafx/TurboGrafx-CD/SuperGrafx emulator.

  * Native GP2X binary
  * Runs fullspeed with 44100HZ sound and fullscreen scaling

**Menu keybindings:**

  * Select item/enter menu/select rom - L.ALT,O
  * Exit current menu - L.CTRL,I

**Emu keybindings:**

  * TG16 I  - O,L.ALT
  * TG16 II - I,L.CTRL
  * TG16 MENU - SPACE
  * TG16 RUN - MINUS
  * VOL.DOWN /VOL.UP - B/V
  * BACK TO MENU - B+V
  * LOAD STATE - CANCEL SHOULDER BUTTON
  * SAVE STATE - OK SHOULDER BUTTON


For information on how to play CD games read Temper's readme file.


---

## GnGeo ##

---


GnGeo is a NEO GEO emulator.

  * Native zaurus port
  * Comes with pure arm assembly cpu cores.

Unfortunately, the arm assembly sound cpu core is broken on Zaurus so this port uses
the C version of the sound core. This makes the emu slower but still playable.

GnGeo requires the user to pass the location of roms as a commandline argument at runtime.
[Gmenu2X](Gmenu2X.md) selector feature is used to avoid this. When you start GnGeo from !Gmenu2X, you
are presented with a file selector. Simply navigate to the directory that contains your roms and
select any file in that directory. !Gmenu2X will then pass the path to that directory to GnGeo.

GnGeo requires a valid bios Neo-Geo bios file to run.

**Keybindings:**

  * NG Button A - 9,Z
  * NG Button B - 0,X
  * NG Button C - I,R.CTRL
  * NG Button D - O,L.ALT
  * NG Start - SPACE
  * NG insert coin - MINUS
  * Back to menu - ESCAPE (Cancel button)


---

## MAME4ALL ##

---


MAME4ALL is a Multiple Arcade Machine Emulator.

  * Native GP2X binary
  * Runs quite slow, only older machines run fullspeed
  * Most games will run quite fast if sound is disabled

MAME4ALL requires the user to pass the location of roms as a commandline argument at runtime.
[Gmenu2X](Gmenu2X.md) selector feature is used to avoid this. When you start MAME4ALL from Gmenu2X, you
are presented with a file selector. Simply navigate to the directory that contains your roms and
select any file in that directory. Gmenu2X will then pass the path to that directory to MAME4ALL.

**Menu keybindings:**

  * Select rom - 9,O,Z,L.ALT
  * Exit submenu - I,0,L.CTRL,X
  * Change option - Shoulder buttons


**Emu Keybindings:**

  * MAME Button A - O,L.ALT
  * MAME Button B - I,L.CTRL
  * MAME Button C - 9,Z
  * MAME Button D - 0,X
  * MAME Button E - Shoulder Cancel button
  * MAME Button F - Shoulder Ok button

  * Add credit - MINUS
  * Start - SPACE
  * Pause - Both shoulder buttons
  * Show profiler - Shoulder Cancel button + SPACE
  * Show FPS -  Shoulder Ok button + MINUS
  * Show MAME menu - MINUS + SPACE
  * Decrease/increase volume - V, B

To type OK when MAME requires it, press LEFT and then RIGHT.



---

## DCastaway ##

---


DCastaway is an Atari ST emulator.

  * Native Zaurus port
  * Runs most games at playable speeds with 44100HZ sound
  * Has switchable keyboard/mouse/joystick input modes
  * Emulates two floppy drives.

DCastaway requires the TOS bios file to run properly. This bios file should
be named `ROM` and placed in DCastaway directory. I recommend using the TOS 1.04 UK bios
version.

**Menu keybindings:**

  * Select item/enter menu/select rom - O,ENTER
  * Exit current menu - ESCAPE (Cancel button)
  * Load first floppy drive - ENTER
  * Load second floppy driver - SPACE

**Emu keybindings:**

  * Go to menu -  left alt + space
  * Swap disks - left alt + escape
  * Load snapshot - left alt + backspace
  * Save snapshot - left alt + tab
  * TAB - switch between input modes - joystick, mouse, regular keyboard input
  * Superthrottle - right ctrl
  * Inc/dec mouse speed left alt + left, right
  * Inc/dec snapshot slot left alt + up, down

  * Mouse button 1 = button 9 or space
  * Mouse button 2 = button 0 or left shift
  * Joystick button = Button O or left ctrl



---

## FUSE ##

---


FUSE is a ZX Spectrum emulator. For further information and instructions
please go [here](http://fuse-emulator.sourceforge.net/).


---

## ScummVM ##

---


From the ScummVM [website](http://www.scummvm.org/):

<i>
ScummVM is a program which allows you to run certain classic graphical<br>
point-and-click adventure games, provided you already have their data files.<br>
The clever part about this: ScummVM just replaces the executables shipped<br>
with the games, allowing you to play them on systems for which they were never designed!<br>
</i>

No changes were made to the ScummVM sources. Please note that the current version
of ScummVM that ships with ZGrom (1.4.1) has buggy touchscreen support. The touchscreen
is offset by a constant on it's y axis. To fix this do this:

  * Go to settings and open the GFX tab
  * Under `Graphics mode` select `Normal (no scaling)`
  * Enable `Aspect ratio correction`

ScummVM uses the SDL backend for handling sound/video and input. SDL that ships
with ZGrom has support for both mouse buttons.

  * Upper silkscreen area toggles left mouse button mode
  * Lower slikscreen are toggles right mouse button mode


---
