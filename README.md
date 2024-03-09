# Floppy Adapter for IBM PS/2 Model 85XX (55 / 56/ 57 / 90 wSLX)

This project is the result of the excellent (pre)work of https://github.com/jtgans/PS2FF/

It has been modified to integrate the last missing piece to make it working.

This card has been tested on a IBM PS/2 8557, and it is working like a charm with a GOTEK like floppy.

The current design is made simple with Troughhole

<img src="https://github.com/vibr77/PS2FloppyDiskAdapterWMediaSense/blob/main/doc/card_rev0.91b.png?raw=true" width=300>


### The licence is creative commons CC-BY-SA

Work based on
- JUNE TATE GANS
- june@theonelab.com
- https://github.com/jtgans/PS2FF


###This is the first release, small todo: 
- Change the BXC337 transistor and the TTL 74HC125 by a 74LS245 with using the 2nd line of buffer to manage the FDD Density select.
- Change the design to SMD to make it more compact

Bill of Material
- 5x 1K resistor
- 1x CAP Ceramic 10pf (noise filter)
- BC337 transistor 
- TTL 74LS125 or 74HC125 (prefer the HC)
- PS/2 Male pin connecter (LCSC ref C707014)
- Floppy Female pin connector right angle (LCSC ref C2897437)

Changes compare to June version:
- Different PCB routing
- Trough hole design
- JP2 Jumper to short PS2_DATA_RATE pin with FLOPPY_DENSITY_SELECT
- BC337 Transistor to inverse FDD_DENSITY
  

