# OpenSlab
flexible and rugged open source low profile leverless controller 

Openslab is an attempt to bridge the gap between the modability of traditional fight sticks and the form factor of PCB based leverless designs.



Plexi build hardware needed/electronics needed
-----------
10 x 15mm m3 standoff
30 x 8mm flat head m3 hex 
14 x m3 nut
8 x 16mm cup head m3 hex
30 cm panel mount USB-B to 5 pin dupont or USB Type C 3.1Panel Mount Adapter Cable
Choice of low profile buttons
.96 inch Display
gpio Button Module Push Button Board
RP2040

Full 3d Print build hardware/electronics needed
-----------
12 x 15mm m3 standoff
34 x 8mm flat head m3 hex 
10 x m3 nut
8 x 16mm cup head m3 hex
30 cm panel mount USB-B to 5 pin dupont or USB Type C 3.1Panel Mount Adapter Cable
Choice of low profile buttons
.96 inch Display
gpio Button Module Push Button Board
RP2040




Electronics links
-----------
0.96 Inch OLED Module 12864 128x64 Yellow Blue SSD1306 Driver I2C Serial Self-Luminous Display Board - https://www.amazon.com/gp/product/B072Q2X2LL?ie=UTF8&psc=1 (You can probabkly find other colors, tollerances may vary this is just what I prototyped with)
Button Array Button Module Electronic Components gpio Button Module Push Button Board - https://www.amazon.com/gp/product/B0C9P8H3YZ?ie=UTF8&psc=1
Panel Mount USB 2.0 B Cable USB B Female to 5 pin Female Dupont Motherboard USB Header Cable - https://www.amazon.com/gp/product/B07DNN94JD?ie=UTF8&psc=1
USB Type C 3.1Panel Mount Adapter Cable USB-C 3.1 Gen2 10Gbps Male to USB C Female Panel Mount Screw Cable - https://www.amazon.com/gp/product/B0CCRXF1N7?ie=UTF8&psc=1
RP2040 Advanced breakout board (If you can't find one of these from a small business, what are you doing here?)
Low Profile Arcade/fightstick Buttons (Tested with Monkey Butts and Sitongs) 

Hardware links (Please note, that I used brass, you can use alternatives)
-----------
15mm m3 standoff - https://www.amazon.com/gp/product/B07H9VJ29Q?ie=UTF8&psc=1
8mm flat head m3 hex - https://www.amazon.com/gp/product/B0BP6B8CRD?ie=UTF8&th=1
m3 nut
16mm cup head m3 hex - https://www.amazon.com/gp/product/B0C7BYKWZF?ie=UTF8&th=1





Print Instructions
-----------
Frame Common Files - Mandatory files regardless of layout or plate materials. There are options for both USB C and B top walls here, and the corners are mirrored, allowing you to swap them around and put a shoulder strap or lanyard on any side, or just print 2 copies of the bottom corners if you don't want the mount points. Also note that there are arrows on the inside of all of the frame wall pieces. these should print facing up, because the top face is slightly thicker  than the bottom (4mm top, 3mm bottom) Also included is a cable cover to tidy up some wiring.

3d print plates common files - this is a collection of print files needed for a fully 3d printed leveless fight stick, that include the center brace (not part of the walls section because it's not used in acrylic builds), the assemblies f to house electronic components (gpio and display), the buttons for the GPIO which will need you to print 4 copies, and the 2 bottom panels

Fauxlix, Fauxir, Fega p2, 6 god , and 6 ERGOd top panels - A collection of layouts that will house your arcade buttons and RP2040. these are just Viewlix, Noir, Sega p2, 6 Gawd, and 6 ERGOd(my personal ergo 6 gawd format) scaled down to use primarily 24mm buttons and will use 30mm as thumb buttons. 

Plates - Cut acrylic/steel Ergod (UNTESTED) - This are just files for acrylic and steel cut parts for the tops and bottom of the fight stick, please note that this includes some 3d printed parts because the electronics housings and RP2040 mount are different. 




Construction process
-------------
- Build Frame
- Mount top face
- Flip upside and down insert buttons, put electronics in housings and then slot them into the top face plate (they press fit between the top and bottom faces), wire everything, add RP mount lid (cable cover)
- mount bottom plate
- set up/config RP2040
- Plug in
- enjoy?
- Give feedback (Optional)


