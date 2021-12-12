# BEFORE WE BEGIN

## DISCLAIMER

The guide presented here assumes you have already followed all instructions found in **Left My Heart In New Vegas**. Please abstain from using this guide until you've correctly set up Fallout: New Vegas.

This document will guide you through the installation of face and hair textures, as well as the **TYPE 4** body replacer.

## PRELIMINARY STEPS

The following mods should be reinstalled if you plan on using **TYPE 4**.

[**Dirty Pre-War Businesswear Fix**](https://drive.google.com/file/d/1TaOxdPB3g4fveejLqOyeE4vZR0cJkJjY/view?usp=sharing)  
Fixes the Dirty Pre-War Businesswear having the incorrect texture.
- BAIN options to install:
  - [X] 00 Core
  - [X] 02 TYPE 4

[**Honest Hearts Gecko Leathers Improved ESP Replacer and JSUE Patch**](https://drive.google.com/file/d/1iZpi_BLNYJipjpe1MruxxQbPuK9PFjDV/view?usp=sharing). Forwards **YUP** fixes and adds a patch for **JSawyer Ultimate Edition**.
- BAIN options to install:
  - [X] 00 ESP Replacer Compatibility Version
  - [X] 01 JSUE Patch Compatibility Version

# FACE AND HAIR TEXTURES

[**Vanilla Underwear Replacer**](https://www.nexusmods.com/newvegas/mods/64006)  
Replacer for the default underwear, removing the shirt for males and tweaking the shape of the female top.

[**Eyelashes New Vegas**](https://www.nexusmods.com/newvegas/mods/34790)  
Adds animated eyelashes to NPCs and the player character.
- Install the **tkEyelashesFNV** main file.
- Hide both plugins.

Additional files to install:
- [**Eyelashes New Vegas ESP Replacer**](https://drive.google.com/file/d/1EKtFdcYvHcx841UvNx9zt6p0bTFaE5H9/view?usp=sharing). Fixed version of the main plugin.

[**HD Teeth and Natural Eyelashes and Eyebrows**](https://www.nexusmods.com/newvegas/mods/53695)  
Improves teeth, eyelashes, and eyebrow textures.
- Install all three main files.

[**Natural Eyes**](https://www.nexusmods.com/newvegas/mods/62811)  
Improves eye textures.
- Install the **00 - Natural Eyes - Shadow** main file.

[**Vanilla Hair - No Shine**](https://www.nexusmods.com/newvegas/mods/50285)  
Removes shine from vanilla hairs.

# BODY REPLACERS

[**TYPE4 - Body and Armors**](https://www.nexusmods.com/newvegas/mods/66903)  
Female body replacer featuring no neckseams and much improved arms and upperbody. Complete set of armor and clothing with support for all DLCs.
- Delete the following records in **FNVEdit**.
  - ArmorRadiationSuit
  - ArmorRadiationSuitAdvanced
  - MS03EnvironmentSuit
  - CSArmorRadiationSuit
- Hide the **meshes\armor\enclavescientist** folder.
- Hide the **meshes\characters\ _male\locomotion** folder.
- Hide the **meshes\pipboy3000** folder.

> This removes the changes to the Radiation Suit and related outfits, and fixes compatibility issues with **Pip-Boy 2500 Mk VI** and animation mods.

Additional files to install:
- [**TYPE 4 Armor Fixes**](https://www.nexusmods.com/newvegas/mods/73885). Fixes a glitch that caused light reflections to flicker with TYPE 4 vanilla armors.
  - Install the **T4 Armor Mesh Fixes (Vanilla)** Main file.
- [**TYPE 4 Patches**](https://drive.google.com/file/d/15PlLJxpq_AsnbaNZlSkTndXwM83oIfu_/view?usp=sharing). Patches a number of mods featured in **Left My Heart In New Vegas**.

[**Mannequin Races**](https://www.nexusmods.com/newvegas/mods/62785)  
Adds seven new custom races to Fallout New Vegas.

Additional files to install:
- **00 - EGM files for hairs** (under Optional files).

[**Mannequin Races - TYPE4**](https://www.nexusmods.com/newvegas/mods/68994)  
TYPE4 textures and meshes for Mannequin Races.

Additional files to install:
- **01 - TYPE4 Underwear** (under Optional files).

[**Body and Face Textures Workshop**](https://www.nexusmods.com/newvegas/mods/55174)  
High resolution textures for Type-based female bodies.
- Install the **00 - Default Version - CORE** and **00b - Raider Textures** main files.

Additional files to install:
- **00 - Dead Money DLC - Christine face** (under Update files).
- **01 - Old Female** (under Update files).
- **01 - Detailed Face Normalmap** (under Optional files).
- **03 - Body Hairy Clean** (under Optional files).
- **05 - Face Vanilla Feel** (under Optional files).

[**T6M Neck Adjusted Outfit Replacers**](https://drive.google.com/file/d/17BjQgaU_IlHBHMhtEuJ6rJ2jUHnoBhXh/view?usp=sharing)  
Outfit replacers for Combat Armor (including variations), Prostitute Outfits, and Raider Outfits.

# FINISHING TOUCHES

## EXTENDED MOD ORDER AND LOAD ORDER

The mods installed in this guide can be placed at the very end of **Left My Heart In New Vegas**.

<details>
<summary>Mod order</summary>

```
Vanilla Underwear Replacer
Eyelashes New Vegas
Eyelashes New Vegas ESP Replacer
HD Teeth and Natural Eyelashes and Eyebrows
Vanilla Hair - No Shine
Natural Eyes
TYPE 4 - Body and Armors
TYPE 4 - Armor Fixes
TYPE 4 Patches
Mannequin Races
Mannequin Races - TYPE 4
T6M Neck Adjusted Outfit Replacers
Body and Face Textures Workshop
```
</details>

<details>
<summary>Load order</summary>

```
tkEyelashesFNV.esp
T4-plugin.esp
TYPE 4 YUP Patch.esp
TYPE 4 Dirty Pre-War Businesswear Fix.esp
TYPE 4 JSUE Patch.esp
TYPE 4 Eyelashes NV Patch.esp
ImprovedGeckoLeatherArmor.esp
ImprovedGeckoLeatherArmor JSUE Patch.esp
Mannequin Rce.esp
```
</details>
