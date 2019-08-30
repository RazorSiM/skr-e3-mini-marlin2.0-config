# Readme

This repo includes only the file modified by me. You need Marlin 2 repo to get this working.

I'll try to keep it updated with major Marlin 2 releases.

## Features

**Bltouch** and probe offset for a Bullseye fan duct plus some tweaks to probe the central area
of the bed. the Z offset is -1.29, you may need to change this.
I changed the pins association to get the probe pins working:
```
#define Z_STOP_PIN         PC14

//
// Z Probe must be this pins
//
#define Z_MIN_PROBE_PIN    PC14
```

**Linear Advance** set to 0.6 for my Ender 3 

**EEPROM SDCard Emulation** to be tested. It should save the config in a file named eeprom.dat in to the SD Card

**Disabled** every bootscreen and some minor things to get more usefull features enabled.
* Info Menu ( useless )
* Arc Support - Something regardless CNC and Laser Cutting. It's **3226Bites**, a ton of memory!
* Bootscreen - It's kinda useless.