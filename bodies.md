[<< Back to Readme](https://github.com/Sigourn/newvegas-sharp/blob/main/README.md)  
[<< Back to Setup](https://github.com/Sigourn/newvegas-sharp/blob/main/setup.md)  
[<< Back to Main](https://github.com/Sigourn/iheartnewvegas/blob/main/main.md)

> PROTIP: Click on the list icon on the upper left corner of this document to see the index for this guide.

# DISCLAIMER

The guide presented here assumes you have already followed all instructions found in **Left My Heart In New Vegas**. Please abstain from using this guide until you've correctly set up Fallout: New Vegas.

## PRELIMINARY STEPS

[**Misc Gameplay Merge**](https://www.nexusmods.com/newvegas/mods/73921)
- Open **NVSE\plugins\scripts\gr_MiscEquipmentChanges.txt** using a text editor, and delete the following lines:
  - SetBipedModelPathAlt ArmorNVCLExplorer 1 "FIXforLegionArmors\ExplorerFemale.nif"
  - SetBipedModelPathAlt ArmorNVCLRecruit 1 "FIXforLegionArmors\RecruitFemale.nif"
  - SetBipedModelPathAlt ArmorNVCLPrime 1 "FIXforLegionArmors\PrimeFemale.nif"
  - SetBipedModelPathAlt ArmorNVCLVeteran 1 "FIXforLegionArmors\VeteranFemale.nif"
  - SetBipedModelPathAlt ArmorNVCLVexillarius 1 "FIXforLegionArmors\VexillariusFemale.nif"
  - SetBipedModelPathAlt ArmorNVCLPraetorian 1 "FIXforLegionArmors\PraetorianFemale.nif"
  - SetBipedModelPathAlt ArmorNVCLCenturion 1 "FIXforLegionArmors\CenturionFemale.nif"
  - SetBipedModelPathAlt ArmorNVCaesar 1 "FIXforLegionArmors\CaesarFemale.nif"

## BODY REPLACERS

[**Improved Vanilla Male Body - Seamless - 4k**](https://www.nexusmods.com/newvegas/mods/70160)  
High poly, improved and seamless version of the male body. Compatible with vanilla outfits.

Files to install:
- **01 - Improved Male Body - FOMOD Installer** (Main files)
  - FOMOD options to install:
    - [X] 00 - Main
    - [X] 05 - Underwear Options
      - [X] 08 - Legacy Underwear
- **00 - Outfit Conversions - Hotfix** (Update files)  
  Work in progress outfit conversion for most of the openfoot meshes.
  - **Merge** with the main file. 

[**TYPE4 - Body and Armors**](https://www.nexusmods.com/newvegas/mods/66903)  
Female body replacer featuring no neckseams and much improved arms and upperbody. Complete set of armor and clothing with support for all DLCs.
- Hide the **meshes\characters\ _male\locomotion** folder.
- Hide the **meshes\pipboy3000** folder.

> ℹ️ This fixes compatibility issues with **Pip-Boy 2500 Mk VI** and animation mods.

[**TYPE4 - Armor Fixes**](https://www.nexusmods.com/newvegas/mods/73885)  
Fixes a glitch that caused light reflections to flicker with TYPE4 armors.
  
Files to install:
- **T4 Armor Mesh Fixes (Vanilla)** (Main files)

[**More Modest TYPE4 Body and Armor**](https://www.nexusmods.com/newvegas/mods/69642)  
Less skimpy outfits for many TYPE4 outfits.
- Hide **jumpsuit fix.esp**
  
[**More Modest TYPE4 Fixes**](https://github.com/Sigourn/iheartnewvegasrepository/blob/main/More%20Modest%20T4%20Fixes.7z)  
Fixes mismatching textures on a number of More Modest TYPE4 outfits.

[**TYPE4 Alternative Outfits**](https://www.nexusmods.com/newvegas/mods/66993)  
Less skimpy Wasteland Wanderer and Raider outfits.
  
Files to install:
- **Raider armors** (Main files)
- **Wasteland Wanderer** (Main files)

[**T6M Prostitute Outfits and Combat Armor**](https://github.com/Sigourn/iheartnewvegasrepository/blob/main/T6M%20Prostitute%20Outfits%20and%20Combat%20Armor.7z)  
Less skimpy Prostitute outfits and less goofy Combat Armor.
- [X] 00 Prostitute Outfits
- [X] 01 Combat Armor JSUE

[**TYPE4 Patches**](https://www.nexusmods.com/newvegas/mods/74893) (Main Files)  
Patches **TYPE4** for a variety of mods.
- BAIN options to install:
  - [X] 00 YUP Patch
  - [X] 01 TYPE4 Fixes
  - [X] 02 Vanilla Radiation Suits
  - [X] 03 JSUE Patch
  - [X] 05 Eyelashes FNV Patch

[**Body and Face Textures Workshop**](https://www.nexusmods.com/newvegas/mods/55174)  
High resolution textures for Type-based female bodies.

Files to install:
- **00 - Default Version - CORE** (Main files)
- **00b - Raider Textures** (Main files)
- **00 - Dead Money DLC - Christine face** (Update files)
- **01 - Old Female** (Update files)  
- **01 - Detailed Face Normalmap** (Optional files)  
- **03 - Body Hairy Clean** (Optional files)  
- **05 - Face Vanilla Feel** (Optional files)  

> ℹ️ This mod is entirely optional, as **TYPE4** already includes seamless textures for its bodies. However, I find they look a bit jarring compared to **Improved Vanilla Male Body**, hence why I recommend installing these textures on top.

## FINISHING TOUCHES

### Mod order and load order

The mods installed in this guide can be placed at the very end of **Left My Heart In New Vegas**.

<details>
<summary>Mod order</summary>

```
Improved Vanilla Male Body - Seamless - 4K
TYPE4 - Body and Armors
TYPE4 - Armor Fixes
More Modest TYPE4 Body and Armor
More Modest TYPE4 Fixes
TYPE4 Alternative Outfits
T6M Prostitute Outfits and Combat Armor
TYPE4 Patches
Body and Face Textures Workshop
```
</details>

<details>
<summary>Load order</summary>

```
T4-plugin.esp
More Modest T4 Fixes.esp
T6M Combat Armor Fix JSUE.esp
T4 YUP Patch.esp
T4 Fixes.esp
T4 Vanilla Radiation Suits.esp
T4 JSUE Patch.esp
T4 Eyelashes FNV Patch.esp
```
</details>

[<< Back to Readme](https://github.com/Sigourn/newvegas-sharp/blob/main/README.md)  
[<< Back to Setup](https://github.com/Sigourn/newvegas-sharp/blob/main/setup.md)  
[<< Back to Main](https://github.com/Sigourn/iheartnewvegas/blob/main/main.md)
