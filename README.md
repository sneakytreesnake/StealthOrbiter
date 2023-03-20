# StealthOrbiter
This mod aims to mount the Orbiter V2.0 extruder to the Voron Stealthburner & [crowncooler](https://github.com/sneakytreesnake/CrownCooler) assembly.

<img width="400" alt="Screen Shot 2022-06-23 at 6 24 17 PM" src="https://user-images.githubusercontent.com/12782053/175235852-639f6085-0307-48b9-b661-db9fc88dab96.png">

# Features
- It is fully compatible with the rest of the stealthburner system of hot ends & shrouds. A slightly modified (and optional!) version of the stealthburner fan shroud has been included to allow access to the orbiter filament lever.
- Compatible with the [Crown Cooler system.](https://github.com/sneakytreesnake/CrownCooler)
- Has a straight filament path. 
- Has an integrated filament sensor beneath the extruder for ERCF. Note that a filament sensor is not explicitly required anymore, but has been kept for legacy reasons.
- Works with cable chains or canbus boards
- Has a hinge feature integrated into the mount, to attach an aesthetic stealthburner shroud.

There are three optional versions to choose from:
- Standard - just a basic orbiter V2.0 mount
- A filament sensor located between the orbiter and the hot end, for use with the ERCF (note that the sensorless branch of the ERCF software no longer requires a sensor)
- A mount for a PG7 cable gland, for using umbilical cords


# Gallery!

Installed onto a standard stealthburner assembly:

<img width="751" alt="Screen Shot 2022-06-23 at 6 24 17 PM" src="https://user-images.githubusercontent.com/12782053/175235852-639f6085-0307-48b9-b661-db9fc88dab96.png">


<img width="832" alt="Screen Shot 2022-06-23 at 6 24 35 PM" src="https://user-images.githubusercontent.com/12782053/175235972-42aaa4e3-cacb-48ac-af07-f9b71dd27c3c.png">


<img width="568" alt="Screen Shot 2022-06-23 at 6 24 07 PM" src="https://user-images.githubusercontent.com/12782053/175235991-af587cd0-a2b5-4694-8a7a-3bd9b6be72e8.png">


Filament path and design (for the filament sensor version):


<img width="568" alt="Screen Shot 2022-06-23 at 6 24 07 PM" src="https://user-images.githubusercontent.com/12782053/216584788-3b26bd3a-42d3-4c24-a112-3d7fa7cbf35e.png">

<img width="568" alt="Screen Shot 2022-06-23 at 6 24 07 PM" src="https://user-images.githubusercontent.com/12782053/216584854-cdd54845-505c-4beb-8d27-d2f70cbc70f3.png">

<img width="568" alt="Screen Shot 2022-06-23 at 6 24 07 PM" src="https://user-images.githubusercontent.com/12782053/216584861-3ea8045e-b1ba-4026-b1cf-616be6b1c0ef.png">

<img width="568" alt="Screen Shot 2022-06-23 at 6 24 07 PM" src="https://user-images.githubusercontent.com/12782053/216584873-6afd6aa8-d75a-4db6-a823-0fa14b1ef3f6.png">


# Development Roadmap
1) [COMPLETE] Initial release!

2) [COMPELTE] Add ERCF filament sensor version

3) [COMPLETE] Add PG7 cable gland mount version


# Installation
1) Print orbiter mount. Though optional, I recommend printing the stealthburner fanshroud.
2) Decide wiring method. Print associated parts

[Canbus Boards](https://github.com/KayosMaker/CANboard_Mounts)

[Cable Chain](https://www.teamfdm.com/files/file/485-orbiter-2-clockwork-beta/)

3) Print the mount with the front face on the bed (so the hold for the ball bearing is printed vertically). Use standard Voron print settings.

4) If you are using the filament sensor feature, add 6mm ball bearing and install Omron D2FL endstop switch using self tapping screws. The ball bearing should drop freely into the hole with no friction. Wire this switch as a standard filament switch.

# BOM
- 6mm stainless steel ball bearing
- Omron D2FL microswitch


# Acknowledgments
- spacelab_2021, for providing the starting point I used in developing this mod
