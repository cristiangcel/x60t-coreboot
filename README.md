# COREBOOT FOR X60T W/ INTEL GPU

All the content of this repository is provided without any kind of warranty, what you will do with the files I provide are your sole responsibility: in case of damage or any other problem I am not responsible. This project is for educational purposes only and I do not own the content of this repository!

--

DESCRIPTION

My coreboot build built on May 2025 for Lenovo (or IBM-Branded) Thinkpad X60 Tablet with Intel Integrated GPU.

Not all components are free software: it contains the binary blob "vgabios.bin" extracted from the original IBM BIOS (using "bios_extract") and containing the proprietary firmware of the graphics card, it contains the latest updates to the microcode.

- Intel GPU Proprietary Firmware
- Intel CPU Microcodes Updates
- SEABIOS as payload

Tested on IBM Thinkpad X60 TABLET TYPE 6364: I tested the internal flashing and external flashing (using CH341A 3.3v + SOIC8 Clip from Aliexpress) and both works, the internal monitor (touch panel) also shows image because it contains the proprietary video bios. Boot works for Linux distros and *BSD Systems, Windows not tested and I will not do it.

--

LICENSE

All coreboot code is released under the GNU GPL license (its license can be seen in the "COPYING" file), with the exception of the vgabios.bin file owned by Intel which is included for "fair use" as this is a project for educational purposes only.
