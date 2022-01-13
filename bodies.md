[<< Back to Readme](https://github.com/Sigourn/newvegas-sharp/blob/main/README.md)  
[<< Back to Setup](https://github.com/Sigourn/newvegas-sharp/blob/main/setup.md)  
[<< Back to Main](https://github.com/Sigourn/iheartnewvegas/blob/main/main.md)

> PROTIP: Click on the list icon on the upper left corner of this document to see the index for this guide.

# BODIES ADD-ON

## Disclaimer

The guide presented here assumes you have already followed all instructions found in **Left My Heart In New Vegas**. Please abstain from using this guide until you've correctly set up Fallout: New Vegas.

This document will guide you through the installation of face and hair textures, as well as the **TYPE 4** and **Improved Vanilla Male Body** body replaceres. Do note, however, that this guide is intended for my personal use only, and you shouldn't expect anything on the way of support if you decide to go through with it.

## Face and hair textures add-on

[**Eyelashes New Vegas**](https://www.nexusmods.com/newvegas/mods/34790)  
Adds animated eyelashes to NPCs and the player character.
- Install the **tkEyelashesFNV** main file.
- Hide **tkEyelashesFNV_FemalesOnly.esp**.

Additional files to install:
- [**Eyelashes New Vegas ESP Replacer**](https://www.nexusmods.com/newvegas/mods/74893) (Optional files)  
  Fixes issues with the plugin, and extends support to Honest Hearts' tribals and Dead Money's Christine.

[**HD Teeth and Natural Eyelashes and Eyebrows**](https://www.nexusmods.com/newvegas/mods/53695)  
Improves teeth, eyelashes, and eyebrow textures.
- Install all Main files.

[**Natural Eyes**](https://www.nexusmods.com/newvegas/mods/62811)  
Improves eye textures.
- Install **00 - Natural Eyes - Shadow** (Main files).

[**Vanilla Hair - No Shine**](https://www.nexusmods.com/newvegas/mods/50285)  
Removes shine from vanilla hairs.

## Preliminary steps for Body replacers add-on

[**Dirty Pre-War Businesswear Fix**](https://github.com/Sigourn/iheartnewvegasrepository/blob/main/Dirty%20Pre-War%20Businesswear%20Fix%201.0.7z)  
Fixes the Dirty Pre-War Businesswear having the incorrect texture.
- Uninstall this mod. It is included in **TYPE4 Patches**, which we will install later.

[**Honest Hearts Gecko Leathers Improved ESP Replacer and JSUE Patch**](https://github.com/Sigourn/iheartnewvegasrepository/blob/main/Honest%20Hearts%20Gecko%20Leathers%20Improved%20ESP%20Replacer%20and%20JSUE%20Patch.7z)  
Includes **YUP** fixes and adds a patch for **JSawyer Ultimate Edition**.
- Reinstall this mod.
- BAIN options to install:
  - [X] 00 ESP Replacer Compatibility Version
  - [X] 01 JSUE Patch Compatibility Version

[**Misc Gameplay Merge**](https://www.nexusmods.com/newvegas/mods/73921)  
Compilation of small gameplay mods by various authors, all fully fixed, optimized, and updated by Qolore7.
- Open **NVSE\plugins\scripts\gr_MiscEquipmentChanges.txt** using a text editor, and delete the following lines:
  - SetBipedModelPathAlt ArmorNVCLExplorer 1 "FIXforLegionArmors\ExplorerFemale.nif"
  - SetBipedModelPathAlt ArmorNVCLRecruit 1 "FIXforLegionArmors\RecruitFemale.nif"
  - SetBipedModelPathAlt ArmorNVCLPrime 1 "FIXforLegionArmors\PrimeFemale.nif"
  - SetBipedModelPathAlt ArmorNVCLVeteran 1 "FIXforLegionArmors\VeteranFemale.nif"
  - SetBipedModelPathAlt ArmorNVCLVexillarius 1 "FIXforLegionArmors\VexillariusFemale.nif"
  - SetBipedModelPathAlt ArmorNVCLPraetorian 1 "FIXforLegionArmors\PraetorianFemale.nif"
  - SetBipedModelPathAlt ArmorNVCLCenturion 1 "FIXforLegionArmors\CenturionFemale.nif"
  - SetBipedModelPathAlt ArmorNVCaesar 1 "FIXforLegionArmors\CaesarFemale.nif"

> ℹ️ This reverts the renamed female models in favor of **TYPE 4**'s models.

## Body replacers add-on

[**Improved Vanilla Male Body - Seamless - 4k**](https://www.nexusmods.com/newvegas/mods/70160)  
High poly, improved and seamless version of the male body. Compatible with vanilla outfits.
- Install **01 - Improved Male Body - FOMOD Installer** (Main files).
- FOMOD options to install:
  - [X] 00 - Main
  - [X] 05 - Underwear Options
    - [X] 08 - Legacy Underwear

Additional files to install:
- **00 - Outfit Conversions - Hotfix** (Update files)  
  Work in progress outfit conversion for most of the openfoot meshes.
  - **Merge** with the main file. 

[**TYPE4 - Body and Armors**](https://www.nexusmods.com/newvegas/mods/66903)  
Female body replacer featuring no neckseams and much improved arms and upperbody. Complete set of armor and clothing with support for all DLCs.
- Hide the **meshes\characters\ _male\locomotion** folder.
- Hide the **meshes\pipboy3000** folder.

> ℹ️ This fixes compatibility issues with **Pip-Boy 2500 Mk VI** and animation mods.

> ℹ️ If you don't want female nudity, you need to delete **femaleupperbody.nif** and **femaletribalupperbody.nif** (found in **meshes\characters\_male** folder), and remove the underscore from **_femaleupperbody.nif** and **_femaletribalupperbody** (also found in the same folder).

Additional files to install:
- [**TYPE4 - Armor Fixes**](https://www.nexusmods.com/newvegas/mods/73885)  
  Fixes a glitch that caused light reflections to flicker with TYPE 4 vanilla armors.
  - Install **T4 Armor Mesh Fixes (Vanilla)** (Main files).
- [**TYPE4 Patches**](https://www.nexusmods.com/newvegas/mods/74893) (Main Files)  
  Patches **TYPE 4** for a variety of mods.
  - BAIN options to install:
    - [X] 00 YUP Patch
    - [X] 01 TYPE4 Fixes
    - [X] 02 Vanilla Radiation Suits
    - [X] 03 JSUE Patch
    - [X] 04 PA Gloves Patch
    - [X] 05 Eyelashes FNV Patch

Optional files to install:
- [**More Modest TYPE 4 Body and Armor**](https://www.nexusmods.com/newvegas/mods/69642)  
  Less skimpy outfits.
  - [**Pre-War Casualwear and Relaxedwear Fix**](https://github.com/Sigourn/iheartnewvegasrepository/blob/main/More%20Modest%20TYPE%204%20Pre-War%20Casualwear%20and%20Relaxedwear%20Fix%20(Dec%2029th).7z). Fixes mismatching textures for a number of Pre-War outfits.
- [**T6M Outfits Selection**](https://github.com/Sigourn/iheartnewvegasrepository/blob/main/T6M%20Outfits%20Selection.7z)  
  - [X] 00 Prostitute Outfits  
    - Less skimpy outfits for prostitutes.
  - [X] 01 Raider Outfits  
    - Less skimpy outfits for raiders.
  - [X] 02 Combat Armor
    - Less goofy looking Combat Armor.
  - [X] 03 Combat Armor JSUE Patch
    - Patches the mod for compatibility with JSawyer Ultimate Edition.
- [**T6M Christine's Outfit**](https://www.nexusmods.com/newvegas/mods/68385)  
  Gives an unique appearance to Christine's outfit from Dead Money.

[**Body and Face Textures Workshop**](https://www.nexusmods.com/newvegas/mods/55174)  
High resolution textures for Type-based female bodies.
- Install **00 - Default Version - CORE** (Main files).
- Install **00b - Raider Textures** (Main files).
  - **Merge** with the main file.

Additional files to install:
- **00 - Dead Money DLC - Christine face** (Update files)
  - **Merge** with the main file.
- **01 - Old Female** (Update files)  
  - **Merge** with the main file.
- **01 - Detailed Face Normalmap** (Optional files)  
  - **Merge** with the main file.
- **03 - Body Hairy Clean** (Optional files)  
  - **Merge** with the main file.
- **05 - Face Vanilla Feel** (Optional files)  
  - **Merge** with the main file.

> ℹ️ This mod is entirely optional, as **TYPE4** already includes seamless textures for its bodies. However, I find they look a bit jarring compared to **Improved Vanilla Male Body**, hence why I recommend installing these textures on top.

[**Mannequin Races**](https://www.nexusmods.com/newvegas/mods/62785)  
Adds seven new custom races to Fallout New Vegas.

Additional files to install:
- **00 - EGM files for hairs** (Optional files)  
  - **Merge** with the main file.
- [**Mannequin Races - TYPE4**](https://www.nexusmods.com/newvegas/mods/68994)  
  TYPE4 textures and meshes for Mannequin Races.
  - Install **00 - Mannequin Races TYPE4** (Main files).
  - Install **01 - TYPE4 Underwear** (Optional files).
    - **Merge** with the main file.

> ℹ️ This mod offers better head meshes for creating your own character. Unfortunately, the included textures are not my cup of tea, and I recommend you copy and paste your TYPE4 textures of choice in order to overwrite the ones from this mod.

## Finishing touches

### Mod order and load order

The mods installed in this guide can be placed at the very end of **Left My Heart In New Vegas**.

<details>
<summary>Mod order</summary>

```
Eyelashes New Vegas
Eyelashes New Vegas ESP Replacer
HD Teeth and Natural Eyelashes and Eyebrows
Vanilla Hair - No Shine
Natural Eyes
Improved Vanilla Male Body - Seamless - 4K
TYPE4 - Body and Armors
TYPE4 - Armor Fixes
TYPE4 Patches
T6M Outfits Selection
T6M Christine's Outfit
More Modest TYPE 4 Body and Armor
More Modest TYPE 4 Pre-War Casualwear and Relaxedwear Fix
Body and Face Textures Workshop
Mannequin Races
Mannequin Races - TYPE 4
Improved Duster Coats - YUP Edition
```
</details>

> ℹ️ **Improved Duster Coats - YUP Edition** needs to load after TYPE4 to overwrite its Combat Ranger meshes.

<details>
<summary>Load order</summary>

```
tkEyelashesFNV.esp
T4-plugin.esp
T4 YUP Patch.esp
T4 Fixes.esp
T4 Vanilla Radiation Suits.esp
T4 JSUE Patch.esp
T4 PA Gloves Patch.esp
T4 Eyelashes FNV Patch.esp
T6M Combat Armor.esp
ChristineOutfit.esp
More Modest TYPE 4 Pre-War Casualwear and Relaxedwear Fix.esp  
ImprovedGeckoLeatherArmor.esp
ImprovedGeckoLeatherArmor JSUE Patch.esp
Mannequin Rce.esp
```
</details>

[<< Back to Readme](https://github.com/Sigourn/newvegas-sharp/blob/main/README.md)  
[<< Back to Setup](https://github.com/Sigourn/newvegas-sharp/blob/main/setup.md)  
[<< Back to Main](https://github.com/Sigourn/iheartnewvegas/blob/main/main.md)
