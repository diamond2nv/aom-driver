# AOM Driver

A high-flexibility, low-cost RF driver for AOMs and EOMs designed by N. Pisenti, D. Barker and A. Restelli.
This design is released under the CERN Open Hardware License v1.2.

The eagle files in this repository will be much easier to use with [eagle-config](https://github.com/JQIamo/eagle-config) installed and configured.

The information in below is for the older version of the AOM driver (v1.0). For documentation on the newest version, go to the [Wiki](https://github.com/JQIamo/aom-driver/wiki/AOM-Driver-Wiki).

# Previous Version

AOM driver design files. The board is designed to do signal conditioning and pre-amplification to drive a secondary stage power amplifier.

## Overview

* `AOM_CadFiles` -- contains the gerbers, BOM, centroid file, and manufacturing instructions for the PCB.
* `TriquintAmplifier` -- preliminary design which utilizes a ~ $10, 2W amplifier chip. Remaining work needs to be done for (broadband) impedance matching.
* `arduino` -- Arduino code to run on the Teensy (controls onboard VCO, VCA, display/frontpanel interaction, etc.)
* `protocase` -- Design files for protocase boxes. 2U version is good for standard amplifiers, 3U version is designed for 5W amps (eg, to drive 1064 AOMs).

See the pdf [here](/static/aom-driver-summary.pdf) for generic info.
