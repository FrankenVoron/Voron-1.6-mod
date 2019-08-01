# Voron-1.6-mod
It's the Voron V1.6, but better! Now with linear rails for XY and a fully enclosable design.

This github page is being updated and developed. Please note that all of these STLs are derived from the Voron Design V1.6 and V2.1 printers--any mods present in this folder are small changes to the existing Voron Design STLs to support changing the linear rods of V1.6 to linear MGN9H rails similar to how V2.1's gantry is.

This mod is fully unsupported by the Voron Design team, support and discussion will be in a separate Discord group, link to be populated in the future.

Default size is 300x300x340mm, reducing it down to 250mm saves only about $25. 340mm is due to lack of availability of 360mm linear steppers.

Total BOM cost is around $750-800, which sits it between the Hypercube ($550) and the Railcore II 300ZL ($1300). 

Advantages over the HEVO:
    
    -Cast aluminum bed (vs. PCB bed) -> much flatter, consistent bed surface
    -Linear rails for XY (vs. linear rods) -> less sag
    -AC heated bed (lower current to the bed, less load on the 24V power supply, quieter)
    -SKR 1.3 board with silent TMC2209 drivers vs. RAMPS board and loud A4988 drivers
    -Integrated Octoprint remote web control through Raspberry Pi
    -True 32 bit board with Klipper control
    -Mobius 3 extruder with Bondtech gears vs. Titan extruder (higher torque, grabs filament from both sides)
    -Enclosed build volume

Advantages over the Railcore:
    
    -Significantly cheaper
    -Easily enclosable
    -No risk of catching hands or tools on CoreXY belts

[V1.6 Mod BOM Link (In Process, NOT FINAL)](https://docs.google.com/spreadsheets/d/1ig14b1j8-F_122QWTeGj5dSmB8Jl30DImUAANSiHRPc/edit?usp=sharing)

[V1.6 Mod Fusion 360 Assembly (300^3)](https://a360.co/2MlttV1) <- will be updated to 300x300x340mm

![V1.6 Mod](https://i.imgur.com/REc2A0J.png)
