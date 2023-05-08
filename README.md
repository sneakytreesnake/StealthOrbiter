# StealthOrbiter
This mod aims to mount the Orbiter V2.0 extruder to the Voron Stealthburner & [crowncooler](https://github.com/sneakytreesnake/CrownCooler) assembly.

<img width="400" alt="Screen Shot 2022-06-23 at 6 24 17 PM" src="https://user-images.githubusercontent.com/12782053/175235852-639f6085-0307-48b9-b661-db9fc88dab96.png">

# Features
- It is fully compatible with the rest of the stealthburner system of hot ends & shrouds. A slightly modified version of the stealthburner fan shroud has been included to allow access to the orbiter filament lever.
- Compatible with the [Crown Cooler system.](https://github.com/sneakytreesnake/CrownCooler)
- Has a straight filament path. 
- Has an integrated filament sensor beneath the extruder for ERCF. Note that a filament sensor is not explicitly required anymore, but has been kept for legacy reasons.
- Works with cable chains or canbus boards
- Has a hinge feature integrated into the mount, to attach an aesthetic stealthburner shroud.

# Gallery

## Versions

| Standard Canbus  | PG7 Canbus | Cable Chain |
| ------------- | ------------- | ------------- |
| <img height="300" alt="Screen Shot 2022-06-23 at 6 24 17 PM" src="https://user-images.githubusercontent.com/12782053/229245967-7c72f1e2-2ce0-4fe2-96df-a6bb5ba10429.png">  |  <img height="300" alt="Screen Shot 2022-06-23 at 6 24 17 PM" src="https://user-images.githubusercontent.com/12782053/229247959-782a5b35-3315-48fa-8873-b30b1c99f6f5.png">  |  <img height="300" alt="Screen Shot 2022-06-23 at 6 24 17 PM" src="https://user-images.githubusercontent.com/12782053/229246036-2fa6f829-6d63-4000-8e99-8779a522f7c4.png">  |
| Standard Mount | PG7 Cable Gland Mount | Standard Mount |

There is a variation of the standard mount to incorporate a filament sensor below the extruder. See below.
## Stealthburner Build

<img height="300" alt="Screen Shot 2022-06-23 at 6 24 35 PM" src="https://user-images.githubusercontent.com/12782053/175235972-42aaa4e3-cacb-48ac-af07-f9b71dd27c3c.png"> <img height="300" alt="Screen Shot 2022-06-23 at 6 24 17 PM" src="https://user-images.githubusercontent.com/12782053/175235852-639f6085-0307-48b9-b661-db9fc88dab96.png"> 

## Crowncooler Build

<img height="400" alt="Screen Shot 2022-06-23 at 6 24 35 PM" src="https://user-images.githubusercontent.com/12782053/229251964-5e48cb4f-470e-4ca3-bbf6-d69447973440.png">

## Filament sensor (for the filament sensor version):

There are a few inherent issues with the sensored mount so I do not recommend them. I highly recommend using the sensorless mounts instead, along with the Happy Hare ERCF software. 

If that answer doesn't satisfy you, there are a number of issues with the sensored mounts:
- requires supports
- sensor breaks the PTFE tube into two
- needs a pretty well calibrated printer to get the tolerance on the ball bearing hole right
- is actually LESS reliable than the sensorless version, as filament shavings from the extruder can work its way down into the ball bearing cavity, which jams it open
- eventually the filament rubbing on the hole around the ball bearing starts to wear through it and enlarge it

<img width="600" alt="Screen Shot 2022-06-23 at 6 24 07 PM" src="https://user-images.githubusercontent.com/12782053/216584788-3b26bd3a-42d3-4c24-a112-3d7fa7cbf35e.png">

<img height="200" alt="Screen Shot 2022-06-23 at 6 24 07 PM" src="https://user-images.githubusercontent.com/12782053/216584854-cdd54845-505c-4beb-8d27-d2f70cbc70f3.png"> <img height="200" alt="Screen Shot 2022-06-23 at 6 24 07 PM" src="https://user-images.githubusercontent.com/12782053/216584861-3ea8045e-b1ba-4026-b1cf-616be6b1c0ef.png"> <img height="200" alt="Screen Shot 2022-06-23 at 6 24 07 PM" src="https://user-images.githubusercontent.com/12782053/216584873-6afd6aa8-d75a-4db6-a823-0fa14b1ef3f6.png">


# Development Roadmap
1) [COMPLETE] Initial release!
2) [COMPELTE] Add ERCF filament sensor version
3) [COMPLETE] Add PG7 cable gland mount version
4) [COMPLETE] Assembly instructions


# Installation & BOM
 
 [Instructions are here.](https://github.com/sneakytreesnake/StealthOrbiter/tree/main/STL)


# Acknowledgments
- spacelab_2021, for providing the starting point I used in developing this mod
- KayosMaker, modified parts to make the canbus mounts
