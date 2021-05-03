# Monster Hunter: World Reshade Fix for Mod Organizer 2

### What do these steps do / why would I need them?
ReShade has not worked with DX12 in Monster Hunter: World for a few months now. There is a fix already on this website, but the existing fix does not work with Mod Organizer 2 due to the way that fix injects the ReShade DLLs. These instructions below should have the same result as the fix that already exists on the site but it will be accomplished with Mod Organizer 2, a program with an already established reputation.

### Important note
This guide assumes you already have Mod Organizer 2 installed and configured for Monster Hunter: World. These instructions are only to show you how get ReShade working with the DX12 version of MHW while using MO2 and without using any weird series of executables. I will not provide support for installing installing MO2 or getting it to work with MHW, sorry.

In theory, you could just install all your mods manually to nativePC as normal then use MO2 and the steps below to launch MHW. But I have not actually tested that. And that would not be taking advantage of the many strengths of MO2.

### Requirements
  * Mod Organizer 2 v2.4.1 or greater.
  * MO2 already configured for Monster Hunter: World.



## Instructions
1.	Install ReShade for Monster Hunter: World as normal. The ReShade preset you want to install might have special instructions for installing ReShade and you should follow those.
2.	Launch Mod Organizer 2.
3.	Hit CTRL + E to open the window to modify executables.
4.	Select your Monster Hunter: World executable (click it once).
5.	Tick the box down below labeled “Force load libraries”.
6.	Click “Configure Libraries” to the right of that checkbox. A window will appear.
7.	Click “Add Row” on the bottom.
8.	Click the “…” directly to the right of the box labeled “Process name”.
9.	Browse to the folder Monster Hunter: World is installed to and choose “MonsterHunterWorld.exe”, then click “Open”.
10.	Click the “…” directly to the right of the box labeled “Library to load”.
11.	Browse to the folder Monster Hunter: World is installed to and choose “ReShade64.dll”.
12.	Repeat steps 7 – 11 choosing “MonsterHunterWorld.exe” for the process again, but this time choose “dxgi.dll” for the library.
13.	Make sure both checkboxes on the left side are checked, then press “OK”. 
14.	Back at the “Modify Executables” window, click “Apply”, then “OK”.
15.	Run Monster Hunter: World through Mod Organizer 2. You should see the ReShade banner appear 10 – 15 seconds after the game is loaded, before you get to the main menu.



I tested this for about 10 hours; both ReShade and all MO2 mods seemed to work correctly. If I forgot something, please let me know.
These instructions are mirrored on my Nexus Mods page, https://www.nexusmods.com/monsterhunterworld/mods/5345/
