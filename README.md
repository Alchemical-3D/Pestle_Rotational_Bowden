# BETA_Pestle_Rotational_Bowden
### The flexible bowden system designed to fit almost anywhere, while providing rotational movement to support even shorter bowden assemblies.


![Bowden](https://github.com/Alchemical-3D/BETA_Pestle_Rotational_Bowden/blob/main/images/Pestle4.png)

#### Join the community discussion, get assistance, or even show off your mods!
#### DISCORD: https://discord.gg/aE49DW2xXe

-----------------------------------------------------------------------------------------------------------------------------------------------------------

#### !  PLEASE READ THESE NOTES PRIOR TO CONTINUING WITH YOUR BUILD !

>A) This assembly comes in relatively close conditions to a heated bed and stepper motor. We will not support issues due to using materials such as PLA to build this assembly. PLA and similar materials (PETG/PLA/PLA+/ETC) are NOT suitable to build 3D printer parts out of, please do not ask if PLA is ok, it is not. If you are going to use PETG for the build, please keep an eye on the motor mount area and consider reducing current to your motor. Steppers produce heat and PETG (while better than PLA) still has a lower TG point, it could begin melting.

>B) THIS IS A BETA RELEASE AND NOT THE FINAL PRODUCT, YOU ARE RESPONSIBLE FOR YOUR SAFETY AND EQUIPMENT WHEN BUILDING AND USING THIS SYSTEM AND
YOU ACCEPT ALL LIABILITY BY USING THESE FILES FROM THIS BETA TO RELEASE CANDIDATES AND POST!

-----------------------------------------------------------------------------------------------------------------------------------------------------------

### PREFACE

This is the Pestle Rotational Bowden, part of the Mortar and Pestle ecosystem.

The goal of this project is to provide an ultra lightweight but powerful extruder which rides the X gantry (or anywhere else you wish) while also being able to rotate allowing the shortest Bowden tube possible. The rotation removes the need for additional bend radii to get to the toolhead by providing this more direct route. Initial testing of this unit showed it was able to achieve a Bowden length approximately <9", when the stock tube was near 20" long, that is an improvement of 50%. On top of the PTFE length savings, the more direct filament route results in much lower PA values than traditional Bowden, as well as retraction settings which are more in line with Direct Drive. All of these benefits combined create a system that takes the best from each world without totally sacrificing where the others do most.

The concept for this extruder was inspired by the now defunct Voron Jetpack. However, we would like to extend a special thanks to the Voron team for their inspiration on this product. Please take a moment if you are not familiar with the Voron project to educate yourself on the hard work they commit to the makerspace. https://vorondesign.com/


-----------------------------------------------------------------------------------------------------------------------------------------------------------

