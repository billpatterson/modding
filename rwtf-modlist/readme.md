
# Requiem - Where's The Fire? 

This is a [Wabbajack](https://www.wabbajack.org/) modlist, and you need to use wabbajack to install it. 

This modlist is focused on [Requiem 5.3 "Around The Fire"](https://www.nexusmods.com/skyrimspecialedition/mods/60888) release, and is intended to be "Requiem with minimal other gameplay changes."


[Who is this modlist for?](#who-is-this-modlist-for)

[What's in this modlist?](#whats-in-this-modlist)

[What's not in this modlist?](#whats-not-included)

[Images](./images/)

[Requirements](#requirements)

[Installation](#installation)

[New game suggestions](#new-game-suggestions)

[Removing optinal mods](#removing-optional-mods)


## Who is this modlist for?

Two groups of people: 

- People who want to "try Requiem" but don't want to build their own mod setup, learn to install requiem, and learn about what mods are compatible with Requiem.

- People who want a "starting mod set for Requiem" without having to select and download a bunch of visual/graphics mods as a starting point. 

Made to be playable on "ok" PC's (no heavy scripting, no ENB, etc).

The main purpose of this mod is to provide a "just requiem, but in a nice-looking skyrim" experience. This means the mod intentionally leaves out or removes any gameplay changes that have different versions for different tastes (e.g. combat overhaul mods, College of Winterhold reworks, quest mechanics changes, etc).  

The secondary purpose of this mod is to provide a platform for people to add their own requiem-compatible mods as extensions. An effort has been made to make sure that the base modset here allows allows other mods to be installed on top without causing widespread conflicts that need to be patched.

Obviously, if your main intent is not "I want to play Requiem" then this is probably not a modlist you want!


## What's in this modlist?

This modlist started from the wabbajack modlist [Animonculory Visual Overhaul](https://github.com/The-Animonculory/Animonculory-Visual-Overhaul) version 3.2

That modlist is the starting point, with extensive edits, deletions and reworking to produce a "visuals only" shell.

That was then further modified by adding Requiem and a few common supporting mods.

Notable mods from AVO:

- Many, many texture / mesh improvement mods to make visuals look better
- SKSE, bug fixes, unofficial patches for base game, scripting resources, etc
- More HUD / SkyHUD / SkyUI
- Nemesis animations system
- True directional movement
- Rustic weathers
- CBBE
- SmoothCam
- Immersive Equipment Displays

Notable additions:

- Requiem
- Requiem dragonborn content patches
- Alternate Start (Live Another Life)
- Honed Metal
- Audio overhaul / immersive sounds compendium
- Take notes - journal of the dragonborn
- Accurate Realistic Fast Travel Time
- Dynamic Things Alternative
- HUD preset, main menu + music replacer

All of these additions (except Requiem) are easily removable, and [directions](./docs/removing_defaults.md) to do so are provided in install directions. Also, there are [directions](./docs/optional_additions.md) for additional things you may want to add (Missives, Spell Research, etc) that have been tested with this list.
 
_Note:_ This modlist is distinct from AVO, and maintained separately. (Changes to AVO will not affect this modlist, and any such changes will likely not be migrated into this modlist. 

Mods included: [full list](https://loadorderlibrary.com/lists/requiem-wtf)


## What's _NOT_ included? 

- ENB's  
- Other lighting adjustments  
- Combat mods
- Content mods (Cutting Room Floor, etc)
- Survival / needs mods (Frostfall, campfire, hunterborn, realistic needs and diseases, etc)

These types of things are not included because (a) not every requiem player will want them, (b) for players who do, there's no single "right" choice from many alternatives, and (c) including them will likely create conflicts (needing patches) for players who want to add other mods.


## Requirements

[Wabbajack](https://www.wabbajack.org/) to install it.

_PC specs:_

Modlist is intended to be played on "ok" PC's. There's no ENB, no heavy scripting, etc.

I run it at 4k resolution without problems on this PC:  
CPU: AMD Ryzen 5 5600  
GPU: Nvidia GTX 1660 ti  


### Requiem version

This modlist was built with Requiem 5.3.1 "Around the Fire"

[Requiem Mod](https://www.nexusmods.com/skyrimspecialedition/mods/60888)  

Later requiem releases may or may not be compatible without updates. 


### Skyrim version 

This modlist was built to run on SkyrimSE.exe version 1.6.640.0  

This modlist assumes you have the Anniversary Edition, the free "everyone gets it" update.  

It does not assume/use the PAID Anniversary Edition upgrade, which adds many more Creation Club items.   

If the skyrim exe version changes, it will likely break the SKSE version included in this modlist.



## Installation

See [installation instructions](install.md) for instructions.


## New Game Suggestions

When you start a new game, you need to do some initialization for your character, and may want to make some in-game MCM settings changes. 

See [new game setup](./docs/new_game_setup.md) for some suggestions. 

If you're an experienced Requiem/Alt-Start player you can ignore this.  


## Removing Optional Mods

Some of the mods included in the list are intended to be removed if you don't want them. 

Removal is easy, and simply requires deactivating mods (no removing custom paches, etc)

See [removing defaults](./docs/removing_defaults.md) for directions. 



## Advanced Details

This modlist needs a couple of generated-content files (textures, LOD's, etc) placed where Wabbajack can find them. You don't need to download them, Wabbajack will pull them during install.

They are hosted on Nexusmods [here](https://www.nexusmods.com/skyrimspecialedition/mods/85928/)

If you're interested in all the ugly details about how this modlist was created, starting from AVO, I've included some of my personal notes:

[Altering AVO](./docs/other_info/edit_AVO.txt)

[Adding Requiem](./docs/other_info/add_requiem.txt)

