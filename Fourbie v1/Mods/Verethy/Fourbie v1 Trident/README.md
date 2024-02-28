# Fourbie v1

Fourbie is a collection of mods aimed at increasing the performance of the Voron 2.4/Trident. 
In short it's an AWD system with a VZBot style toolhead. The X rail mounts on top of the X member and the toolhead is balanced over the top. Belts terminate on the front on one end and the rear on the other. This leads to a more balanced gantry than the stock voron allowing for increased performance. A front extrusion is added to support the front AB drives. There is support for CF tubes and extrusions. It also supports the use of a single MGN9 or MGN12.

![Trident1](https://i.imgur.com/KYcPzZA.png)

![Trident2](https://i.imgur.com/6nFsEiv.png)

The primary components of the MOD are 
* Front AB drives for AWD Support
* Rear AB drives with integrated Tensioners
* XY Joints

STL's are in this repository

These are all designed to be used together, however they could be used in a number of other configurations
Possible configurations include:

    * AWD with all of the mods and VZ printhead style toolheads.
    
    * AWD with using the front and rear AB drives from this mod, Redoubt XY Joints and Voron style toolheads. 
    
    * 2WD using the XY Joints and rear AB from this mod, Redoubt front idlers and VZ Printhead style toolheads.
    

The standard configuration is all of the above mods together. This is what is tested. All other potential configurations are untested. 
Note that this is an advanced mod. There is no build documentation. Bom will not be comprehensive. It is expected that you will inspect the CAD and do the work to figure out what you need to install it. 

Due to the number of idlers, you need to build to spec and take your time to make sure everything is properly built and aligned, front to back. Failure to do this will lead to your fourbie eating all of your belts. Nom. Also before printing make sure that you have properly tuned your filament and that it is producing dimensionally accurate parts. This MOD has been designed with very tight tolerances and improper calibration will lead to problems. 


## Recommended configuration

* MGN9 for X rail.
* CF Tube for X rail
* Front AB drives with extrusion

An NF Crazy or Mosquito is recommended to minimise loss of Y. With an NF crazy there is no loss of X and about 25mm loss on Y. Given that most people generally  do not print in the outer 1cm of the bed on Voron this is very little real world loss of build volume. 
We are looking at options for BerdAir to reduce loss of build volume down to the minimum. 


## BOM

For the front drive mounts you need:
2x 2GT toothed idlers (3mm bore)
4x 2GT smooth idlers (3mm bore)
12x M3x5x0.5mm shims

## Tools

Tools are to used to adapt [Unique Prints](https://uniqueprints.shop/) Carbon Fibre gantry to MGN9.
If unsure check the CAD.

## Credit/Attribution
Credit goes to the Voron team for they great work creating the Voron 2.4 https://vorondesign.com/voron2.4
Annex Engineering that inspired some elements of the rear AB drives.  https://github.com/Annex-Engineering/Redoubt
Aive from the Makerbogans discord who's work on an AWD drive system for voron 2.4 defined the belt path for the front AB drives. 
The VZBot team for the VZ printhead - which made developing this mod much faster and also allows for the the use of many more toolhead configurations than we would have provided support for otherwise. https://github.com/VzBoT3D/Vz-Printhead-Printed
Thanks to Vez for giving permission to include the printhead in the CAD. 



