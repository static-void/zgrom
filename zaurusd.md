
---

# zaurusd #

---

zaurusd provides the following functionality:

  * Backlight control
  * Automatic headphone/speaker switching
  * Automatic usb host/client switching
  * Automatic kdrive screen rotation

Some of these functions can be adjusted with the `zaurusd-ctl` utility

---

**Backlight control**

zaurusd handles backlight increase/decrease button mappings. These are mapped as follows:

  * Fn + 1 - Turn off backlight (press any key to turn the backlight on)
  * Fn + 3 - Decrease backlight intensity
  * Fn + 4 - Increase backlight intensity

zaurusd will also autmatically turn off the backlight when you close the zaurus screen.

---

**Headphone/speaker switching**

zaurusd will automatically switch between headphone/speaker outputs. So for instance, if you plug in your headphones, zaurusd will automatically disable the speaker and enable the headhphone output and vice versa. Note however that zaurusd currently cannot detect whether the headphones were plugged in after resuming from STR (Suspend To Ram). So if you plug in your headphones while the zaurus is suspended and if you then resume it, zaurusd will **not** detect the headphones.

---

**Usb host/client switching**

zaurusd will automatically switch between usb host/client drivers based on the type of cable inserted into the zaurus device. So for instance, if you insert the usb host cable, zaurusd will unload all current usb drivers and load the proper usb host drivers.

The default usb client gadget device is `g_ether`. This can be changed with the `zaurusd-ctl` utility. so for instance, if you want to enable the usb gadget mass storage driver, try this:

`$zaurusd-ctl -u g_mass_storage,file=/dev/blockdevice`

As you can see, the `-u` switch takes a comma separated list of arguments. The first argument is the name of the module driver, the following arguments are just arguments specific to that module. In the abovementioned example the `file` argument is an argument of the `g_mass_storage` module that specifies which block device to use as usb mass storage.