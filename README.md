![3w6](https://raw.githubusercontent.com/weteor/3W6/main/images/3w6_rev2_1s.jpg) 

# 3w6 - split ortholinear keyboard

The 3w6 is a low profile, split ortholinear keyboard with 36 keys.

I needed a keyboard for work and wasn't really satisfied with the available alternatives (namely Corne, Kyria and Ferris), mostly because they were rather large and didn't had the spacing I would like.

It's designed to be a no frills, cheap and small keyboard to be taken everywhere.

So no hotswap, no multiple switchtypes, no encoders, no LEDs.

BUT with onboard controllers (so no extra ProMicros, Elite-C), production files including SMT assembly files, and sturdy through hole mounted USB-C connectors.

## revision 2
changes:
- new middle plate (1.6mm, better 2.0mm) instead of diodes. Uses Aluminium PCBs as a cheaper alternative to lasered aluminium. 
- pimoroni trackball support (can only be used combined with the new middle plate when used with the plate)
- plate is now 1.2mm thick, to fit the chocs better. Needs middle plate, since the cutouts of the USB-Connectors were left out. There is enough space for them under the plate, when the middle plate is in place.
- added mounting holes to support tenting puck from splitkb.com. Due to insufficient space not all 4 holes are supported, but 3 screws should be enough to hold everything comfortably in position. Can only be used plateless! 
- package for the MCU was changed from QFN44 to TQFP44, since the previous one wasn't available. Can now be soldered/replaced by hand if need.
- IO-expander was changed from TCA9555RTWR to TCA9555PWR (alternativly PCA9555PW), since the previous one wasn't available. Package changed from WQFN24 to TSSOP24. Can now be soldered/replaced by hand if need.
- Board can now be soldered by hand if needed (challenging though, 0402 components). 

## try it
You may also compare the layout with other layouts of other layouts at https://jhelvy.shinyapps.io/splitkbcompare/ .

Or you can print [this file](https://raw.githubusercontent.com/weteor/3W6/main/plate_outline.pdf) to test if you like the layout. Or mount it to some cardboard and test it with your favourite switches.

## production files
If you want to build one yourself, grab the 
Gerber files [here](https://github.com/weteor/3W6/tree/main/prod/Rev2) and give it a go.

And if 3d printing is your thing, files for plate and midlayer can be found [here](https://github.com/weteor/3W6/tree/main/prod/Rev2/3d%20Print) (made by the great [bomtarnes](https://github.com/keyboard-magpie), thanks a lot!)
## build instructions
you may find instructions here: 
- rev1 (deprecated): [build instructions rev1](./prod/build_instruction_rev1.md)
- **rev2 (current)**   : [build instructions rev2](./prod/build_instruction_rev2.md)

## firmware
This keyboard uses [QMK firmware](https://qmk.fm/).
You can find everything you need to build a firmware for this board in the [QMK Repository](https://github.com/qmk/qmk_firmware). 

Here are some instructions on how to [set up your QMK environment](https://docs.qmk.fm/#/newbs) and a few notes [specifically for the 3w6](https://github.com/qmk/qmk_firmware/tree/master/keyboards/3w6).

## rev2(current)
![3w6](https://raw.githubusercontent.com/weteor/3W6/main/images/3w6_rev2_1s.jpg) 
![3w6](https://raw.githubusercontent.com/weteor/3W6/main/images/3w6_rev2_2s.jpg) 
## rev1
![3w6](https://raw.githubusercontent.com/weteor/3W6/main/images/3w6_1s.jpg) 
![3w6](https://raw.githubusercontent.com/weteor/3W6/main/images/3w6_2s.jpg)
![3w6](https://raw.githubusercontent.com/weteor/3W6/main/images/3w6_3s.jpg)
