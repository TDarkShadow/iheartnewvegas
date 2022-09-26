[<< Back to Readme](readme.md)

> PROTIP: Click on the list icon on the upper left corner of this document to see the index for this guide.

# FALLOUT: NEW VEGAS SETUP

![Banner](images/gog_banner.jpg)

## REQUIREMENTS

- An english copy of the game from [**GOG**](https://www.gog.com/game/fallout_new_vegas_ultimate_edition).
  - Installation instructions are found on the next section. 
- A [**Nexus**](https://users.nexusmods.com/register) account.
  - A free account will work just fine.
- A file archiver, such as [**7-Zip**](https://www.7-zip.org/).
- A text editor, such as [**Notepad++**](https://notepad-plus-plus.org/downloads/v7.9.5/).
- [**DirectX Runtime Libraries**](https://www.microsoft.com/en-us/download/details.aspx?id=8109).
- [**Microsoft VC++ 2013**](https://www.microsoft.com/en-us/download/details.aspx?id=40784) (x86 version) and [**Microsoft VC++ 2015-2019**](https://docs.microsoft.com/en-GB/cpp/windows/latest-supported-vc-redist?view=msvc-170) (x86 and x64 versions).

## INSTALLATION

During installation of the game, make sure you select **English** as the game's language before proceeding with installation.

By default, GOG will install New Vegas to the next directory:
```
C:\Games
```
This will create a folder in the following path, which we will refer to as our **Root** folder. This is where the game's executable (**FalloutNV.exe**), launcher (**FalloutNVLauncher.exe**), and **Data** folder will be found.
```
C:\Games\Fallout New Vegas
```
Should you decide to install New Vegas someplace else, install it outside all default Windows folders (Program Files, Program Files (x86), Desktop, and Documents for example). Windows User Account Control monitors these folders, which can cause problems later on.

## POST-INSTALLATION

The GOG release of New Vegas ships with a language plugin we do not need. Delete **FalloutNV_lang.esp** from the **Fallout New Vegas\Data** folder.

In addition to this, we need to generate fresh .INI files, responsible for the configuration of our game.

- Navigate to **Documents\My Games**, and delete the **FalloutNV** folder, if present.
- Run **FalloutNVLauncher.exe** from the game's **Root** folder.
- Click **OK** to both pop-ups that say **Detecting Video Hardware**.
- Click **Options**, then select the **Ultra** preset option.
- Set **Resolution** to your preference.
- Set **Antialiasing** to **8 Samples**. 
- Click **OK**, then **EXIT**.

Last but not least, you will need a folder where to install our mod manager and keep your mods. I recommend the following path:
```
C:\Games\Fallout New Vegas Mods
```
> ⚠️ Make sure you *don't* create your Fallout New Vegas Mods folder *inside* your Fallout New Vegas folder. Mod Organizer 2 will fail to register your installed mods.

## NEXUS DOWNLOADS

Most mods downloaded for New Vegas will be acquired through [**Nexus**](https://www.nexusmods.com/newvegas). Nexus often provides two types of downloads, accessible through a mod page's **Files** tab.

![Mod manager download](images/mod_manager_download.png)

This option downloads the archive to your mod manager, from which you can install it. Most mods have this download option available, as the vast majority don't require specific installation instructions.

![Manual download](images/manual_download.png)

This option downloads the archive straight to your computer. To install it, you will need to add it to your mod manager, or follow the installation instructions provided by the mod author. For the most part, mods that should be installed *without* the use of a mod manager will have this download option as the only available method.

For this first part of the guide, files will be downloaded using the manual download option exclusively. For the second part of the guide, files will be downloaded using the mod manager download option. All in all, this makes the first part of the guide more tedious in spite of its smaller size.

## UTILITIES AND TOOLS

### [**FNV BSA Decompressor**](https://www.nexusmods.com/newvegas/mods/65854?)

Decompresses the Fallout New Vegas BSAs and repacks them without zlib compression for performance. Also transcodes the .ogg sounds effects to .wav so they work. It also extracts any mp3 files to loose files because they will not play when in a BSA.
- Manually download **FNV BSA Decompressor** (Main files).
- Extract the contents of the archive, and run **FNV BSA Decompressor.exe**.
- Under **Path to the Fallout: New Vegas installation**, select the game's **Root** folder. It's possible that it is detected by default.
- Click **Decompress**.
- **Exit** the program once the process is finished.

> ℹ️ The following lines will have been added to your **Fallout.ini** file, found in **Documents\My Games\FalloutNV**. If you ever encountering missing meshes in-game (recognizable by red exclamation marks), make sure the lines are still present in your .ini.

```
[Archive]
SArchiveList=Fallout - Invalidation.bsa, Fallout - Textures.bsa, Fallout - Textures2.bsa, Fallout - Meshes.bsa, Fallout - Meshes2.bsa, Fallout - Voices1.bsa, Fallout - Sound.bsa, Fallout - Misc.bsa
```

### [**FNV 4GB Patcher**](https://www.nexusmods.com/newvegas/mods/62552?)

Makes Fallout New Vegas 4GB Aware. Automatically loads NVSE if present.
- Manually download **FNV 4GB Patch** (Main files).
- Extract the contents of the archive to the game's **Root** folder.
- Run **FalloutNVpatch.exe**.
- Close the command prompt once the process is finished.

### [**New Vegas Heap Replacer**](https://www.nexusmods.com/newvegas/mods/69779)

Replaces the in-game heap with a faster, more optimized version. It should decrease load times, remove some stutter and slightly improve frame rate. 
- Manually download **NVHR** (Main files).
- Extract the contents of the archive to the game's **Root** folder. Merge when prompted.

### [**xNVSE**](https://github.com/xNVSE/NVSE/releases)

The New Vegas Script Extender expands the engine and scripting capabilities of Fallout New Vegas. This framework is required by many modern mods.
- Click **nvse_6_2_8.7z** under **Assets** to download the file.
- Extract the contents of the archive to the game's **Root** folder. Merge when prompted.

### [**FNVEdit**](https://www.nexusmods.com/newvegas/mods/34703)  

An advanced graphical module viewer/editor and conflict detector. While not required for **New Vegas Sharp**, it is a valuable tool for anyone looking to detect and solve conflicts in their setup.
- Manually download **FNVEdit 4.0.4** (Main files).
- Extract the contents of the archive to **Fallout New Vegas Mods\FNVEdit 4.0.4**.

### [**Mod Organizer 2**](https://www.nexusmods.com/skyrimspecialedition/mods/6194)

An excellent mod manager, offering lots of quality of life conveniences that make modding an easy and quick process.
- Manually download **Mod Organizer 2** (Main files).
- Run the downloaded **Mod Organizer 2** executable.
- When prompted to choose an install location, choose **C:\Games\Fallout New Vegas Mods\MO2**.
- When installation has finished, click **Finish**.
- The **Instance manager** window will appear. Click the **Create a new instance** button on the upper left.
- Choose **Create a portable instance**. You will be asked to select a game to manage.
  - If **New Vegas** is available using the correct filepath (**C:\Games\Fallout New Vegas**), select it. Otherwise, click **Browse...** at the bottom and choose your game's **Root** folder.
- You will be asked to select a folder where data will be stored. The default MO2 folder (**C:\Games\Fallout New Vegas Mods\MO2**) is fine.
- Click **Next** and then **Finish**. Mod Organizer 2 will now launch.

> ℹ️ If you get a pop-up called **Register?**, choose **Yes**. This will allow Mod Organizer 2 to handle Nexus links.

> ℹ️ If you get a pop-up called **Show tutorial?**, choose **No**.

You can hide unnecessary information in Mod Organizer 2 by right clicking on the headers above the installed mods, and unchecking the tabs you don't want to see. I suggest unchecking everything but the **Conflicts**, **Flags**, and **Priority** boxes. You can also click on the **X** to the bottom right of the **load order** panel, hiding unnecessary background information seen on the pane below.

### Adjusting mod and load order

Your installed mods are listed on the pane to the left. This is the order in which New Vegas loads their assets, with mods closer to the bottom overwriting the assets of mods closer to the top (if conflicting assets are present). We will refer to it as our **mod order**.

Your plugins are listed on the pane to the right. This is the order in which New Vegas loads its plugins, with plugins closer to the bottom overwriting the records of plugins closer to the top (if conflicting records are present). We will refer to it as our **load order**.

Reorganize it to read as follows using drag and drop, and enable the plugins.
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
### Adjusting falloutcustom.ini

- Click the **Tools** ![Tools](MO2/MO_ini.png) button, and click **INI Editor**. Select the **falloutcustom.ini** tab.
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

- Click the **Configure profiles** ![Profiles](MO2/MO_Profiles.png) button.
- Check the following options:
  - [X] Use profile-specific Save Games.
  - [X] Use profile-specific Game INI files.
  - [X] Automatic Archive Invalidation.
- With the **Default** profile selected, click **Copy**. Type in **New Vegas Sharp** and click **OK**.
- With the **New Vegas Sharp** profile highlighted, click **Select**.
- The **INI file is read-only** window will appear. Select **Remember my choice** from the dropdown menu, and click **Clear the read-only flag**.

New Vegas Sharp is the profile we will be modding. You can always revert to the **Default** profile to quickly deactivate all installed mods.

### Registering tools in Mod Organizer 2

For **FNVEdit** to work in Mod Organizer 2, we need to register it.
- Click the **Modify Executables** ![Executables](MO2/MO_Executables.png) button.
- Click the **Add an executable** ![AddExe](MO2/MO_Add_File.png) button and choose **Add from file...**.
- Navigate to FNVEdit's folder (**C:\Games\Fallout New Vegas Mods\FNVEdit**) and double click **FNVEdit.exe**.
- In the **Start In** field, choose the game's **Root** folder (**C:\Games\Fallout New Vegas**).
- In the **Arguments** field, paste in the following line.

```
-IKnowWhatImDoing
```

- Click **Apply**.
- Click **OK** to close the window.

### Hiding NVSE and FalloutNVLauncher in Mod Organizer 2

From now on, you should avoid running the game through **nvse_loader.exe**. You should also avoid accidentally running **FalloutNVLauncher.exe**. We can hide both of these from Mod Organizer 2's list of executables.
- Click the **Modify Executables** ![Executables](MO2/MO_Executables.png) button.
- Select **Fallout Launcher**, and tick **Hide in user interface**.
- Select **NVSE**, and tick **Hide in user interface**.
- Click **Apply**.
- Click **OK** to close the window.

## RUNNING THE GAME

From this point on, *always* use Mod Organizer 2 to run the game and to launch any tools you use. Mod Organizer 2 uses a Virtual Files folder, which is kept separate from your New Vegas installation. Failing to run the game through Mod Organizer 2 will mean the game won't register any of the installed mods.

To launch the game, make sure to have the **New Vegas** executable selected from the dropdown menu on the right pane. Then, click on the **Run** button to launch the game.

![Executables](MO2/MO_NewVegas.png)

# MOVING ON TO THE NEXT SECTION

[To New Vegas Sharp >>](main.md)  
[<< Back to Readme](readme.md)
