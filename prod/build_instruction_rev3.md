**if you are going to order pcb with the provided files please make sure the components in the BOM are still valid and have the correct values! I will update them from time to time, but there is no guarantee the current version is still correct.**

If the board was manufactured with the included Bom and Pick and Place Files the following components are needed to complete the build:

Amount | Component
-------|----------
1        | 3x6x2.5mm SMD Micro Switch, can be found on Ebay or Aliexpress
36       | Kailh Choc V1 switches
34       | Keycaps 1u, 17x18mm, Kailh original choc caps work, transparent ones might not. MKB fit perfectly
2        | Keycaps 1.5u, same as above exept size obviously
1        | USB-C to USB-A cable (connection to PC)
1        | USB-C to USB-C cable (connection between halves)
optional | [Pimoroni Trackball Breakout](https://shop.pimoroni.com/products/trackball-breakout)
optional | [Tenting Puck](https://splitkb.com/products/tenting-puck)
optional | some self adhesive neopren material to put under the board, *alternativly* some rubber feet
optional | black permanent marker to paint the edges of the PCB

optional step:
- use a black (or whatever color matches your board) permanent marker to paint all edges. I think it looks a lot nicer with darker edges.

ok, let's start:
- solder the microswitch. Start with one side and check if the plate will fit before soldering the other side.
- connect the left half ( the one with two USB connectors) to the PC and try to flash the board. 
- Open some kind of editor and check if the board is working by shorting the two slots for each switch on the bottom of the pcb (use a paperclip or tweezers). If single switches don't work check and/or change the matching diode.
- connect both sides and check the same way. ( you can safely connect the sides while the board is connected to the pc)

optional step:
- solder the pimoroni trackball to the pcb. [See instructions here](./build_instruction_rev2_pimoroni.md)

ok, ready to put the switches on.

- start with the six switches which are completely surrounded by the midlayer. Clip them in the plate and solder them to the pcb. If unsure solder just one leg, that way it is easier to correct mistakes. Make sure the middle plate is tightly squeezed between plate and pcb. If you use a 2mm midplate, it is normal that the switch pins are only barely visible on the back of the pcb.
- clip in a few more switches and solder them as above.
- rinse & repeat

optional step:
- cut the neopren to fit the board and tack it under it, or use some rubber feet. 

Congratulations, you should have a functioning and nice looking keyboard now!
