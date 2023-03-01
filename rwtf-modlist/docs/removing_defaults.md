
# Removing Defaults

Several of the installed mods are intended to be easily removed if you don't want them.

This page describes things you can remove/disable without worrying about destabilizing the mod set.


## HUD Mods

Some default HUD changes are made by RWTF. You can/should edit them to your liking.

### Base interface

Inventory/spell screens, dialog boxes, etc:
- SkyUI  
- Dear Diary Dark Mode (white text)  
- A Matter of Time  

Start menu + music:  
- Main menu texture and music replacer - Windy Malukah

If you want to "clean reset" the UI, you'll want to remove those, as well as the Hud Alterations mods below.

You don't need to re-run the Reqtificator when adding/removing any of these UI mods.

 
### HUD Alterations

To remove all HUD mods and start fresh to install your own... 

Deactivate or unistall from "RWTF - HUD" section:

- moreHUD SE  
- moreHUD inventory edition  
- SkyHUD  
- Paramount versitile HUD presets  

No other changes necessary. Replace with your preferred HUD setup.

Note that *SmoothCam has some HUD settings!* See in-game MCM if keeping SmoothCam.

Re-running Reqtificator not necessary in this case, but doesn't hurt!

### Tweaking

You can leave the existing mods and tweak behavior by editing:

  .../interface/skyhud/skyhud.txt 

Note that this file may be provided by several mods, so finding the "winning" copy to edit is important!

Mods known to provide a copy of this file: 

- Paramount - Versatile HUD Presets
- Dear Diary Dark Mode (white text)

In the default setup, Dear Diary Dark Mode comes last, so its copy of the file "wins" in load order. 

*Suggesion:* find the copy of the file you want to edit, copy it. Save the new copy as:

   <mod organizer folder>/overwrite/interface/skyhud/skyhud.txt
   
Freely edit that copy to have all your changes overwrite any copy of the file provided by mods.

See SkyHUD nexusmods page for information about settings you can alter. 


## Alternate Start

Deactivate or uninstall from "RWTF - Misc" section:

- Alternate Start - Live Another Life - SSE

- New Beginnings - LIve Another Life Extension SSE

Re-run Reqtificator executable in Mod Organizer to update your "requiem for the indifferent.esp" patch.

No other changes needed. 


## Honed Metal

Deactivate or unistall from "RWTF - Misc" section:

- Honed Metal Community AE patch
- Honed Metal Revoiced

Re-run Reqtificator executable in Mod Organizer to update your "requiem for the indifferent.esp" patch.

No other changes needed. 


## Misc

Some other one-off mods you may want to remove: 

- Take Notes
- Dear Diary Dark Mode (white text)
- Survival Mode Prompt Removed
- Accurate and Realistic Fast Travel Time
- Saints and Seducers Begone
- Requiem - Resist and Regen Tweak
- Requeim - small tweaks Seducers

Simply deactivate or uninstall some/any of these mods; no other changes needed.

Re-run Reqtificator executable in Mod Organizer to update your "requiem for the indifferent.esp" patch after removing any/all of these. 
