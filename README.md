# Mabi Pro Lazyfae Mods
 
There is a variety of different mods available here.  You can just download and use all, or pick and choose.  Either way, I strongly recommend you know how to check for outdated mods at the very least, because I will not generally notify and make updates for the public, so much as myself.  So if I'm not active or forget to update via github, crashing is expected.

Link to a guide currently on mabi.pro forums, to finding outdated files.  This doesn't cover manually updating, just seeing if they're a potential problem.<br>
<http://mabi.pro/thread/4136-checking-for-outdated-mods-data-folder#post13806>
<hr></hr>



data/db/ai<br>
If local/aidescdata_human is the only file, it's an auto-play instrument mod.
___
data/cutscene<br>
skip cutscene mods.  As of 10/20/20, does not include custom content skips.  Should not cause crashing or lock ups on any vanilla content.
___
data/layout<br>
skillcomboprogress.xml will move the Combo Card Display to below your character, instead of above.  I believe this uses absolute values and not relative positions, it's set for 1920x1080 display and may instead cause complications on higher resolutions.<br>
characterinfo/main.xml will just rename the tabs on your character sheet, C key by default.
___
data/db/npc<br>
Swaps female blunt ego to look like female bow ego.
___
data/db/charactercondition.xml<br>
Paints Characters in Deadly as red, and Mana Shield as blue.
___
data/db/collectingform.xml<br>
Allows infinite range gather from Sheep, Chickens, and Elemental Sprites.  If you are not next to the creature though, the items will drop roughly half the distance between you.
___
data/db<br>
dungeon_ruin.xml and dungeondb2.xml will remove dungeon fog.  Unlike dll mods, this will still work if you log into a dungeon lobby.  While not related to the mod, you will lose draw distance in game, if you log in to a dungeon lobby and don't head out the entrance and go back in.<br>
dungeon_ruin.xml greatly increases the green color and lighting for Pantay.
___
data/db/gametip.xml<br>
Removes the game tips from loading screen and the tips that pop up when you use demi.
___
data/db/itemdb.xml<br>
Some fairly broad edits here.  Update some items name and/or descriptions.  Applied my own Item Filter, which consists of decreasing text size of items I don't normally pick up as well as removing the item appearance when laying on the ground.  Functionality wise, the items can still be picked up and used.  Fomor Scrolls now tell you the reward amount for collecting the set amount, it does not factor in the server gold bonus.  Evidence of Boss Monster tells you the monster it was dropped from.<br>
data/db/itemdb translations.xml is included here, but by default won't do anything.  It is only meant to add/translate Item Names and Descriptions, does not include Item Filter.  Either rename this to itemdb.xml (requires removing the other itemdb first) so that you get the translations without the filter, or remove this file to keep your data folder clean.
___
data/db/minimapinfo.xml<br>
Adds zoom to minimap regions that will support it.  Removes fog from all minimaps outside of dungeons.  This will reveal places like Solea and Ant Hell.  Also will remove the fog/exploration done for Iria's minimaps.
___
data/db/partyboardcategory.xml<br>
Improves some features allowed for Party Board Restrictions.  More "Total Levels" restrictions are added, and text changed from Accrued Levels or w/e was previously used.  Production Mastery has been moved up on the list, to be right under Total Levels category, should make setting up a production party more convenient.  Carpentry has been added as a possible restriction, and placed right under Production Mastery.  "Mediation" has been fixed to read as "Meditation."<br>
The limits on "Total Levels" are currently set to 100+, 250+, 300+, 500+, 1,000+, and 3,000+.  Reasons: 100+ is int SM, 250+ is HM dungeons, 300+ is adv SM, 500+ more as a fill, 1,000+ for HM missions, and 3,000+ for if things end up added as significantly harder than HM missions.
___
data/db/production.xml<br>
Uncaps most, if not all, auto production.  Do NOT edit max production count, will eat your mats as well as dura consumed but not increase your returns.  Theoretically will add a base herb requirement for Thicket Costume, so that you can now make a Sun Kit Costume Kit without a problem, but have not personally confirmed.
___
data/db/propdb.xml<br>
Will cause most sign text to now float in the air.  Some signs are at awkward heights though, such as Tara's Jousting signs, up by Lileas.  The text will instead float at a peculiar height above or below these signs, there is no proper fix for this without affecting other signs.  Any sign without floating text, should need clicked and servers an extra function besides just hovering over it to see the text.
___
data/db/race.xml<br>
Adds the ability to heal any creature, this does allow Ctrl+targeting with heal to work on anything besides players as that is a skill mod and not race.  Sharp Mind will work as normal on anything that you are in combat with, if the creature is focusing something else though you will not see their skill, ex wolf fighting sheep.  Mimics and Flying Books no longer sleep, can target them and see their name normally, fun note this is done by making the client think they are graywolves.  Names are now revealed on the majority of creatures, there are some creatures that basically server as gfx and can not be attacked and do not serve as an obstruction of any kind so their names remain hidden.  I have given the name Cave Vines to the plants that spawn with Black Herb's final boss.  Recluse Spiders are now just Recluse.  Haunting will now use the Wisp model, instead of Ghost.
___
data/db/undergroundmaze.xml<br>
Maxes draw distance for Ant Hell and Solea.
