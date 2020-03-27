Ender 5 Configurations
======================

>Repository for backing up and sharing the source and slicer profiles of Ender 5.

Hardware Specifications
----------------------
>All printed parts were printed by self.
* CREALITY Silent 1.1.5 Mainboard(embedded TMC2208)
* MK8 extruder(because my vanila extruder is broken...)
* Exoslide Ender 5 XY Kit(https://exoslide.com/products/kits/ender5-XY)
  * Only using X Gantry
* BLTouch v3.0(with PIN 27 board)
* Dual Z Axis(with stepper motor parallel module, https://www.thingiverse.com/thing:3784970)
* Hero Me Gen 3 with dual 5015 blower fans(https://www.thingiverse.com/thing:3182917)

Slicer
----------

*Simplify3D v4.1.2*  
*PrusaSlicer v2.1.1*  
*Cura v4.5.0*  

Updated
---------

    2020-01-30 
        - Change direct drive to bowden. because printed motor mount parts are melted...
        - Update S3D profile(direct -> bowden).
    
    2020-02-10
        - Add PrusaSlicer profile.
        - Add Smart-Plug and OctoPrint for remote control(No Raspberry-Pi, using OMV-NAS)
            * Smart-Plug: http://bitly.kr/DSLtJszO

    2020-03-27
        - Add Cura profile.
        - Remove Exoslide Y-Gantry(Bearing tread was broken).