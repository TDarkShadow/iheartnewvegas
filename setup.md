[<< Back to Main](https://github.com/Sigourn/newvegas-sharp/blob/main/README.md#left-my-heart-in-new-vegas)

# NEW VEGAS SETUP

# Requirements

- An english copy of the game from [**GOG**](https://www.gog.com/game/fallout_new_vegas_ultimate_edition).
  - Installation instructions are found on the next section. 
- A [**Nexus**](https://users.nexusmods.com/register) account. This guide assumes you are using a Free account, so no need to pay for Premium.
- A file archiver. I recommend [**7-Zip**](https://www.7-zip.org/).
- A text editor. I recommend [**Notepad++**](https://notepad-plus-plus.org/downloads/v7.9.5/).
- [**DirectX Runtime Libraries**](https://www.microsoft.com/en-us/download/details.aspx?id=8109).
- [**Microsoft VC++ 2013**](https://www.microsoft.com/en-us/download/details.aspx?id=40784) (x86 version) and [**Microsoft VC++ 2015-2019**](https://docs.microsoft.com/en-GB/cpp/windows/latest-supported-vc-redist?view=msvc-170) (x86 and x64 versions).

# Installation

You should install Fallout: New Vegas outside all default Windows folders (Program Files, Program Files (x86), Desktop, and Documents for example). Windows User Account Control monitors these folders, which can cause problems later on.

Your Fallout: New Vegas **Root** folder is where Fallout: New Vegas will be installed, and where the game's executable (**FalloutNV.exe**), launcher (**FalloutNVLauncher.exe**), and **Data** folder will be found.

For the purpose of this guide, this will be our **Root** folder and where you should install Fallout: New Vegas:
```
C:\Games\Fallout New Vegas
```
Additional, you will need a folder where to install our mod manager and keep your mods. I recommend the following path:
```
C:\Games\Fallout New Vegas Mods
```

> Make sure you don't create your Fallout New Vegas Mods folder inside your Fallou New Vegas folder, or else you will run into issues when you try to launch the game through Mod Organizer 2, most importantly, your mods not being registered.

# Generating fresh .INI files

- Run FalloutNVLauncher.exe from the game's Root folder.
- Click OK to both pop-ups that say **Detecting Video Hardware**. If there aren't any pop-ups, navigate to Documents\My Games\FalloutNV and delete all the files ending in .INI, then retry.
- Select **Options** then select the **Ultra** preset option. A way to improve performance without drastically changing the game's visuals is by disabling shadows. New Vegas only features actor shadows which are barely visible, but which can still have a big performance impact if there are many NPCs in one area.
- Set the **Resolution** option to your preference.
- Click **OK** then **Exit**.

# Utilities

[**FNV BSA Decompressor**](https://www.nexusmods.com/newvegas/mods/65854?)  
Decompresses the Fallout New Vegas BSAs and repacks them without zlib compression for performance, Also transcodes the .ogg sounds effects to .wav so they work. It also extracts any mp3 files to loose files because they will not play when in a BSA.
- Manually download the **FNV BSA Decompressor** main file.
- Run **FNV BSA Decompressor.exe**, select your game's **Root** folder and press the **Decompress** button.
- Close the program after the patching process is done.

> This utility will add the following lines to your Fallout.ini file.

```
[Archive]
SArchiveList=Fallout - Invalidation.bsa, Fallout - Textures.bsa, Fallout - Textures2.bsa, Fallout - Meshes.bsa, Fallout - Meshes2.bsa, Fallout - Voices1.bsa, Fallout - Sound.bsa, Fallout - Misc.bsa
```

[**FNV 4GB Patcher**](https://www.nexusmods.com/newvegas/mods/62552?)  
Makes Fallout New Vegas 4GB Aware. Automatically loads NVSE if present.
- Manually download the **FNV 4GB Patch** main file.
- Place the **FalloutNVpatch.exe** in your game's **Root** folder and run it as an Administrator.
- Close the command prompt after the patching process is done.

> From now on, run the game through the **New Vegas** option in Mod Organizer 2, rather than the **NVSE** option.

# Mod Organizer 2

[**Mod Organizer 2**](https://www.nexusmods.com/skyrimspecialedition/mods/6194)  
**Mod Organizer 2** is an excellent mod manager, offering lots of quality of life conveniences that make modding an easy and quick process.
- Manually download the **Mod Organizer 2** main file.
- Run the **Mod Organizer 2.exe**.
- When prompted to choose an install location, choose your Fallout: New Vegas **Mods** folder (**C:\Games\Fallout New Vegas Mods\MO2**).
- When installation has finished, uncheck the **Launch Mod Organizer** option and click **Finish**.

> Nexus Mod Manager and Vortex are two popular mods managers, however, they have significant issues and should be avoided.

## Configuration

### Initial setup

- Run **ModOrganizer.exe**.
- Mod Organizer 2 will prompt you to **Create a new instance**. Click **Create a portable instance**.
- You will be asked to select a game to manage. If **New Vegas** is available using the appropriate file path, select it. Otherwise, click **Browse...** and select your game's **Root** folder.
- You will be asked to select a folder where data will be stored. The default MO2 folder is fine.
- Click **Next** and then **Finish**. Mod Organizer 2 will now launch.

> If you get a pop-up called **INI file is read-only**, select **Remember my choice** from the drop-down at the bottom, then click **Clear the read-only flag**.

> If you get a pop-up called **Register?**, click **Yes**. This will allow Mod Organizer 2 to handle Nexus links.

> If you get a pop-up called **Show tutorial?**, click **No**.

### Adjusting mod and load order

Your installed mods are listed on the pane to the left. This is the order in which Fallout: New Vegas loads their assets, with mods closer to the bottom overwriting the assets of mods closer to the top (if conflicting assets are present). We will refer to it as our **mod order**.

Your plugins are listed on the pane to the right. This is the order in which Fallout: New Vegas loads their plugins, with plugins closer to the bottom overwriting the records of plugins closer to the top (if conflicting records are present). We will refer to it as our **load order**.

Reorganize your load order to read as follows using drag and drop, and enable the plugins.
```
FalloutNV.esm
DeadMoney.esm
HonestHearts.esm
OldWorldBlues.esm
LonesomeRoad.esm
GunRunnersArsenal.esm
ClassicPack.esm
MercenaryPack.esm
TribalPack.esm
CaravanPack.esm
```

> If there is a plugin called **FalloutNV_lang.esp**, delete it from the game's **Data** folder.

> You can hide unnecessary information in Mod Organizer 2 by right clicking on the headers above the installed mods, and unchecking the tabs you don't want to see. I suggest unchecking everything but the **Conflicts**, **Flags**, and **Priority** boxes. You can also click on the **X** to the bottom right of the **load order** panel, hiding unnecessary background information seen on the pane below.

### Adjusting FalloutCustom.ini

- Click the **Tools** ![Tools](https://raw.githubusercontent.com/Sigourn/morrowind-sharp/master/MO_ini.png) button, and click **INI Editor**. Select the **the falloutcustom.ini** tab.
- Paste in the following lines.

```
[General]
bUseThreadedAI=1
iNumHWThreads=2
bPreemptivelyUnloadCells=1

[BackgroundLoad]
bSelectivePurgeUnusedOnFastTravel=1

[Display]
bFull Screen=1
iTexMipMapSkip=0

[Controls]
fForegroundMouseAccelBase=0
fForegroundMouseAccelTop=0
fForegroundMouseBase=0
fForegroundMouseMult=0

[Audio]
iAudioCacheSize=8192
iMaxSizeForCachedSound=1024
```

- Click **Save** and close the window.

### Setting up Profiles

Mod Organizer 2 has a feature called **Profiles**, which lets you quickly change from one mod setup to another.

- Click the **Configure profiles** ![Profiles](https://raw.githubusercontent.com/Sigourn/morrowind-sharp/master/MO_Profiles.png) button.
- Check the following options:
  - [X] Use profile-specific Game INI files.
  - [X] Use profile-specific Save Games.
  - [X] Automatic Archive Invalidation.
- With the **Default** profile selected, click **Copy**. Type in **Fallout: New Vegas Sharp** and click **OK**. Close the window.
- On the **Profile** tab, select the **Fallout: New Vegas Sharp** profile.

Fallout: New Vegas Sharp will be the profile we'll be modding. You can always revert to the **Default** profile to quickly deactivate all installed mods.

# xNVSE

[**xNVSE**](https://github.com/xNVSE/NVSE/releases)  
New Vegas Script Extender (xNVSE) expands the engine and scripting capabilities of Fallout New Vegas. This framework is required by many modern mods.
- Click the **nvse_6_2_4.7z** under **Assets** to download it.
- Extract the contents of the archive to the game's **Root** folder.

## xNVSE Plugins

[**New Vegas Heap Replacer**](https://www.nexusmods.com/newvegas/mods/69779)  
Replaces the in-game heap with a faster, more optimized version. It should decrease load times, remove some stutter and slightly improve frame rate. 
- Manually download the **NVHR** main file.
- Extract the contents of the archive and run **cpu_info.exe**. It will determine which file you need to install.
- Place the **.dll** file from the appropiate folder (indicated by **cpu_info.exe**) in your game's **Root** folder.

> This mod is not compatible with [**New Vegas Stutter Remover**](https://www.nexusmods.com/newvegas/mods/34832).

[**JIP LN NVSE Plugin**](https://www.nexusmods.com/newvegas/mods/58277)  
Extension of the New Vegas Script Extender which adds new functions, engine bug fixes and tweaks, and restored broken game features.
- Download the main file using the **Mod Manager Download** option.
- Install this mod in Mod Organizer 2.

[**JohnnyGuitar NVSE**](https://www.nexusmods.com/newvegas/mods/66927)  
Extension of the New Vegas Script Extender which adds new functions, engine bug fixes and tweaks, and restored broken game features.
- Download the main file using the **Mod Manager Download** option.
- Install this mod in Mod Organizer 2.

[**NVAC - New Vegas Anti Crash**](https://www.nexusmods.com/newvegas/mods/53635)  
Extension of the New Vegas Script Extender that implements structured exception handling and sanity checking to reduce frequency of game crashes.
- Download the main file using the **Mod Manager Download** option.
- Install this mod in Mod Organizer 2.

[**NVTF - New Vegas Tick Fix**](https://www.nexusmods.com/newvegas/mods/66537)  
Extension of the New Vegas Script Extender that fixes the tick count bug (which creates noticable micro stutter), optimizes hash tables (helping performance and decreasing menu load times), and fixes the high FPS bug (fixing physics and lipsync at high framerates).
- Download the main file using the **Mod Manager Download** option.
- Install this mod in Mod Organizer 2.
- Also install the [**Viva New Vegas NVTF Custom INI**](https://github.com/VivaNewVegas/Viva-New-Vegas-Patch-Emporium/blob/main/NVTF%20Custom%20INI.7z). This INI enables/disables certain settings to achieve the best balance between performance and stability.

[**FNV Mod Limit Fix**](https://www.nexusmods.com/newvegas/mods/68714)  
Extension of the New Vegas Script Extender that allows a maximum of 255 plugins to be loaded, as well as improving FPS, removing game stutter, and allowing for faster loading times (particularly when using a large number of mods).
- Download the main file using the **Mod Manager Download** option.
- Install this mod in Mod Organizer 2.

[**OneTweak**](https://www.nexusmods.com/skyrim/mods/40706)  
Extension of the New Vegas Script Extender that enables borderless window mode for safe alt-tabbing.
- Manually download the **OneTweak** main file.
- Extract the contents of the archive, and place the **OneTweak.dll** and **OneTweak.ini** files found **SKSE\plugins** in in your **Fallout New Vegas\Data\NVSE\plugins** folder. If such a folder is not present, create it.
- Click the **Tools** ![Tools](https://raw.githubusercontent.com/Sigourn/morrowind-sharp/master/MO_ini.png) button, and click **INI Editor**. Select the **the FalloutCustom.ini** tab.
- Set **bFull Screen** to 0.

[**Console Paste Support**](https://www.nexusmods.com/newvegas/mods/65906)  
Extension of the New Vegas Script Extender that enables hotkeys for pasting and enhanced movement/deletion.
- Download the main file using the **Mod Manager Download** option.
- Install this mod in Mod Organizer 2.

[**Improved lighting Shaders**](https://www.nexusmods.com/newvegas/mods/69833)  
Extension of the New Vegas Script Extender that almost completely fixes the exterior lighting bug, and allows up to four times the number of active lights.
- Download the main file using the **Mod Manager Download** option.
- Install this mod in Mod Organizer 2.

# FNVEdit

Because mods can conflict with one another, or have bugs/unintended changes themselves, we will be installing **FNVEdit** to help us troubleshoot and get rid of these issues.

[**FNVEdit**](https://www.nexusmods.com/newvegas/mods/34703)  
An advanced graphical module viewer/editor and conflict detector.
- Manually download the **FNVEdit 4.0.4** main file.
- Extract the contents of the archive to **Fallout New Vegas Mods\FNVEdit**.

## Registering FNVEdit in Mod Organizer 2

For FNVEdit to work in Mod Organizer 2, we need to register and configure it.

- Click the **Modify Executables** ![Executables](https://raw.githubusercontent.com/Sigourn/morrowind-sharp/master/MO_Executables.png) button.
- Click the **Add an executable** ![AddExe](https://raw.githubusercontent.com/Sigourn/morrowind-sharp/master/MO2_Add_File.png) button and select *Add from file...*.
- Navigate to FNVEdit's folder (**C:\Games\Fallout New Vegas Mods\FNVEdit**) and double click its .exe file.
- In the **Start In** field, select your **Root** folder (**C:\Games\Fallout New Vegas**).
- In the **Arguments** field, paste **-IKnowWhatImDoing**.
- Click **Apply** and then **OK**.

# MOVING ON TO THE NEXT SECTION

[To Left My Heart In New Vegas >>](https://github.com/Sigourn/newvegas-sharp/blob/main/newvegassharp.md#left-my-heart-in-new-vegas)  
[<< Back to Main](https://github.com/Sigourn/newvegas-sharp/blob/main/README.md#left-my-heart-in-new-vegas)
