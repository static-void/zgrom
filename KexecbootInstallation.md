
---

# How to install Kexecboot #

---

First you need to download Kexecboot for your specific Zaurus model.
Go to [this](http://kexecboot.org/download) page and download Kexecboot
for your device.

The zip file you just downloaded contains two files:

  * updater.sh - A script that automatically install the Kexecboot kernel
  * zImage - The Kexecboot kernel

Place these two files into the root directory of your SD/MMC/CF card.
For best results, format your card to FAT16/FAT32 filesystem. FAT16 is
recommended.

Completely turn off your Zaurus device. **Plug in the charger and hold the OK button** and turn
your Zaurus on. You should see this menu:

---

<a href='http://imgur.com/TvZ1t'><img src='http://i.imgur.com/TvZ1t.jpg' alt='' title='Hosted by imgur.com' /></a>

---

Select option 4:

---

<a href='http://imgur.com/MLtsW'><img src='http://i.imgur.com/MLtsW.jpg' alt='' title='Hosted by imgur.com' /></a>

---

Now you will see the following dialog. Select CF if you placed your Kexecboot
files on a CF card or select SD if you placed the files on an SD/MMC card.

---

<a href='http://imgur.com/F3Wnx'><img src='http://i.imgur.com/F3Wnx.jpg' alt='' title='Hosted by imgur.com' /></a>

---

After that, your device will reboot and install the Kexecboot kernel and then
it will restart again. After that you should see the kexecboot menu:

---

<img src='http://kexecboot.org/sites/kexecboot.org/files/pictures/kexecboot-0.6-pre.png' alt='Kexecboot screenshot' />

---

**And that's it, you've successfully installed Kexecboot on your Zaurus!**