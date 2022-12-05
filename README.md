# BETA_Pestle_Rotational_Bowden
Flexible bowden system designed to fit almost anywhere, while providing rotational movement to support even shorter bowden assemblies.


![Bowden](https://github.com/Alchemical-3D/BETA_Pestle_Rotational_Bowden/blob/main/PESTLE_IMAGES_V7/Pestle4.png)

# Join the community discussion, get assistance, or even show off your mods!  
# DISCORD: https://discord.gg/aE49DW2xXe

-----------------------------------------------------------------------------------------------------------------------------------------------------------

!!!!  PLEASE READ THESE NOTES PRIOR TO CONTINUING WITH YOUR BUILD !!!!

>A)  This assembly comes in relatively close conditions to a heated bed and stepper motor. We will not support issues due to using materials such as PLA to build this assembly. PLA and similar materials (PETG/PLA/PLA+/ETC) are NOT suitable to build 3D printer parts out of, please do not ask if PLA is ok, it is not. If you are going to use PETG for the build, please keep an eye on the motor mount area and consider reducing current to your motor. Steppers produce heat and PETG (while better than PLA) still has a lower TG point, it could begin melting.

>B)  THIS IS A BETA RELEASE AND NOT THE FINAL PRODUCT, YOU ARE RESPONSIBLE FOR YOUR SAFETY AND EQUIPMENT WHEN BUILDING AND USING THIS SYSTEM AND 
YOU ACCEPT ALL LIABILITY BY USING THESE FILES FROM THIS BETA TO RELEASE CANDIDATES AND POST!

-----------------------------------------------------------------------------------------------------------------------------------------------------------

# PREFACE

This is the Pestle Rotational Bowden, part of the Mortar and Pestle ecosystem.   

The goal of this project is to provide an ultra lightweight but powerful extruder which rides the X gantry (or anywhere else you wish) while also being able to rotate allowing the shortest Bowden tube possible.  The rotation removes the need for additional bend radii to get to the toolhead by providing this more direct route.  Initial testing of this unit showed it was able to achieve a Bowden length approximately <9", when the stock tube was near 20" long, that is an improvement of 50%.  On top of the PTFE length savings, the more direct filament route results in much lower PA values than traditional Bowden, as well as retraction settings which are more in line with Direct Drive.   All of these benefits combined create a system that takes the best from each world without totally sacrificing where the others do most.

The concept for this extruder was inspired by the now defunct Voron Jetpack.  However, we would like to extend a special thanks to the Voron team for their inspiration on this product.  Please take a moment if you are not familiar with the Voron project to educate yourself on the hard work they commit to the makerspace.  https://vorondesign.com/


-----------------------------------------------------------------------------------------------------------------------------------------------------------
![Bowden 2](https://github.com/Alchemical-3D/BETA_Pestle_Rotational_Bowden/blob/main/PESTLE_IMAGES_V7/PestleExploded3.png)

# PRINT SETTINGS

Materials - ABS/ASA (Note: The parts are designed accounting for shrinkage of ASA & ABS, other filament types may or may not work.)

Layer Height - 0.20

Extrusion Width - Forced 0.4m

Infil Percentage - 40%+

Infil Type - Grid, Honeycomb, Triangle, or Cubic

Top/Bottom Wall Count - 5

Perimeter Count - 4

-----------------------------------------------------------------------------------------------------------------------------------------------------------

# B.O.M.  

>NOTE: Alchemical-3D has affiliate status with most of the links below, purchases using these links help continue funding of the project.  If you wish to configure a Pestle kit through a vendor instead of source individual parts, use this link [here](https://kb-3d.com/store/extruders-hotends/731-pestle-rotational-bowden-extruder-kit-beta-12-configurable-1670209967306.html?affp=6182).

>NOTE: This is the bare minimum, it is wise to have spare screws/heatsets etc.

1. QTY - 7 - [M3x5x4 Heatsets](https://kb-3d.com/store/inserts-fasteners-adhesives/278-brass-heat-set-threaded-insert-for-plastic-m3x5x4mm.html?affp=6182) (Be sure to get angled exterior texture, not straight) 
2. QTY - 2 - [Thrust Bearing 5mm ID](https://kb-3d.com/store/magnets-bearings/696-5mm-x-12mm-x-4mm-thrust-bearing-f5-12m-1645908989939.html?affp=6182)|
3. QTY - 1 - M3x16 SHCS (Socket Head Cap Screw)
4. QTY - 1 - M3x20 SHCS (Socket Head Cap Screw)
5. QTY - 2 - M3x30 SHCS (Socket Head Cap Screw)
6. QTY - 2 - M3x35 SHCS (Socket Head Cap Screw)
7. QTY - 1 - M5x16 SHCS (Socket Head Cap Screw)
8. QTY - 1 - M5 Hex Nut
9. QTY - 3 - [PC4-M6 Bowden Connector](https://kb-3d.com/store/inserts-fasteners-adhesives/707-push-fit-embedded-bowden-fitting-coupler-175-ecas04-1667064368065.html?affp=6182)
10.  QTY - 1| - [BondTech BMG Extruder Internals Kit](https://kb-3d.com/store/bondtech/484-bondtech-bmg-extruder-internals-kit-build-your-own-1645151327973.html?affp=6182) (Some clones have the correct components for this build internally)
11. QTY- 1 - [Nema 14 High Temp Stepper Motor](https://kb-3d.com/store/stepper-motors/460-ldo-nema-14-high-temp-stepper-motor-36sth20-1004ahg-1640706867164.html?affp=6182)

Highly Recommended Items Below but optional.

12. QTY - 1 - Threadlocker (Loctite Blue or similar strength, its important to note that threadlockers WILL damage ASA/ABS if they come in contact, take care when applying thread lockers that it only gets on the metal assembly.)

-----------------------------------------------------------------------------------------------------------------------------------------------------------


# PESTLE ASSEMBLY

Link below is an interactive 3D View of Pestle assembly for reference. This identifies the location and orientation of each screw, heat-set and part you will require to assemble the pestle extrusion system.  If you have further questions please join the Discord and feel free to ask!

# 3D MODEL: https://collaborate.shapr3d.com/v/v6mYEXV8CYMdK-g0WFfRf
# DISCORD: https://discord.gg/aE49DW2xXe


# PESTLE RETRACTION SETTINGS

>NOTE: These settings are intended as a starting point for makers of the system to begin tuning and do not reflect all system requirements.  Individual system needs vary and your use case may require adjustments.

Retraction Distance - 1.00MM

Retraction Speed - 40MM/S

Detraction Speed - 45MM/S

Estimated Presure Advance - .280


