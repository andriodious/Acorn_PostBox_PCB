# acorn_postbox_PCB
Acorn POST monitor PCB

This board enables the display of data from the 6 pin Acorn POST header on some Acorn machines e.g. Archimedes, A4000,A5000,A7000 and RiscPC motherboards from RISC OS 3.1 thru 3.71.  

The board contains a CPLD breakout daughterboard on one side, and an LCD output on the other.

A small clock circuit provides input for the CPLD, and a variable resistor to adjust the contrast of the LCD display. 

Power and ground are taken from the host systems POST header.


This project is based on the following GitHub project, and requires the code here to program the CPLD:

https://github.com/hoglet67/acorn_postbox