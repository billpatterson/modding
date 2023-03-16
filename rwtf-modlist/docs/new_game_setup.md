
# New Game Setup

When starting a new game, you need to trigger Requiem activation, and pick a starting scenario.

You may also want to change some MCM settings in your game before going further. 


## New Game - Do This

Post-Game-Start Steps, new game:

1. Let all mod MCM's get recognized and loaded - wait until you're not seeing new messages incoming.

1. Do requiem install and let it finish (open & close inventory menu)

1. OPTIONAL: If using Spell Research: import spells now

1. Use MCM to set mod options you care about (see below for suggestions)  

1. Save game

1. Use/activate mara statue to select start (stadard Alternate Start mod process), then sleep in the bed to activate your choice


## Suggested MCM settings


_Take Notes:_

- Set open key to N
- Set new entry to N

_Requiem_: **Important**: 

- Atmosphere > Cell respawn time: 365 (default is 30)

_Requiem_: suggested:

- Atmosphere > Timescale : 14  
- Atmosphere > poisons without visuals  
- Atmosphere > fast travel allowed  

_SmoothCam_:  

If the in-game camera "floats" too much for your liking, turn off or try changing settings to half default value:  
- MCM > SmoothCam > Third Person > Interpolation > Min Follow Rate
- MCM > SmoothCam > Third Person > Interpolation > Max Follow Rate.

If that's still not enough, you can disable SmoothCam entirely.

(SmoothCam can at first seem jarring for people who have never used it, but is generally liked after allowing some time to adjust to it.)


_Spell Research_:  

If using _Spell Research_, hotkeys are often useful:
- Spell Research > Options > enable hotkey > Home  
- Spell Research Book Options > enable hotkey > End  

_Sound_:  
Settings > Audio  
True Storms adds some volume controls for rain and thunder. You may want to turn down the defaults to better suit other Skyrim volume settings. In particular, the "rain while inside buidings" sound is a bit loud.


## Immersive Equipment Displays

_Activation Key:_

IED uses Backspace key as activator, by default. This is usually fine, but in Enchanting when renaming an item it can make text editing frustrating as the shortcut key isn't blocked here. 

Suggested: change the key to apostrophe or backslash or something similar.

To do that, you need to edit the mod's .ini file, and you need the right key code.

.ini file: in Animations section in Mod Organizer, right click on Immersive Equipment Displays, choose Open In Explorer. Look in SKSE\plugins\ folder for ImmersiveEquipmentDisplays.ini to edit.

Key codes: get from website noted in that .ini file:   https://www.creationkit.com/index.php?title=Input_Script#DXScanCodes

In .ini file, change this line to set your new activation key:  
ToggleKeys=0x0E

Semicolon:  
ToggleKeys=0x27

Apostrophe:  
ToggleKeys=0x28

Backslash:  
ToggleKeys=0x2B  

F6:  
ToggleKeys=0x40  