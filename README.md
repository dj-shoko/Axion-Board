# Information
Fully functionally working PCB utilizing the RP2040 MCU with all GPIO pins broken out and able to be utilized. Main purpose of the board is for usage in beatmania IIDX and Sound Voltex controllers. The PCB can be dropped into DJ DAO based beatmania IIDX controllers as a drop in replacement, utilizing the same pin layout as their original PCBs. Main functionality allows for the usage of 11 buttons, 11 5V LEDs, 2 RGB pins, and 2 quadrature encoders (analog should also be accepted in theory due to those being hooked up to all 4 analog pins). PS2 support should be possible as well on the current PCB, but untested at the moment. Two extra pins are also available either for RGB or other general purposes if needed.

# Render and Schematics
[Current board render](images/render.png)
[Current board schematics](images/schematics.jpg)

# Credits
- [RP2040-designguide](https://github.com/Sleepdealr/RP2040-designguide/tree/main) to get started on the PCB designing aspects and schematics.
- [Pico Game Controller Firmware](https://github.com/speedypotato/Pico-Game-Controller) by SpeedyPotato for quick sanity check.
- [USBemani](https://github.com/progmem/usbemani) by Progmem for the current firmware I'm using for this board. Personally forked firmware UF2 files [here](https://github.com/dj-shoko/usbemani/releases).
