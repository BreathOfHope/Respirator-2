RS274X format gerber files for PCB fabrication
Double layer PCB 4100mils x 2500 mils, standard FR4, 1.6mm thickness
Usable with 1oz Copper thickness, but 2oz preferred. Min 8mil vias and tracks, 
Solder paste, Solder mask, Silk screen and signal layers (for top and bottom) along with drill files

Engineering Changes needed on BoHv0.1 PCBs for use with Arduino Nano: Solder a short wire from pin8 to pin6 and another from pin7 to pin5 of nano_conn_2 on solder side, if the rotary encoder is to be used with Nano. (i.e connect A4 to A6 and A5 to A7. Please note that A4-A5 are the same pins used as SCL-SDA for I2C).
No changes needed for Uno.

These changes shall be included in next gerber release.
