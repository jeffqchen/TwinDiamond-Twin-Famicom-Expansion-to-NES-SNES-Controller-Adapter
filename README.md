# twindiamond

TwinDiamond - Twin Famicom Expansion A to NES/SNES Controller Adapter

This is an adapter for the Nintendo Twin Famicom expansion port A. It is compatible with NES and SNES controllers, plus the NES Zapper lightgun with the 2P NES port.

===Printing===  
Print everything facing up is a good choice. There really isn't much to it.

The front jacket obviously needs supports.

The plug part might appear split if your line width is set too big. Try 0.35mm and enable "print thin walls" in your slicer. Don't use supports on the the plug. Make sure you don't have too much over-extrusion for the bottom layers as it may clog the holes for the pins. Try an NES plug with the plug part. If they don't go in, clear the NES port holes with a 9/64" drill bit, usually only around the orifice.

The back part doesn't need support either.

===PCB===  
This design requires a PCB to be ordered:
https://oshpark.com/shared_projects/1aCic7tG

Gerber ZIP is attached.

===PARTS===  
The pins used in the project can be purchased from Digikey.

#Pins on the front:
Quantity: 22 or 28
Part No.: ED1183-ND
Name: CONN PC PIN CIRC 0.040DIA GOLD by Mill-Max Manufacturing Corp.

#Pins on the back:
Quantity: 9 or 15
Part No.:88SE-ND or 89SE-ND
Name: CONN D-SUB SOCKET 20-26AWG CRIMP

Required pins are:
Male:
5 for all the SNES ones, 5 for 1P NES, 7 for 2P NES. Detailed pinout shown in one of the photos above.

Female:
9 for pin 1, 4, 5, 7, 9, 12, 13, 14, 15

Note you don't have to populate all the pins, but it makes it look better.

Screw and nut used is Hex M2 16mm (full length 17.8mm). This can be purchased from Amazon as a kit.

===Assembly===  
Soldering is not too hard but requires attention. You may want to plug in a controller into the printed plug first, insert the pins in from the back of the printed piece, one port at a time, then fit the PCB over the stumps and solder. Use just enough amount of the solder. Make sure nothing protrudes too much up from the surface.

Repeat the same thing for the back female pins. Fit the 9 pins inside the back piece and then solder them in with small amount of solder.

===Misc===  
Thingiverse Page:  
https://www.thingiverse.com/thing:4882800

===Special Thanks===  
Chris Kempson:  
http://chriskempson.com/posts/nes-controller-to-famicom-adapter/

NesDev Wiki:  
https://wiki.nesdev.com  

Mike Chi (creator of the very famous RetroTink)  
https://www.retrotink.com
