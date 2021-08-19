**Build instructions for Pimoroni Trackball**

First we need to fit the trackball in the plate. The cutout is a tad too small to fit for the pimoroni to fit well with the choc switches.
Try to fit the trackball and use a file to widen the cutout untill the housing fits. File the edge nearest to the alpha keys.

Clip the six switches which are surrounded by the midplate into the plate.

Now we need to remove some parts of the pimoroni PCB ... don't panic, everything will be fine.
File away until the corner between the "5VOK" and "ADDR+1" print. 
This is how the result should look like:

Put the Pimoroni into the plate and try to fit it together with the midplate. The midplate should without being pushed out by the pimoroni pcb. If not, file a bit more until it fits.

ok, now take a look at the bottom of the pcb and see how the vias align between pcb and Pimoroni. There will be an overlap, thats ok. 
Solder some wire to each via on the Pimoroni. Try to keep the wire more to the edge. Try to fit the wires in a way that there is minimal wire or solder to the side where the plate will sit.

Again, fit the pimoroni in the plate. Use plate, switches and midplate to get a proper alignment and fit the wires through the pcb.

Solder and clip.

*if you use a Rev 2.0 board* (see back of pcb ner the inner thumbkey).
There is an error on the board. The Pomoroni GND PIN is not connected to the boards GND. Two options.

1. Solder a wire to the gnd pin. Feed it through the big hole next to the pimoroni and the IO Expander (the big chip) and solder the wire to the pins marked x (or look into the schematic to see which pins are gnd)
```
   | | | | | | | | | | | |
   | | | | | | | | | | | |
   -----------------------
  |                       |
  |       TCA9555         |
  |       TSSOP-24        |
   ------------------------
   | x x | | | | | | | | |
   | x x | | | | | | | | |
   
```
2. scrap away a bit of soldermask on the back of the board, the copperlayer there is Gnd. Either bridge with solder or use some wire to connect Pin with the copper.

 
Congratulations. Pimoroni installed!