![Bowden 2](https://github.com/Alchemical-3D/BETA_Pestle_Rotational_Bowden/blob/main/images/PestleExploded3.png)

-------------------------------------------------------------------------------------------------------------------

### PRINT SETTINGS

| Setting | Value |
|:---: |:----:|
|Materials | ABS/ASA (Note: Parts account for shrinkage of ASA & ABS) |
|Layer Height | 0.20 |
|Extrusion Width | Forced 0.4m |
|Infil Percentage | 40%+ |
|Infil Type | Grid, Honeycomb, Triangle, or Cubic |
|Top/Bottom Wall Count | 5 |
|Perimeter Count | 4 |

-----------------------------------------------------------------------------------------------------------------------------------------------------------

### BOM

>NOTE: Alchemical-3D has affiliate status with most of the links below, purchases using these links help continue funding of the project. If you wish to configure a Pestle kit through a vendor (KB-3D) instead of source individual parts, use this link [here](https://kb-3d.com/store/extruders-hotends/731-pestle-rotational-bowden-extruder-kit-beta-12-configurable-1670209967306.html?affp=6182).

>NOTE: This is the bare minimum, it is wise to have spare screws/heatsets etc.

| QTY:| Material: | Notes: |
| :---: |:---:| :---:|
| 7 | [M3x5x4 Heatsets](https://kb-3d.com/store/inserts-fasteners-adhesives/278-brass-heat-set-threaded-insert-for-plastic-m3x5x4mm.html?affp=6182) | (Angled exterior texture, not straight) |
| 2 | [Thrust Bearing](https://kb-3d.com/store/magnets-bearings/696-5mm-x-12mm-x-4mm-thrust-bearing-f5-12m-1645908989939.html?affp=6182)      |  5mm ID X 12mm OD  |
| 1 | M3x16mm SHCS  |    (Socket Head Cap Screw) |
| 1 | M3x20mm SHCS  | (Socket Head Cap Screw) |
| 2 | M3x30mm SHCS  |   (Socket Head Cap Screw) |
| 2 | M3x35mm SHCS  | (Socket Head Cap Screw) |
| 1 | M5x16mm SHCS  |   (Socket Head Cap Screw) |
| 1 | M5 Hex Nut    |   Standard M5 Hex Nut |
| 3 | [PC4-M6 Connector](https://kb-3d.com/store/inserts-fasteners-adhesives/707-push-fit-embedded-bowden-fitting-coupler-175-ecas04-1667064368065.html?affp=6182) | Pnuematic Bowden Fitting |
| 1 | [BondTech BMG Internals Kit](https://kb-3d.com/store/bondtech/484-bondtech-bmg-extruder-internals-kit-build-your-own-1645151327973.html?affp=6182)       |   (Clones acceptable) |
| 1 | [Nema 14 High Temp Stepper Motor](https://kb-3d.com/store/stepper-motors/460-ldo-nema-14-high-temp-stepper-motor-36sth20-1004ahg-1640706867164.html?affp=6182)      |   Pancake Stepper - Round |
| 1 | Threadlocker | Recommended Optional |

>Threadlocker (Loctite Blue or similar strength, its important to note that threadlockers WILL damage ASA/ABS if they come in contact, take care when applying thread lockers that it only gets on the metal assembly.)



-----------------------------------------------------------------------------------------------------------------------------------------------------------


### PESTLE ASSEMBLY
Link below is an interactive 3D View of Pestle assembly for reference. This identifies the location and orientation of each screw, heat-set and part you will require to assemble the pestle extrusion system. If you have further questions please join the Discord and feel free to ask!

#### 3D MODEL: https://collaborate.shapr3d.com/v/v6mYEXV8CYMdK-g0WFfRf

1. - Use interactive model to locate each heatset location in the Pestle Extruder assembly, there should be a total of 6 heat sinks required for assembly.  (3ea) Main Body, (1ea) Lever, and (2ea) Transmission Plate. Heat soldering iron to appropriate temp for filament being used (near printing temp) and slowly press each heatset in squarely. IMPORTANT: The heatset in main body that secures the lever MUST be insterted from the bottom of the body and remain flush with the bottom of the model, if this heatset is inserted from the top it may interfere with lever function.


2. - Use interactive model to locate the (3ea) PC4-M6 locations, (2ea) of these pieces will be added during assembly, the third can be added at any time, when adding the PC6-M4 fitting to the support arm and sure it is being pressed in squarely or the model can split, you may use a wrench or other flat object between the arm braces, place the fitting on a table, and push down on it for easier insertion. Brute force may result in broken parts.

3. - Insert (1ea) MR85ZZ bearing (included in BMG kit) into the Top Plate and Bottom plate of the extruder. A cutout has been made to allow press fit. These parts should be snugly fit but take care when inserting to keep components square as always to reduce risk to model.


4. - Slide (2ea) 5mm OD/3mm ID needle bearing assemblies over (1ea) short 3mm bearing steel rod, and (1ea) secondary BMG drive gear over top of needle bearings. Snap gear assembly into printed part Lever housing.


5. - Insert (1ea) thumbscrew spring (included in BMG kit, set aside thumbscrew) into the inside of the main body. A penetration has been made to house this spring and once the lever is installed it will be secure.


6. - Verify alignment and use the printed part lever to push the spring in as you insert it into the main body of Pestle. Do not bend Pestle main body at lower supports or it may break, use the main body second of the spring to pin the lever in place. Once in place verify the filament path lines up with the teeth on the secondary BMG gear.


7. - Slide (1ea) BMG primary gear of (1ea) BMG 50T 5mm Primary Drive gear and secure grub screw to flat section. A typical installation of the BMG gear is almost all the way down the shaft. And insert back of BMG 50T 5mm Primary Drive gear into the bearing previously installed on transmission plate.


8. - Locate and install the transmission plate, Nema14 stepper, and main body with geared assemblies installed all at once. The Nema 14 stepper will hold the assembly together as project continues, do not worry about setting the stepper adjustments at this point.


9. - Slide top plate and bearing over main body and gear assembly and insert final (2ea) PC4-M6 fittings between top plate and main body. Fittings must be added prior to fastening top plate.


10. - Add M5x16 BHCS to Rotational Cross Brace so that the threads stick out away from the top and posts with (1ea) thrust bearing (or shim washers) in between head of bolt and Rotational Cross Brace printed part.


11. - Add rotational cross brace to top of Pestle extruder fitting the (4ea) posts into the top plate post holes.  Secure pestle rotational brace with (2ea) M3x30mm & (2ea) M3x30mm BHCS.  Screws will pass through entire assembly to transmission plate and main body respectively.


12. - Add (1ea) M5 Nut to respective mount solution and thread pestle assembly through it with (1ea) thrust bearing between the rotational cross brace and the mounting solution.


13. - (Skip step if not using PTFE in this manor) Add PTFE bowden tubing from support arm looping under the extruder and into the bottom of the extruder.  This acts as the reverse bowden guide for filament, take care not to bend at to steep of an angle and kink the PTFE.  If PTFE is kinked and does not allow filament to pass, it should be replaced.


14. - Add PTFE tubing from top of extruder to toolhead assembly, then review Pestle Bowden retraction settings below.


---------

PESTLE RETRACTION SETTINGS
-


| Setting | Value |
| :---: | :---: |
| Retraction Distance | 0.95mm |
| Retraction Speed | 40mm/S |
| Detraction Speed | 45mm/S |
| Estimated Presure Advance | .280 |
| Estimated Presure Advance Smooth Time | .035 |


>NOTE: These settings are intended as a starting point for makers of the system to begin tuning and do not reflect all system requirements.  Individual system needs vary and your use case may require adjustments.

### DISCORD: https://discord.gg/aE49DW2xXe
