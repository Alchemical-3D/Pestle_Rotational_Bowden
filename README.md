<div align="center">

# 🥣 Pestle Rotational Bowden

[![Status](https://img.shields.io/badge/Status-Beta-brightgreen.svg)](#)
[![Drive](https://img.shields.io/badge/Drive-Bowden-blue)](#)
[![Ecosystem](https://img.shields.io/badge/Ecosystem-Alchemical--3D-purple)](#)

*The flexible Bowden system designed to fit almost anywhere, while providing rotational movement to support even shorter Bowden assemblies.*

<p align="center">
  <img src="https://github.com/Alchemical-3D/BETA_Pestle_Rotational_Bowden/raw/main/images/Pestle4.png" width="80%" alt="Bowden" style="border-radius: 12px; box-shadow: 0px 8px 20px rgba(0, 0, 0, 0.4);" />
</p>

**[Join the Discord!](https://discord.gg/aE49DW2xXe)**

</div>

<br>

---

## ⚠️ Important Build Notes

> [!CAUTION]
> **Material Warning**
>
> This assembly comes in relatively close proximity to a heated bed and stepper motor. We will not support issues due to using materials such as PLA to build this assembly. PLA and similar materials (PETG, PLA+, etc.) are **NOT** suitable to build 3D printer parts out of. If you are going to use PETG for the build, please keep an eye on the motor mount area and consider reducing the current to your motor. Steppers produce heat, and PETG (while better than PLA) still has a lower TG point and could begin melting.

> [!WARNING]
> **Builder Responsibility**
>
> This is an aftermarket engineering project. You are solely responsible for your own safety and the integrity of your equipment when building and operating this system. By utilizing these files and instructions, you accept all liability.

---

## 📖 Preface

This is the Pestle Rotational Bowden.

The goal of this project is to provide an ultra-lightweight but powerful extruder which rides the X gantry (or anywhere else you wish) while also being able to rotate, allowing the shortest Bowden tube possible. The rotation removes the need for additional bend radii to get to the toolhead by providing a more direct route. 

Initial testing of this unit showed it was able to achieve a Bowden length of approximately <9", when the stock tube was near 20" long. That is an improvement of 50%. On top of the PTFE length savings, the more direct filament route results in much lower PA values than traditional Bowden setups, as well as retraction settings which are more in line with Direct Drive. All of these benefits combined create a system that takes the best from each world without sacrificing overall performance.

The concept for this extruder was inspired by the now-defunct Voron Jetpack. We would like to extend a special thanks to the Voron team for their inspiration on this product. Please take a moment if you are not familiar with the Voron project to educate yourself on the hard work they commit to the makerspace: [https://vorondesign.com/](https://vorondesign.com/)

---

<p align="center">
  <img src="https://github.com/Alchemical-3D/BETA_Pestle_Rotational_Bowden/raw/main/images/PestleExploded3.png" width="80%" alt="Bowden 2" style="border-radius: 12px; box-shadow: 0px 8px 20px rgba(0, 0, 0, 0.4);" />
</p>

---

## ⚙️ Print Settings

| Setting | Value |
| :--- | :--- |
| **Materials** | ABS/ASA *(Note: Parts account for shrinkage of ASA & ABS)* |
| **Layer Height** | 0.20 mm |
| **Extrusion Width** | Forced 0.4 mm |
| **Infill Percentage** | 40%+ |
| **Infill Type** | Grid, Honeycomb, Triangle, or Cubic |
| **Top/Bottom Wall Count** | 5 |
| **Perimeter Count** | 4 |

---

## 📋 Bill of Materials (BOM)

> [!NOTE]
> **Affiliate Links**
> Alchemical-3D has affiliate status with most of the links below. Purchases using these links help continue funding of the project. If you wish to configure a Pestle kit through a vendor (KB-3D) instead of sourcing individual parts, use this link [here](https://kb-3d.com/store/extruders-hotends/731-pestle-rotational-bowden-extruder-kit-beta-12-configurable-1670209967306.html?affp=6182).
>
> *Note: This list is the bare minimum. It is wise to have spare screws, heat sets, etc.*

| QTY | Material | Notes |
| :---: | :--- | :--- |
| **7** | [M3x5x4 Heatsets](https://kb-3d.com/store/inserts-fasteners-adhesives/278-brass-heat-set-threaded-insert-for-plastic-m3x5x4mm.html?affp=6182) | Angled exterior texture, not straight |
| **2** | [Thrust Bearing](https://kb-3d.com/store/magnets-bearings/696-5mm-x-12mm-x-4mm-thrust-bearing-f5-12m-1645908989939.html?affp=6182) | 5mm ID x 12mm OD |
| **1** | M3x16mm SHCS | Socket Head Cap Screw |
| **1** | M3x20mm SHCS | Socket Head Cap Screw |
| **2** | M3x30mm SHCS | Socket Head Cap Screw |
| **2** | M3x35mm SHCS | Socket Head Cap Screw |
| **1** | M5x16mm SHCS | Socket Head Cap Screw |
| **1** | M5 Hex Nut | Standard M5 Hex Nut |
| **3** | [PC4-M6 Connector](https://kb-3d.com/store/inserts-fasteners-adhesives/707-push-fit-embedded-bowden-fitting-coupler-175-ecas04-1667064368065.html?affp=6182) | Pneumatic Bowden Fitting |
| **1** | [BondTech BMG Internals Kit](https://kb-3d.com/store/bondtech/484-bondtech-bmg-extruder-internals-kit-build-your-own-1645151327973.html?affp=6182) | Clones acceptable |
| **1** | [LDO Nema 14 High Temp Stepper Motor - 9T](https://kb-3d.com/store/stepper-motors-servos/4480-ldo-nema-14-high-temp-stepper-motor-36sth20-1004ahg-9t-for-g2-1640706862009.html?affp=6182) | Pancake Stepper - Round |
| **1** | [Loctite 222MS Threadlocker](https://kb-3d.com/store/tools-equipment/774-loctite-threadlocker-222ms-low-strength-purple-mil-spec-6ml-1673749510419.html?affp=6182) | Recommended Optional |

> [!WARNING]
> If using **Threadlocker** (Loctite Blue or similar strength), please note that these can damage ASA/ABS when coming into contact. Take care when applying threadlockers to ensure they only contact the metal assembly parts.

---

## 🛠️ Assembly Guide

If you have questions regarding the location and orientation of each screw, heat set, and part you will require to assemble the Pestle extrusion system, please join the Discord and feel free to ask!

1. Locate each heat set location in the Pestle Extruder assembly; there should be a total of 6 heat sets required for assembly: (3) Main Body, (1) Lever, and (2) Transmission Plate. Heat your soldering iron to an appropriate temperature for the filament being used (near printing temp) and slowly press each heat set in squarely.
   > [!IMPORTANT]
   > The heat set in the main body that secures the lever **MUST** be inserted from the bottom of the body and remain flush with the bottom of the model. If this heat set is inserted from the top or improperly inserted, it may interfere with the lever's function.

2. Locate the (3) PC4-M6 locations. Two of these pieces will be added during assembly; the third can be added at any time. When adding the PC4-M6 fitting to the support arm, ensure it is being pressed in squarely, or the model can split. You may use a wrench or other flat object between the arm braces—place the fitting on a table and push down on it for easier insertion. Brute force may result in broken parts.

3. Insert (1) MR85ZZ bearing (included in the BMG kit) into the Top Plate and Bottom Plate of the extruder. A cutout has been made to allow a press-fit. These parts should be snug, but take care when inserting to keep components square and reduce the risk of cracking the model.

4. Slide (2) 5mm OD / 3mm ID needle bearing assemblies over (1) short 3mm bearing steel rod, and the secondary BMG drive gear over the top of the needle bearings. Snap the gear assembly into the printed Lever housing.

5. Insert (1) thumbscrew spring (included in the BMG kit; set aside the thumbscrew) into the inside of the main body. A recess has been made to house this spring, and once the lever is installed, it will be secure.

6. Verify alignment and use the printed lever arm to compress the spring as you insert it into the main body of the Pestle. Do not bend the main body at the lower supports, or it may break; use the main body section of the spring to pin the lever in place. Once in place, verify the filament path lines up with the teeth on the secondary BMG gear.

7. Slide the BMG primary gear over the BMG 50T 5mm primary drive gear and secure the grub screw to the flat section. A typical installation of the BMG gear sets it almost all the way down the shaft. Insert the back of the BMG drive gear into the bearing previously installed on the transmission plate.

8. Locate and install the transmission plate, Nema 14 stepper, and main body with the geared assemblies all at once. The stepper motor will hold the assembly together as the build continues. Do not worry about setting the stepper adjustments at this point.

9. Slide the top plate and bearing over the main body and gear assembly, and insert the final (2) PC4-M6 fittings between the top plate and the main body. Fittings must be added prior to fastening the top plate.

10. Add an M5x16 BHCS to the Rotational Cross Brace so that the threads stick out away from the top, with a thrust bearing (or shim washers) placed between the head of the bolt and the printed Rotational Cross Brace.

11. Add the rotational cross brace to the top of the Pestle extruder by fitting the (4) posts into the top plate's post holes. Secure the brace using (2) M3x30mm and (2) M3x35mm BHCS screws. The screws will pass through the entire assembly to the transmission plate and main body, respectively.

12. Add an M5 nut to your respective mounting solution and thread the Pestle assembly through it, with a thrust bearing placed between the rotational cross brace and the mounting solution.

13. *(Skip this step if not using PTFE in this manner)* Add PTFE Bowden tubing from the support arm looping under the extruder and into the bottom of the extruder. This acts as the reverse Bowden guide for the filament. Take care not to bend at too steep of an angle and kink the PTFE. If the PTFE is kinked and does not allow filament to pass smoothly, it should be replaced.

14. Add PTFE tubing from the top of the extruder to your toolhead assembly, then review the Pestle Retraction Settings below.

---

## 📏 Retraction Settings

| Setting | Value |
| :--- | :--- |
| **Retraction Distance** | 0.95 mm |
| **Retraction Speed** | 40 mm/s |
| **Detraction Speed** | 45 mm/s |
| **Estimated Pressure Advance** | 0.280 |
| **Estimated Pressure Advance Smooth Time** | 0.035 |

> [!NOTE]
> These settings are intended as a starting point for tuning and do not reflect all system requirements. Individual system needs vary, and your specific use case may require adjustments.

***

> ☕ **Did you find this guide helpful?** 
> 
> My projects are open-source and free for the community. If you've enjoyed my designs and want to support my work, consider [leaving me a tip on Ko-fi](https://ko-fi.com/alchemical3d)! 
>
> [![Ko-Fi](https://ko-fi.com/img/githubbutton_sm.svg)](https://ko-fi.com/alchemical3d)


### [Visit our Discord!](https://discord.gg/aE49DW2xXe)
### DISCORD: https://discord.gg/aE49DW2xXe
