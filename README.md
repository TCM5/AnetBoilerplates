# ANET Boilerplate

As an Anet owner I had to take a lot of time (and still taking) to make my Anet to print with quality. Searching for recomemndations on how to acomplhish that objective, I found out that a lot of common upgrades are used by the Anet Community (specially A6 and A8 owners) but this information is not found in one place, and some times not explained for dummies like my self. 

In resume, this repository is not Code based, but *"How to upgrade Anet printers for Dummies"* based in order to hold and share common procedures that should be considered.

## Upgrades

Upgrade's are divided in ordered Stage's in order to mark an order how upgrade should implemented.
**Note:** This not excludes the fact the Stage 3 upgrades could be implemented before previous Stage's.

### [Stage 1](Stage1/README.md) 
* [Upgrade Stock Firmware to Marlin](Stage1/0_InstallMarlin.md)

This should not be considered an Anet upgrade but a mandatory pre-requisit from the bottom. The main reason is not to take advantage of new features and bug fixing's that marlin provide, but security! The Stock Anet firmware is based on Marlin, but for some reason, it has security check's disabled which can be dangerous and costy.


* [Install an heat bed mosfet](Stage1/1_InstallHeatBedMosfet.md)

In the Anet community is recomended to install a mosfet to the hotend but, in my case, no main advantages were found. 


* [Add a glass bed (Optional)](Stage1/2_InstallGlassBed.md)

This one is optional because is not needed to achieve good printing's, but it will make your print's with a better bottom layer quality and easyly removable. 


### Stage 2

Anet are good printer's, but they are cheap. And cheap is noticed on little part's that where badly designed

* Hotend fan duct

* Extruder Cooling Spacer

* Extruder Filament Guide

* Z-Endstop Offset (if glass bed installed)

* Filament guide

*

### Stage 3

* Auto-Leveling with a sensor

### Stage 4

Stage 4 is your imagation and contribution. A lot of other upgrades could be made, but what works for me, could not works for you, so good luck!

## Nice to know (not Anet specific)

### CAD's

| --- | Target | Free Version |
| --- | --- | --- |
| [FreeCAD](https://www.freecadweb.org/) | Windows, MacOS, Linux | X |
| [Sketchup](https://www.sketchup.com/) | Windows | X |
| [Thinkercad](https://www.tinkercad.com/) | Browser | X |



### Slicer's

| --- | Target | Free Version |
| --- | --- | --- |
| [Cura](https://ultimaker.com/en/products/ultimaker-cura-software) | Windows, MacOS, Linux | X |
| [Slic3r](http://slic3r.org/) | Windows, MacOS, Linux  | X |
| [Repetier-Host](https://www.repetier.com/) | Windows, MacOS, Linux | X |

### Host's

| --- | Target | Free Version |
| --- | --- | --- |
| [OctoPrint](https://octoprint.org/) | Raspberry Pi | X |
| [Repetier-Host](https://www.repetier.com/) | Windows, MacOS, Linux | X |

