# MHW-ReShade-DX12-Fix

This is a mirror of the information posted on my Nexus Mods account. 

### The Instructions
This guide assumes you already have Mod Organizer 2 installed and configured for Monster Hunter: World. These instructions are only to show you how to get ReShade working with the DX12 version of MHW without using any weird series of executables.
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
