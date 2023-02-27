
# Requiem - Where's The Fire? 

This is a [Wabbajack](https://www.wabbajack.org/) modlist, and you need to use wabbajack to install it. 

This modlist is focused on [Requiem 5.3 "Around The Fire"](https://www.nexusmods.com/skyrimspecialedition/mods/60888) release, and is intended to be "Requiem with minimal other gameplay changes."


[Who is this modlist for?](#who-is-this-modlist-for)

[What's in this modlist?](#whats-in-this-modlist)

[What's not in this modlist?](#whats-not-included)

[Requiem version](#requiem-version)

[Skyrim version](#skyrim-version)

[Installation](#installation)


## Who is this modlist for?

Two groups of people: 

- People who want to "try Requiem" but don't want to build their own mod setup, learn to install requiem, and learn about what mods are compatible with Requiem.

- People who want a "starting mod set for Requiem" without having to select and download a bunch of visual/graphics mods as a starting point. 

The main purpose of this mod is to provide a "just requiem, but in a nice-looking skyrim" experience. This means the mod intentionally leaves out or removes any gameplay changes that have different versions for different tastes (e.g. combat overhaul mods, College of Winterhold reworks, quest mechanics changes, etc).  

The secondary purpose of this mod is to provide a platform for people to add their own requiem-compatible mods as extensions. An effort has been made to make sure that the base modset here allows allows other mods to be installed on top without causing widespread conflicts that need to be patched.

Obviously, if your main intent is not "I want to play Requiem" then this is probably not a modlist you want!


## What's in this modlist?

This modlist started from the wabbajack modlist [Animonculory Visual Overhaul](https://github.com/The-Animonculory/Animonculory-Visual-Overhaul) version 3.2

That modlist is the starting point, with extensive edits, deletions and reworking to produce a "visuals only" shell.

That was then further modified by adding Requiem and a few common supporting mods.

Notable mods from AVO:

- Many, many texture / mesh improvment mods to make visuals look better
- SKSE, bug fixes, unofficial patches for base game, scripting resources, etc
- More HUD / SkyHUD / Infinity UI
- Nemesis animations system
- True directional movement
- Rustic weathers
- CBBE

Notable additions:

- Requiem
- Requiem dragonborn content patches
- Alternate Start (Live Another Life)

Note that this modlist is distinct from AVO, and maintained separately. Changes to AVO will not affect this modlist, and any such changes will likely not be migrated into this modlist. 


## What's _NOT_ included? 

- ENB's  
- Other lighting adjustments  
- Combat mods
- Content mods (Cutting Room Floor, etc)
- Survival / needs mods (Frostfall, campfire, hunterborn, realistic needs and diseases, etc)

These types of things are not included because (a) not every requiem player will want them, (b) for players who do, there's no single "right" choice from many alternatives, and (c) including them will likely create conflicts (needing patches) for players who want to add other mods.


## Requiem version

This modlist was built with Requiem 5.3.1 "Around the Fire"

[Requiem Mod](https://www.nexusmods.com/skyrimspecialedition/mods/60888)  

Later requiem releases may or may not be compatible without updates. 


## Skyrim version

This modlist was built to run on SkyrimSE.exe version 1.6.640.0  
This modlist assumes you have the Anniversary Edition, the free "everyone gets it" update.  
It does not assume/use the PAID Anniversary Edition upgrade, which adds many more Creation Club items.   

If the skyrim exe version changes, it will likely break the SKSE version included in this modlist.

## Installation

See [installation instructions](install.md).


## Support / Questions

This modlist, for now, is provided "as is" in the hope that it will be useful to someone. 

This is a first release, and may contain bugs or issues. 

You're welcome to post questions to [skyrimrequiem](https://www.reddit.com/r/skyrimrequiem/) reddit group, or to DM user AHostOfIssues there. 

You're also welcome to post issues in the [GitHub project](https://github.com/billpatterson/modding/tree/main/rwtf-modlist)


## External 

This modlist needs a couple of generated-content files (textures, LOD's, etc) placed where Wabbajack can find them. 

They are hosted on Nexusmods [here](https://www.nexusmods.com/skyrimspecialedition/mods/85928/)

You don't need to download them, Wabbajack will pull them during install. 


## Ugly Details

If you're interested in all the ugly details about how this modlist was created, starting from AVO, I've included some of my personal notes:

[Altering AVO](./docs/other_info/edit_AVO.txt)

[Adding Requiem](./docs/other_info/add_requiem.txt)
