# SteelSeries Aeros 9 Wireless

This is a mostly perfect mouse. It can be used with bluetooth, wireless or wired.

## Keyboard

On the left side is a number pad which unfortunatly defaults to the number row of
a regular keyboard and not the numeric pad.

To fix this, copy the file `90-steelseries-aeros-9-wl.hwdb` into the folder
`/etc/udev/hwdb.d` and update the hardware database of the system. Usually,
this is done by running `systemd-hwdb update`. Next time when the mouse
connects to the system the buttons will be mapped to the numeric keypad.
