
# RWTF Installation

See See [main readme](readme3.md) for general information about this modlist.


## Wabbajack

You will need to have [Wabbajack](https://www.wabbajack.org/) installed. 

## Wabajack info file

You will also need to download the wabbajack info file for this modlist for wabbajack to use:

[RWTF wabbajack file](./wabbajack/Requiem-WTF.wabbajack)


## Paid AE Update CC Content

It's assumed that the additional Creation Club items included in the **paid** Anniversary Edition update is not installed. (This means all the extra CC content that comes with the _paid_ AE update, not the four "everyone gets these for free" items included in general AE update.)

If you have this added CC content, and leave it active, you will have spam of non-reqtified problematic quests in game).

You can remove the extra content in Steam by going to DLC section and un-checking Anniversary Edition DLC.


## Install using Wabbajack

- Run wabbajack, choose "Install from Disk"
- Target Modlist: choose the RWTF wabbajack info file you downloaded
- Modlist Install Location: pick whatever directory you want
- Resource Download Location: pick a directory, or leave the default value
- Click the Run button 
 

## Finish 

The modlist is now installed and ready to play. 

Run ModOrganizer.exe in the install directory, choose "SKSE" from the list next to the Run button in the upper right, and click Run. See the _New Game - Do This_ section for steps to take to start a new game.

The "reqtificator" has already been installed and run, the "requiem for the indifferent.esp" patch as been generated, etc. You don't need to follow the requiem install directions; it's been done for you. 

## New Game - Do This

Post-Game-Start Steps, new game:

1. Let all mod MCM's get recognized and loaded - wait until you're not seeing new messages incoming.

1. Do requiem install and let it finish (open & close inventory menu)

1. OPTIONAL: If using Spell Research: import spells now

1. Use MCM to set mod options you care about (see below for suggestions)  

1. Save game

1. Use mara statue to select start (stadard Alternate Start mod process)


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

(SmoothCam can be jarring for people who have never used it, but is generally liked after allowing some time to adjust to it.)


_Spell Research_:  

If using _Spell Research_, hotkeys are often useful:
- Spell Research > Options > enable hotkey > Home  
- Spell Research Book Options > enable hotkey > End  


## Extending

There is nothing more you _need_ to do, but you are free to continue on with adding additional mods to suit your personal game preferences. If you do install more mods, be sure to use the Reqtificator executable set up for you in Mod Organizer after adding, to re-generate a new "requiem for the indifferent.esp" patch file. 

If you do start adding  your own mods, you are strongly encouraged to read and understand the install directions, compatibilty notes, etc for requiem:

[Requiem Wiki]https://github.com/ProbablyManuel/requiem/wiki

[Nexusmods Requiem](https://www.nexusmods.com/skyrimspecialedition/mods/60888)

[Requiem Announcements](https://probablymanuel.github.io/requiem/)


## Optional add-ons

There are some "tested with this modlist" mods you may want to add. These mods are things the mod author uses, but which change the game in significant ways that many users will not want.

See [optional_additions](./docs/optional_additions.md) for a few known-to-work mods you can add if you like. 

If you add mods, and either have problems or have to generate custom patches, I'd like to hear about the experience so I can see if changes need to be made to this mod. (I'm much more open to removing "stock" mods from the list, vs adding more mods, to improve compatibility.)

