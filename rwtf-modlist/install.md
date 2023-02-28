
# RWTF Installation

See See [main readme](readme.md) for general information about this modlist.

When the install is done, you 

## Wabbajack

You will need to have [Wabbajack](https://www.wabbajack.org/) installed. 

## Wabajack info file

You will also need to download the wabbajack config file for this modlist for wabbajack to use:

[RWTF wabbajack file](https://github.com/billpatterson/modding/blob/main/rwtf-modlist/wabbajack/RWTF_wabbajack.7z)

Download that file and unzip it. It contains the _Requiem-WTF.wabbajack_ file you need to feed into Wabbajack to tell it what to install. 


## Paid AE Update CC Content

This modlist does not use the additional Creation Club items included in the **paid** Anniversary Edition update. (This means all the extra CC content that comes with the _paid_ AE update, not the four "everyone gets these for free" items included in general AE update.)

If you have this added CC content, and leave it active, you will have spam of non-reqtified problematic quests in game).

You can remove the extra content in Steam by going to DLC section and un-checking Anniversary Edition DLC.


## Install using Wabbajack

Locate the "Requiem-WTF.wabbajack" file.

Run wabbajack, then...
- choose "Install from Disk"
- Target Modlist: choose the RWTF wabbajack info file you downloaded
- Modlist Install Location: pick whatever directory you want
- Resource Download Location: pick a directory, or leave the default value
- Click the Run button 

Wait for wabbajack to download all needed mods (can take a while; a paid Nexusmods account is suggested for faster downloads; you can get for a few dollars a month and cancel any time).


## Finish 

The modlist is now installed and ready to play. 

Run ModOrganizer.exe in the install directory, choose "SKSE" from the list next to the Run button in the upper right, and click Run. See the _New Game - Do This_ section for steps to take to start a new game.

The "reqtificator" has already been installed and run, the "requiem for the indifferent.esp" patch as been generated, etc. You don't need to follow the requiem install directions; it's been done for you. 

When you start a new game, you need to do some initialization for your character, and may want to make some in-game MCM settings changes. 

See [new game setup](./docs/new_game_setup.md) for some suggestions. 

If you're an experienced Requiem/Alt-Start player you can ignore this.  


## Removing Optional Mods

A few mods included in the list are intended to be removed if you don't want them. 

See [removing defaults](./docs/removing_defaults.md) for (easy) directions. 


## Extending

There is nothing more you _need_ to do, but you are free to continue on with adding additional mods to suit your personal game preferences. If you do install more mods, be sure to use the Reqtificator executable set up for you in Mod Organizer after adding, to re-generate a new "requiem for the indifferent.esp" patch file. 

If you do start adding  your own mods, you are strongly encouraged to read and understand the install directions, compatibilty notes, etc for requiem:

[Requiem Wiki](https://github.com/ProbablyManuel/requiem/wiki)

[Nexusmods Requiem](https://www.nexusmods.com/skyrimspecialedition/mods/60888)

[Requiem Announcements](https://probablymanuel.github.io/requiem/)


## Optional add-ons

There are some "tested with this modlist" mods you may want to add. These mods are things the mod author uses, but which change the game in significant ways that many users will not want.

See [optional_additions](./docs/optional_additions.md) for a few known-to-work mods you can add if you like. 

If you add mods, and either have problems or have to generate custom patches, I'd like to hear about the experience so I can see if changes need to be made to this mod. (I'm much more open to removing "stock" mods from the list, vs adding more mods, to improve compatibility.)

