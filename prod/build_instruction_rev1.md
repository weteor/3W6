----
**This Revision is old and should not be used**
----

**if you are going to order pcb with the provided files please make sure the components in the BOM are still valid and have the correct values! I will update them from time to time, but there is no guarantee the current version is still correct.**

If the board was manufactured with the included Bom and Pick and Place Files the following components are needed to complete the build:

Amount | Component
-------|----------
3        | 12 pin USB-C Connectors (see [datasheet](https://github.com/weteor/3W6/blob/main/dev/docs/USBC_12pin_DataSheet.png), bought them from Aliexpress, choose the 0.8mm variant, not the 1.4mm)
1        | 3x6x2.5mm SMD Micro Switch, can be found on Ebay or Aliexpress
36       | Kailh Choc V1 switches
34       | Keycaps 1u, 17x18mm, Kailh original choc caps work, transparent ones might not. MKB fit perfectly
2        | Keycaps 1.5u, same as above exept size obviously
1        | USB-C to USB-A cable (connection to PC)
1        | USB-C to USB-C cable (connection between halves)
optional | some self adhesive neopren material to put under the board *alternativly* some rubber feet
optional | black permanent marker to paint the edges of the PCB

optional step:
- use a black (or whatever color matches your board) permanent marker to paint all edges. I think it looks a lot nicer with darker edges.

ok, let's start:
- solder the USB-C connectors to the board. Use the plate with switches clipped into the four cornerslots to check if the the plate fits while doing so. 
- solder the microswitch. Again solder one side and check if the plate will fit before soldering the other side.
- connect the left half ( with two USB connectors) to the PC and try to flash the board. If thats not working check the soldering on the connectors and look for any production errors. 
- Open some kind of editor and check if the board is working by shorting the two slots for each switch on the bottom of the pcb (use a paperclip or tweezers). 
- connect both sides and check the same way. ( you can safely connect the sides while the board is connected to the pc)

ok, ready to put the switches on.

To make it easier getting the spacing between plate and pcb right ( and make the USB connectors sit right between both), the diodes act as spacers. They are the highest (1.1 mm) components on the board. I even added some without function around the board edged to make it easier to fit the plate, so use them :)

- start with the four switches in the corners, clip them in the plate and solder them to the pcb. If unsure solder just one leg, that way it is easier to correct mistakes. make shure the space between the plate and the pcb is even all around.
- clip in a few more switches and solder them as above.
- rinse repeat

optional step:
- cut the neopren to fit the board and tack it under it, or use some rubber feet. 

Congratulations, you should have a functioning keyboard now!


