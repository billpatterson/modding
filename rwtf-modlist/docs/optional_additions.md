
# Optional Additions

Several additional mods that have been tested as "add ons" and confirmed to work with this modlist.  

(Things the modlist author adds post-install for use in personal setup.)

[Missives](#missives)  
[JK's Skyrim Exteriors](#jks-skyrim-exteriors)  
[Spell Research](#spell-research)  
[Misc](#misc)  
[College Overhaul](#college-overhaul)  
[Book Covers of Skyrim](#book-covers-of-skyrim) (information only)  
[WACCF/ACE/CCOR](#waccf-ace-ccor) (information only)  
[Campfire/Frostfall](#campfire/frostfall) (information only)  


## Missives

Add in "RWTF - Misc" section:
+ [Missives](https://www.nexusmods.com/skyrimspecialedition/mods/17576) (base mod)
+ [Missives notes retexture](https://www.nexusmods.com/skyrimspecialedition/mods/46201)
+ [Missives - Solstheim Patch SE](https://www.nexusmods.com/skyrimspecialedition/mods/26788)
+ [Missives the witcher board](https://www.nexusmods.com/skyrimspecialedition/mods/47097)
Note: "witcher board" gets overwritten/ignored if not at bottom of missives addons list.

Add in "RWTF - Requiem" patches group:
+ [Requiem Missives extended patch](https://www.nexusmods.com/skyrimspecialedition/mods/62742?tab=files)

Note: "Headhunter", "Requiem - RMB Patches - Headhunter - Missives"  
Installing this popular companion to Missives caused obtaining quests from Steward & Inkeeper to behave oddly. Should be compatible, though, so experiment if you like. 

Note: Carriage and Ferry Travel Overhaul mod causes conflict with Missives (carriage drivers as quest targets). There is a patch on nexusmods if you want to add CFTO, and if patched should be fine.


## JK's Skyrim Exteriors

+ [JK's Skyrim all in one](https://www.nexusmods.com/skyrimspecialedition/mods/6289)  
Place mod/.esp in the "Settlements" section in Mod Organizer
Note: needs to be before Missives, if using.

+ [Missive JK Skyrim patch](https://www.nexusmods.com/skyrimspecialedition/mods/22380)
After missives base mod, before missive add-ons and patches

Note: Carriage and Ferry Travel Overhaul mod has conflict with JK's Skyrim, but JK's Skyrim page has a patch file. 


## Spell Research

### Compatibility warning:
Spell Research tends to produce "needs a patch" for _ANY_ mod related to magic/spells. If you plan to install magic overhauls, etc, be sure there's a compatibility patch before deciding to install Spell Research. 

### Gameplay effect

Installing SR as described below produces the following gameplay experience:

- Spell research features for research, spell composition, crafting scrolls and tomes, analyzing ingredients  
- Spell research features for studying found artifacts and tomes  
- Spell books still exist, and teach spells when read  
- Spell books still for sale at the usual vendors  
- Requiem perks still grant opportunity to learn two spells when taking magic perks  
- Spell research materials can be found as loot (e.g. paper and quills in a cabinet in world)  

With my requiem-5-patch patch (supplementary patch to extend requiem-5 patch):  
- Spell research materials (paper, quills, ink, alembics, cauldrons) for sale at appropriate vendors  
- Spell research loot can be found in some chests (tomes, artifacts)  

In-game, you can learn spells by research or buying spell tomes. _Suggested:_ learn spells from tomes you find as loot, but never buy spells from vendors. Allows you to learn some new archetypes to study without breaking SR intent.

Note: There is a mod to make spell books just teach SR archetypes rather than teaching spells. If you want to use this, you will have to patch HEAVILY for Requiem compatibilty. Not to be undertaken lightly!

### Installing

NOTE: Spell research must go above Requiem, then requiem, then requiem SR patches. 

Add "RWTF - spell research" section above Requiem section in Mod Organizer.

Add the folling mods to "RWTF - spell research" section:  
+ [Spell Research 2.2.2](https://www.nexusmods.com/skyrimspecialedition/mods/20983)  
+ [Spell Research - Experience Book](https://www.nexusmods.com/skyrimspecialedition/mods/28355) (just "book v1.7.4")  
+ [Enhanced Graphics for SR Exp Book](https://www.nexusmods.com/skyrimspecialedition/mods/39947)  
+ [Spell Research - Convenience Add-On](https://www.nexusmods.com/skyrimspecialedition/mods/28953) (just "Spell Resarch Add-On")  
+ [Spell Research - Spell Composing](https://www.nexusmods.com/skyrimspecialedition/mods/65756)  
+ [Spell Research - Ultimate Add-On Patch](https://www.nexusmods.com/skyrimspecialedition/mods/66538) (combined patches for all the SR extension/tweak mods above)


Intended load order (with .esp's in same order in Plugins list):  
Spell Research  
Spell Research - Experience Book  
Enhanced Graphics for Spell Research  Experience Book  
Spell Research - Convenience Add-On  
Spell Research - Spell Composing  
Spell Research - Ultimate Add-On Patch  

The experience book with enhanced graphics makes a *big* difference to enjoying SR, the Convenience Add-On is "quality of life", spell-composing UI is somewhere in the middle.

_Requiem Patch_:  
Add the following mod with other requeim patches:   
+ [Spell Research - Requiem 5 patch](https://www.nexusmods.com/skyrimspecialedition/mods/57178)  

_Note:_ The SR requiem-5 patch does *not* patch the vendors (mages) in the College of Winterhold to sell materials/tomes, and does not patch most "loot lists" to allow player to find SR-items in loot chests. Doesn't prevent SR from working properly, but does limit you by removing things you're intended to be able to find/buy.

TODO: I'm building a custom patch to fix this, but it's not uploaded anywhere yet.

*Re-run the Requitificator,* as a new "requiem for the indifferent.esp" patch is required now!


### In game: spell import

When you start a new game, you *must manually trigger spell import*. Do this in the Alternate Start "Mara statue room" when game starts, after triggering requiem install.

Go to MCM > Spell Research > Options > Import Spells

Let it run (lengthy) until you get final confirmation.

The spell import process is largely invisible, with just occasional message text. It's not done until you see the "Spell Research: All Spells Imported - OK" dialog! Be patient.


## Misc 

+ Fog Mesh Remover  
Put at very bottom (overwrites only retextures from "Little Things", safe to remove mid-game)

+ Magic Sneak Attacks  
Put with Honed Metal, Alt Start, etc

+ Requiem - Magic Sneak Attacks  
Put with Requiem patches

+ No kill cams  


## College Overhaul

+ Magical college of Winterhold
Put above requiem with Hone Metal, though does not cause conflicts with requiem.

Note: had tried: Immersive College of Winterhold. Removed. Didn't like door auto-colsing (exacerbates "find person X" problem), and it edited vendor chests of college NPC's which requiem also does, causing conflict.


## Book Covers of Skyrim

AVO includes the mod "Book Covers Skyrim Updated", which is different than older "book covers of skyrim" mod. 

You therefore do _NOT_ want to install patches for the old mod:
- Requiem Dragonborn - Book Covers
- Requiem Patch Central patch

Ignore those, do not install them. 

There is currently no requiem patch for the newer BCS-Updated mod. 

Leaving "Book Covers Skyrim Updated" and putting requiem "last" in load order means some BCS-Updated changes will get inored, which is fine. 


## WACCF/ACE/CCOR

These mods are *intentionally not included* in the modlist.

Install if you like, but note [this comment](https://www.reddit.com/r/skyrimrequiem/comments/101g9i3/requiem_53_waccfaceccor_patches_updated) from the Requiem patch author, noting that future versions may not be patched.

Also, these mods are "patch generators" meaning they cause a need for patching due to conflicts with many other mods. They're good mods, you may want them, but they're intentionally left out of this modlist to reduce complications. 

## Campfire/Frostfall

As of this writing, these are being left out due to (a) changes not everyone may want, (b) need for patching with other mods users may want to add in, and (c) issues with current releases (particularly MCM/SKSE issues with interface to change settings). 

This may have improved by the time you're reading this. 

You are free to install, as working versions should not conflict with other things in this modlist (e.g. modlist disables Creation Club survival mode so that won't conflict, etc).
