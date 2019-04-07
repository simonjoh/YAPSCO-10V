# YAPSCO-10V
Modification of the YAPSC:10V with onboard -12V supply.

The board has the same outer dimensions and mounting hole positions as YAPSC:10V, so a drop-in replacement should be quite easy.

## Specifications
* Input voltage +12V..+24V (components can go further)
* Same as YAPSC:10V


## Schematic and PCB
Most of the schematic symbols have been updated with new ones from Kicad's library.

Some PCB footprints have been replaced with surface mounted versions to be able to squash in the -12V supply while keeping the board outline and mounting holes the same as YAPSC:10V.

The DB15 connector footprint has also been added to the PCB layout so that it can easily be soldered onto the board if needed.

The PCB now includes a DC-DC voltage inverter set to -12V, but can be adjusted as necessary with 2 feedback resistors (R28, R29). Component values for the DC-DC converter can be calculated with the SMath sheet "Calc MC33063.sm".


## Everything else
The firmware has not been modified and connectors are generally kept in the original places.


## Disclaimer
The board is being manufactured and therefore have not been tested yet. The only thing I have tested, is the DC-DC controller on a breadboard, but since everything has mainly been kept as the original it should just work right out of the box, right? :)
