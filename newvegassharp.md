[<< Back to Main](https://github.com/Sigourn/morrowind-sharp/blob/master/readme.md#morrowind-a-morrowind-modding-guide)  
[<< Back to Setup](https://github.com/Sigourn/morrowind-sharp/blob/master/setup.md#morrowind-setup)

# NEW VEGAS SHARP

> PROTIP: Click on the list icon on the upper left corner of this document to see the index for this guide.

# BEFORE WE BEGIN

## DISCLAIMER

The guide presented here assumes you have already followed all instructions found in the [**Setup**](https://github.com/Sigourn/morrowind-sharp/blob/master/setup.md#morrowind-setup) page. Please abstain from using this guide until you've correctly set up Fallout: New Vegas and the recommended tools.

## MODDING TIPS

### Don't uninstall mods mid-playthrough

A lot of things can go wrong when uninstalling a mod mid-playthrough. Some, expected. Some, completely unexpected.

### Always keep backup saves

Before you install a mod you are not completely sure about, make a backup of your save in case things go wrong.  
Before you uninstall a mod you are not completely sure about, make a backup of your save in case things go wrong.

### Read the descriptions

Mod descriptions exist for a reason. The elaborate ones, usually for a *good* reason. Apart from describing what a mod is supposed to, descriptions tend to list things such as:

- Requirements: mods or utilities a given mod needs to work as intended.
- Compatibility issues: known conflicts with other mods, whether general or specific.
- Known issues: bugs or unintended behavior.

Reading descriptions helps you troubleshoot mods, and what's more, decide beforehand whether a mod is worth the trouble of installing it.

### File structure matters

The file structure is how files are organized for the game to read and use them. Incorrect file structure accounts for a good deal of mods that don’t work properly.

## MOD ORGANIZER 2 TIPS

### Installing Nexus mods with Mod Organizer 2

Because Mod Organizer 2 is associated with Nexus links, mods downloaded in Nexus will be instantly added to Mod Organizer 2.

- Click **Mod manager download** under the file you want to download.
- Click **Slow download**.
- In Mod Organizer 2, click on the **Downloads** tab. You can check the download progress for your file there.
- Right-click the downloaded file, and click **Install**.
- MO2 will prompt you to give the mod a name. I suggest giving it a descriptive name, such as mod name + version number (e.g. "Yukichigai Unofficial Patch - YUP 12.2").
- Click **OK**.
- The mod will appear in the left pane. Check the box next to it to finish installation.

> Whenever you are asked to install a mod from Nexus, limit yourself to the main file, unless explicitly told to install a different file. Likewise, if there are multiple main files present, you will be told which one you need to install.

### Installing multiple files from a same Nexus mod with Mod Organizer 2

There will be times when you will be asked to install multiple files from the same mod page. These can be either updates or optional files regarding a given mod, or multiple different mods from the same page, usually compilation pages for minor mods which the author didn't think deserved individual mod pages.

Mod Organizer 2 allows the user to either merge, replace, or rename the file being installed.

![ModExists](https://raw.githubusercontent.com/Sigourn/morrowind-sharp/master/MO2_ModExists.png)

What these options do is simple:

- **Merge** merges the contents of the file being installed with those of the file of the same name already installed. The new files will take priority over the old files, overwriting as necessary. This is useful when installing an update file which only includes certain files from the new mod.
- **Replace** replaces the contents of the already installed file with those of the newly installed file. This is akin to uninstalling the old file, and installing the new file. It is recommended you use this option whenever a mod has received a new update, as the update may not necessarily overwrite the old files.
- **Rename** installs the new file as a separate mod with a different name. In the case of compilation pages, this is a very useful feature as it lets you keep the different files (mods) as different installed mods.

> The guide will tell you when you need to merge, replace, or rename files in order to avoid problems.

### Manually installing mods with Mod Organizer 2

Sometimes authors will block the **Mod manager download** option in Nexus, and you will have to download the mod manually. On other occasions, you will download a mod from a different site altogether.

- Download your file.
- In Mod Organizer 2, click the **Install a new mod from archive** ![Archive](https://raw.githubusercontent.com/Sigourn/morrowind-sharp/master/MO_Archive.png) button.
- Navigate to the folder where the downloaded file is stored and double click on it.
- MO2 will prompt you to give the mod a name. I suggest giving it a descriptive name, e.g. "mod name" + "version number".
- Click **OK**.
- The mod will appear in the left pane. Check the box next to it to finish installation.

### BAIN installers

BAIN installers allow modders to split their mods into a number of options. This way, the user can select the options they want to install. This guide has numerous mods packaged as BAIN installers, and detailed instructions on which of the options offered by these mods you should check (install) and uncheck (skip).

### Hiding files

Mod Organizer 2 lets you hide specific files from your installed mods, like assets and plugins. A hidden plugin is treated as a deactivated plugin, with the bonus that it will no longer be listed in your load order. This is particularly useful when your load order is cluttered by deactivated plugins. Hiding assets is useful when you want certain files not to overwrite another mod's.

- To hide a plugin, right click on your installed mod and click **Information...**.
- On the **Filetree** tab, right click on the plugins, folders, or files you want to hide, and click **Hide**.
- Mod Organizer 2 will hide the files, and these will no longer affect your game.

### Repackaging mods

There will be times you'll be greeted with the following message when installing a mod through Mod Organizer 2.

> **The content of data files does not look valid.**

In lieu of mod authors not fixing their mods themselves, there are two ways to fix this.

- Repackage the mod yourself and install it through Mod Organizer 2.
- Repackage the mod yourself *in* Mod Organizer 2.

The concept of a mod package is simple: if Mod Organizer 2 recognizes *anything* resembling a file structure (folders such as **Meshes** and **Textures**, or **.esp** and **.esm** files) the mod will be considered valid.

![DataFiles1](https://raw.githubusercontent.com/Sigourn/morrowind-sharp/master/MO2_DataFiles.png)

In this case, the mod contains a **Data** folder and a loose **.txt** file acting as the mod's documentation.

- Right-click on **Data**.
- Click **Set as data files directory**.
- The message will tell you the content of data files looks valid.

Whenever you encounter this scenario, just do as I've shown above.

![DataFiles2](https://raw.githubusercontent.com/Sigourn/morrowind-sharp/master/MO2_DataFiles2.png)

In this case, the mod contains loose files, and you will have to create a folder to drop them in.

Right-clicking on **data** and clicking **Create directory...** will let you create a folder, and then it's just a matter of dragging and dropping your files inside.

- Right-click on **data**.
- Click **Create directory...**.
- Enter the name of the folder you want to create, and click **OK**.
- The message will tell you the content of data files looks valid.

Whenever you encounter this scenario, I'll tell you which folders you have to create and what files you have to move.

### Creating a separator

Separators allow you to neatly separate installed mods in Mod Organizer 2 for ease of viewing. These can be created and then moved around in the left pane to place them where you want them to be.

- Right click on the empty space on the left pane, below **Overwrite**, and click **Create Separator**.
- Name your separator and click **OK**.

I suggest creating a separator for each of the following mod categories. Separators can be collapsed to keep your mod list clean and tidy, which you will come to appreciate when you install over 100 mods.

# PATCHES

[**Navmesh Fixes and Improvements**](https://www.nexusmods.com/newvegas/mods/62041)  
Fixes virtually every navmesh where the edge connections were missing or pointing at misplaced or invalid triangles, all while retaining the original triangle ordering at the cell edges whenever possible for maximum compatibility. Also makes improvements to the majority of the affected navmeshes, like adding gaps for obstacles such as rocks and trees.

[**Yukichigai Unofficial Patch - YUP**](https://www.nexusmods.com/newvegas/mods/51664)  
A compilation of vital bug fixes for Fallout: New Vegas and its DLCs, all combined into one ESM. The only pure bug fix compilation available on the Nexus: no new features, no balance tweaks, no restored content.
- Install the **YUP - Base Game and All DLC** main file.

[**Unofficial Patch NVSE Plus**](https://www.nexusmods.com/newvegas/mods/71239?)  
Collection of bugfixes requiring NVSE.

[**Combat Lag Fix**](https://www.nexusmods.com/newvegas/mods/71973)  
Improves framerate in combat by fixing an engine bug that lowered framerate while attacking an enemy with a health-bar visible.

[**Weapon Mesh Improvement Mod**](https://www.nexusmods.com/newvegas/mods/65052)  
Fixes mesh errors, UV errors, incorrect flags, missing extra data, form lists, projectiles, and other weapon related bugs and errors.
- Also install the [**Viva New Vegas WMIM ESP Replacer**](https://github.com/VivaNewVegas/Viva-New-Vegas-Patch-Emporium/blob/main/WMIM%20ESP%20Replacer.7z). Removes all changes the mod makes other than the changes required for the mesh fixes, as the original ESP has some bugs, conflicts, and many non-bug fix changes.

[**Throwable Weapon Fixes**](https://www.nexusmods.com/newvegas/mods/62767)  
A collection of fixes for throwable weapons, focused on projectiles.

[**Landscape Disposition Fix**](https://www.nexusmods.com/newvegas/mods/73937/)  
Small mod fixing several hundred vanilla floating objects, underground or above ground.

[**Dirty Pre-War Businesswear Texture Fix**](https://www.nexusmods.com/newvegas/mods/65774)  
Fixes the Dirty Pre-War Businesswear and Grimy Pre-War Businesswear having the incorrect textures.
- Forward the appropiate fixes from **Yukichigai Unofifcial Patch** using **FNVEdit**.

[**Female White Glove Society Mask Fix**](https://www.nexusmods.com/newvegas/mods/66940)  
Fixes the White Glove Society Mask mesh for female characters.

[**Fix for the Caesar Legion Armors Redone**](https://drive.google.com/file/d/1OfFnnrl2gvU6p2QNI-4xGndicBM_zd-a/view)  
Collection of fixes for the Caesar Legion Armors.

> This mod is based off [**Fix for the Caesar Legion Armors**](https://www.nexusmods.com/newvegas/mods/65004), including edits made for compatibility with body replacers.

[**Less Flickery City of New Vegas**]()  


<details>
	<summary>Optional Patches - Click to expand</summary>

[**Ammo Burst Case Count Fix**](https://www.nexusmods.com/newvegas/mods/69175)  
Fixes the game only giving you one ammo case when your weapon uses more than one ammo count in a shot, for you and companions.

[**Ammo Script Fixes**](https://www.nexusmods.com/newvegas/mods/63997)  
Fixes several problems at the core level with how ammo scripts and effects work, plus some tweaks for consistency and fun.

[**Critical and Effects - Fixes and Tweaks**](https://www.nexusmods.com/newvegas/mods/69200)  
Fixes the damage dealing critical effects of most vanilla weapons so that they cannot cause you to miss "killcounts" and other proc effects such as crime responsibility.

[**Gauss Rifle VATS Fix - JIP**](https://www.nexusmods.com/newvegas/mods/69136)  
Fixes the Gauss Rifle not dealing headshot and critical damage in VATS.

[**Mostly Unarmed Tweaks**](https://www.nexusmods.com/newvegas/mods/69283)  
Fixes the fatigue-dealing weapons to deal correct and damage-adjusted fatigue to enemies and the player, plus a few more changes related to unarmed combat for player and NPCs.

[**Universal Pyromaniac Buff for Fire Effects**](https://www.nexusmods.com/newvegas/mods/71505)  
Makes the Pyromaniac perk affect *all* the lingering fire damage effects from weapons and ammo.

[**Gun Runners Kiosk Glass Fix**](https://www.nexusmods.com/newvegas/mods/70293)  
Fixes the glass texture in the Gun Runners' kiosk.
</details>

# USER INTERFACE

[**Better Readable Beauty Font**](https://www.nexusmods.com/morrowind/mods/49201)  
High resolution replacer for the Magic Cards font, used in most of the user interface.

# QUALITY OF LIFE IMPROVEMENTS

[**Adamantium Ore Fix**](https://www.nexusmods.com/morrowind/mods/47068)  
Allows the player to find the exact amount of Adamantium Ore needed to craft Bols Indalen's custom Adamantium Armor.
- Rename the file to **Adamantium Ore Fix** before installing it.

# GAMEPLAY

[**Expansion Delay**](https://www.nexusmods.com/morrowind/mods/47588)  
Fixes Bethesda's overly enthusiastic expansion hooks by delaying the Dark Brotherhood attacks (for Tribunal) and limiting intrusive dialogue topics to a few NPCs (Bloodmoon).

# OVERHAULS

These mods rebuild existing mechanics from the ground up, making drastic changes to them that can't be summarized in a few lines without omitting important information, or outright modify how you approach to playing the game, be it because of increased difficulty or reworked mechanics.

[**Class-Conscious Character Progression (CCCP)**](https://www.nexusmods.com/morrowind/mods/48110)  
A leveling mod that implements most features of Galsiah's Character Development.

# AUDIO

[**No Female Nord Screeching**](https://www.nexusmods.com/morrowind/mods/49232)  
Replaces a handful of sound files to stop female Nords from bursting your ear drums when they are attacked.
- Rename the file to **No Female Nord Screeching** before installing it.

# DIALOGUE

[**Great Service**](https://www.nexusmods.com/morrowind/mods/47767)  
Enables over 100 lines of voiced dialogue for shopkeepers that were shipped with the original game but never used.

# VISUALS

[**Pete's Scroll 2018 ...in 2020**](https://www.nexusmods.com/morrowind/mods/47863)  
Replacement scroll and journal textures, rendered out in 1k, 2k, and 4k dimensions.
- Install the **Pete's Journal and Scroll** optional file.
- Check the following options in the BAIN installer:
  - [ ] 01 Journal and Scroll - 1K
  - [X] 01 Journal and Scroll - 2K
  - [ ] 01 Journal and Scroll - 4K
  - [ ] 02 Daedric Alphabet Scroll

# FINISHING TOUCHES

## FINAL MOD ORDER AND LOAD ORDER

The mod order dictates the priority a given mod's assets have over the mods installed before it. Respect this order to ensure assets are overwritten as intended.

> Indented you will find mods from the optional sections of the guide.

<details>
<summary>Mod order</summary>

```
DLC: Tribunal
DLC: Bloodmoon
    Drop Light
    Light Decay
    No Beds for the Diseased
    Realistic Movement Speeds
    Wading in Water MW
```
</details>

The load order dictates the priority a given mod's plugins have over the mods' plugins loaded before them. Respect this order to ensure plugin records are overridden as intended.

> Indented you will find mods from the optional sections of the guide.

<details>
<summary>Load order</summary>

```
Morrowind.esm
Tribunal.esm
Bloodmoon.esm
```
</details>

## MANUALLY CLEANING OUR PLUGINS

> This section includes plugins from the optional sections of the guide.

Some of our installed plugins contain changes we are not really interested in. These changes don't constitute dirty changes themselves, rather, changes we simply do not want. Because of this, we will be using [**TESAME**](https://github.com/Sigourn/morrowind-sharp/blob/master/mwtools.md#tesame) to delete the unwanted records.

- Run TESAME in Mod Organizer 2.
- Delete the following record from **Services Restored.ESP**:
  - NPC **hecerinde**
- Save the plugin as **Services Restored.ESP**, overwriting the original.

> This omits the restoration of Hecerinde's Secret Master tools from [**Services Restored**](https://www.nexusmods.com/morrowind/mods/47068), for consistency with the rest of the Secret Master tools unavailable in the game.

- Run TESAME in Mod Organizer 2.
- Delete the following records from **Alex's Better Fitted Female Armors.ESP**:
  - Armor **netch_leather_cuirass**
  - Armor **imperial_chain_cuirass**
  - Armor **steel_cuirass**
  - Armor **imperial cuirass_armor**
- Save the plugin as **Alex's Better Fitted Female Armors.ESP**, overwriting the original.

> This removes the edits from [**Better Fitted Female Armors**](https://www.nexusmods.com/morrowind/mods/50187) to armor meshes which were already designed for female characters.

## CONFLICT RESOLUTION

**tes3cmd** also allows us to solve conflicts in leveled lists, generating a **multipatch.esp** file which will be placed at the end of our load order. This is very useful when, for example, you have a mod that adds new weapons to a leveled list while another removes items from a leveled list (such as Daedric equipment).

- Run Wrye Mash (**mash64**) in Mod Organizer 2.
- In the **Mods** tab, click the **Misc** header and go to **TES3cmd** -> **Create MultiPatch**. Click **Yes** on the prompt.
- tes3cmd will now generate the multipatch. After the process is over, click **OK**.
- **multipatch.esp** will now be present at the end of your load order.

## MOD CONFIG

> This section includes mods from the optional sections of the guide.

The following mods need to be configured using the in-game **Mod Config** menu.

### abot's Smart Journal

- Set **Add a prefix in order to group quest names?** to 0. This will remove the lag when opening the quest page without this option set to 0.
- Disable every option below **Sort quests list by quest name?**. These options are useful to troubleshoot mods, but we don't need them. 

### abot's Tooltip

- Disable **Show item Value/Weight Ratio in tooltip**.

### Ashfall

- Enable **Hunger/Thirst can Kill**.
- Disable **Potion Hydrate**.
- Under **Mod values**, set **Tiredness Rate** to 45.

# MOD KEYBINDINGS

> This section includes mods from the optional sections of the guide.

This is a handy reference table which will hopefully help you have a better idea of what new hotkeys are available to you, having followed this guide from beginning to end.

Key | Function | Added by
------------ | ------------- | -------------
Y | Fast forward time | Pass the Time
K | Orders followers to attack the current target | Kill Command
L | Equips lockpicks | Security Enhanced
P | Equips probes | Security Enhanced
B | Opens/closes books and scrolls | Switchable Scriptures
C | Equips light sources | Torch Hotkey
Ctrl+Y | Turbo fast forward time | Pass the Time
Ctrl+Left Click | Select individual item in stack in inventory | Morrowind Code Patch
Shift+Left Click | Select entire stack in inventory | Morrowind Code Patch
Alt+Left Click | Transfer entire stack | Morrowind Code Patch
Shift+E | Equips/unequips item in inventory | Quick Equip
Shift+E | Use potion/ingredient in inventory | Quick Equip
Shift+Activate | Activates/deactivates placed/static light sources | The Midnight Oil

# ACKNOWLEDGMENTS

I want to thank the following people for their support. Not only for their kind comments towards me and the guide, but also for having gone the extra length and financially supporting me!

# CHANGELOG

- 🆕 Mod has been added to the guide.
- ⚠️ Mod has been updated or its installation/configuration instructions have changed.
- 🚫 Mod has been removed from the guide.

<details>
	<summary>1.0 (November 26th)</summary>

- Initial release.
</details>

[<< Back to Main](https://github.com/Sigourn/morrowind-sharp/blob/master/readme.md#morrowind-a-morrowind-modding-guide)  
[<< Back to Setup](https://github.com/Sigourn/morrowind-sharp/blob/master/setup.md#morrowind-setup)
