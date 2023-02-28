# Ender 3/Pro/V2

============================================
BUILD STATUS: Stopped at 2.5 with RPI, PEI Spring Steel Sheet Textured+Smooth, and MicroSwiss.
============================================


<pre>
This is a documentation of my Ender 3/Pro Documentary of my printer build. 
This setup is repeatable. Good for print farms. I have this on 3 of my E3 (2xE3Pros, 1xRegularE3)

Tools To be used:
-Tire Gauge for Alignment
-Grease
-X Gantry Alignment tool
-6/7/8/10 wrench
-Nozzle Wrench or BTT Crab Nozzle Change tool

V1: Base Ender 3/Pro (Out of the Box Upgrades)
-Capricorn PTFE Tube
-X axis Tensioner
-Y Axis Tensioner
-Yellow Stiffer Bed Springs
-Metal Extruder
-X Gantry Alignment Tool (or use 2 objects of same type if you cannot print yet) : https://www.thingiverse.com/thing:4376394
-Tire Gauge E3 Calibration Kit : https://www.thingiverse.com/thing:4582774
-White/Black Pentel for (Dark/Light filaments) for eStep tuning and flow rate tuning

V1.1: Printable part Must haves during Build process (The earlier you get this the Better)
-Vslot Covers Snap on for Extrusion rails : https://www.thingiverse.com/thing:4866310
-Double V Slot Corner Bracket : https://www.thingiverse.com/thing:2763033
-Z Stepper Support : https://www.thingiverse.com/thing:4699747
-Cable Protector: https://www.thingiverse.com/thing:3322027
-LCD Full case cover : https://www.thingiverse.com/thing:3014209/makes
-LCD ribbon cable guide clip : https://www.thingiverse.com/thing:2960375
-PSU Support: https://www.thingiverse.com/thing:3927972
-Better Spool Holder : https://www.thingiverse.com/thing:3020026
-Nozzle Tool Wrench : https://www.thingiverse.com/thing:4738816

V1.5: Aesthethics and Organiztion
-X Axis Tensioner Cover e3 Pro: https://www.thingiverse.com/thing:4799007
-SD Card Extender : https://www.thingiverse.com/thing:3537808
-Handle Bar https://www.thingiverse.com/thing:1290106
-Cable Chains (Unnecesary but makes your printer looks clean) : https://www.thingiverse.com/thing:4316238
-LED Bar(soldering/wiring required) https://www.thingiverse.com/thing:3292889
-Nozzle Wiper : https://www.thingiverse.com/thing:4747447

V2.0: Performance Upgrades with printed Parts
-Printed Direct Drive with stock parts: https://www.thingiverse.com/thing:3443609 or straight to 
Hydra V5 for Bowden and 1x 4010 24V Part cooling fan set up : https://www.thingiverse.com/thing:4062242
-Stepper Cable Support : https://www.thingiverse.com/thing:4279827

========================================================================================
FREE/Minimal UPGRADES End
========================================================================================
Final v2.0 BOM: 
-Capricorn PTFE Tube
-X axis Tensioner
-Y Axis Tensioner
-Yellow Stiffer Bed Springs
-Metal Extruder
-Tire Gauge
-Ballpen Spring
-2 608 Bearings
-SD Card Extender
-2pcs M3 screw and T-nut
-24v LED
-8 x 2mm neodymium 
-30mm Socket adapter
-6/7 socket wrench
-Brass Brush
*Add v5 hydra if you went that route

========================================================================================
Good place to STOP, this is where the additional expense comes in.
========================================================================================
*V5 Hydra Parts:
- M3 x 12 mm Pan Head hex bolts 4x
- M3 X 8mm Pan Head hex bolts 3x
- M3 X 16mm Pan Head hex bolts 6x
- M3 X 20mm Pan Head hex bolts 3x
- M3 X Nylok Nuts 12x
- M3 X Plain Nuts 3x

*V6 Hydra Additional Parts:
- M3 x 20mm Hex Bolts and M3 Nylocs 2x : for Heat Sink 
- M3 x 12mm Hex bolts and Nylocs 2x : for V6 Clamp to the Duct Base.
- M3 x 10 mm long Nylocs 2x : for BL Touch


Version 2.5: Performance Parts, Better cooling
-E3 Pro rear PSU Mod (only print left part): https://www.thingiverse.com/thing:4101358
-E3 Pro rear PSU Mod (Better right part): https://www.thingiverse.com/thing:4461049
-E3 (Non Pro) rear PSU Mod: https://www.thingiverse.com/thing:5303395
-PSU Fan Cover: https://www.thingiverse.com/thing:4460994
-5015 24v Sunon/GDSTime Fan Upgrade 2x: Part Cooling
-4010 24v Sunon/GDSTime Fan Upgrade 1x: Hot End
-Hydra Hotend Version6 Setup : https://www.thingiverse.com/thing:4253359/


========================================================================================
Good place to STOP again. Currently a best bang for your buck set up!
At this stage you can print PETG on open air with no problem
========================================================================================

Version 3.0: More parts more money
-HotBed: PEI Spring sheet from Whambam or BuildTak is good or any that has textured and smooth
-Dual Z mod: https://www.amazon.com/BIGTREETECH-Upgrade-Stepper-Upgrades-Printer/dp/B09DS6TQJY
-BMG Extruder:  check https://www.bondtech.se/product/bmg-extruder/ or authorized resellers
-Hotend: Micro Swiss All Metal MK8 hotend https://store.micro-swiss.com/collections/all-metal-hotend-kits
-Nozzle: Ruby/Tungsten Carbide/Diamond Tip Nozzle to print anything https://www.amazon.com/Temperature-Markerbot-Creality-Printer-Carbide/dp/B07Q23K51X
-Z Probe: BL Touch by ANTCLABS https://www.antclabs.com/
-Linear rails: Upgrade Guide https://www.youtube.com/watch?v=I3xMHjiYENk&
-Mother Board: BigTreeTech SKR mini E3 v3 (if in a budget SKR mini E3 v1.2 is enough)
-Raspberry Pi: RPi3b+ or later versions for Klipper or Octoprint for remote access printing
-Ikea Lack Enclosure Mod: https://www.thingiverse.com/thing:3534066
-Air filter Mod (HEPA+Carbon Filter) https://www.thingiverse.com/thing:3374299

02/27/2023 - After 2 years my first E3 Pro Board gave out. It seems that the Extruder motor is skipping even without load and higher Vref. Extruder driver may be failing. Time to upgrade the mother board. 
While Waiting for an SKR mini E3 v3 i have used my SKR mini E3 v1.2.
Will upgrade extruder Motors to BMG
Will add BLTouch
Will Upgrade to Hydra v6

Version 4.0:
-SwitchWire Conversion https://github.com/boubounokefalos/Ender_SW
</pre>
