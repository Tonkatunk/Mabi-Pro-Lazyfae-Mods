# Mabi Pro Lazyfae Mods
 
If you have an existing data folder, BACK IT UP BEFORE DOWNLOADING!!! This is just a copy/paste, if you have existing files that conflict with my mods, the copy/paste will replace your files. So make sure you have your data folder backed up to prevent losing mods you use.<br>

There is a variety of different mods available here.  You can just download and use all, or pick and choose.  To install all, just download from releases, then move the "data" folder into your Mabi Pro directory, that's all. You can safely remove any other files/folders, as well as any desktop.ini files you find. To uninstall, you do need to manually remove the data folder files. You can check which ones from the github or if you kept a backup of the data folder somehwere on your pc.<br>

Link to a guide currently on mabi.pro forums, to finding outdated files.  This doesn't cover manually updating, just seeing if they're a potential problem.<br>
<http://mabi.pro/thread/4136-checking-for-outdated-mods-data-folder#post13806>

___
___
___


EDIT: There were some mods I kept in the past, such as dungeon defog or minimap zooms, that with kanan or astral are redundant. They have been removed.

data/db/ai<br>
Removed. Used to be an auto-play instrument mod, can look elsewhere if you really need it.
___
data/db/cutscene<br>
skip cutscene mods.  As of 10/20/20, does not include custom content skips.  Should not cause crashing or lock ups on any vanilla content.<br>
Look for data/db/cutscene/c3/cutscene_c3g12_s#12_1_fight_nuadha.xml.  If you have this file, remove it.  The scene this skips, causes a soft lock.  It skips the intro to the Nuadha fight scene for G11, and doing this will cause Nuadha to not spawn, making it impossible to finish the quest, ie soft lock.
___
data/db/layout<br>
skillcomboprogress.xml will move the Combo Card Display to below your character, instead of above.  I believe this uses absolute values and not relative positions, it's set for 1920x1080 display and may instead cause complications on higher resolutions.<br>
characterinfo/main.xml will just rename the tabs on your character sheet, C key by default.
___
data/db/npc<br>
Swaps female blunt ego to look like female bow ego.
___
data/db/aircraftdesc.xml<br>
EDIT: Removed.<br>
Enhances flying pet's ascension, descension, and turning speeds as well as making them all constant.  If you want to adjust any of the speeds for yourself, look for rising, drop, or rotation.  Use replace all in a text editor and change the numbers in the quotes, higher is faster and lower is slower.  Do not touch velocity!!
___
data/db/charactercondition.xml<br>
Paints Characters in Deadly as red, and Mana Shield as blue.
___
data/db/collectingform.xml<br>
EDIT: Removed.<br>
Felt niche and wasn't interested in maintaining it. If anyone wants to pick it up, cross reference the production items in collecting form, with the data/db/itemd.xml and get the names. The name there should be enough to tell you what you're changing, aka enough context for the actions.
___
data/db<br>
EDIT: Removed.<br>
dungeon_ruin.xml and dungeondb2.xml will remove dungeon fog.  Unlike dll mods, this will still work if you log into a dungeon lobby.  While not related to the mod, you will lose draw distance in game, if you log in to a dungeon lobby and don't head out the entrance and go back in.<br>
dungeon_ruin.xml greatly increases the green color and lighting for Pantay.
___
data/db/gametip.xml<br>
Removes the game tips from loading screen and the tips that pop up when you use demi.
___
data/db/itemdb.xml<br>
Some fairly broad edits here. Applied my own Item Filter, which consists of decreasing text size of items I don't normally pick up as well as removing the item appearance when laying on the ground. Functionality wise, the items can still be picked up and used.<br>
Fomor Scrolls now tell you the reward amount for collecting the set amount, it does not factor in the server gold bonus.  Evidence of Boss Monster tells you the monster it was dropped from.<br>
Phoenix feathers were renamed to Life Crystal and given a unique description.  There other mods to change appearance, data/gfx/char/item/mesh/item_feather_001.pmg and data/gfx/imgage/item_phoenix_feather.dds<br>
I had previously edited some untranslated items, with names/descriptions I could find from other sources, due to a hiatus I have reverted this and may re-translate in the future. Wanted to minimize potential problems during a large update.<br>
Item Bags will just give you the total bag space, so it will look like Item Bag (80) instead of Item Bag(8x10) for example. Also attempting to differentiate between bag types, you can't equip multiple different bags but not two bags of the same type. Wanted this distinction to be clearer.<br>
___
data/db/minimapinfo.xml<br>
EDIT: Zoome will not be included anymore. Adds zoom to minimap regions that will support it. Removes fog from all minimaps outside of dungeons.  This will reveal places like Solea and Ant Hell.  Also will remove the fog/exploration done for Iria's minimaps.
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
EDIT: Removed<br>
NOTICE FROM PRO'S STAFF: Do not edit race.xml for anything outside of visual edits.  Targeting sleeping mimics and books is allowed at this point in time.<br>
Mimics and Flying Books no longer sleep, can target them and see their name normally.  Haunting will now use the Wisp model, instead of Ghost.<br>
Word of warning to mod creators/editors.  While I have checked and got the okay from a mod, about editing race for mimics/books, that does not mean it is a favorable mod, only tolerated.  Please be respectful of our staffs' decisions, don't create drama, and don't go beyond the permitted edits.
___
data/db/undergroundmaze.xml<br>
EDIT: Removed<br>
Maxes draw distance for Ant Hell and Solea.
___
data/gfx/char<br>
Elf, Giant, and Human folders: Dummy meshes, minimizing characters makes them invisible save for weapons.  race/male/wear has swapped underwear files, unused alternate underwear models.
___
data/gfx/char/item/anim<br>
Item drop animations are removed, so all items instantly appear on the ground.
___
data/gfx/char/item/mesh<br>
item_arenacoin.pmg increases coin size, this increases Red Coin size without having to worry about breaking frequently from updates.  Side-effect of increasing arena coin sizes as they share the model.  item_bosskey and item_roomkey files to increase dungeon room key size.  item_none is only used if you have the data/db/itemdb.xml for the item filter, if you removed the item filter you can safely remove this too.  item_feather_001.pmg changes the phoenix feather model when on the ground.
___
data/gfx/fx/char_effect<br>
Removes the quest arrow, that shows you the direction to the currently highlighted quest.
___
data/gfx/fx/effect/c2_g5_s3_props.xml<br>
Removed waterfall fx.
___
data/gfx/fx/effect/c2_g6_s1_snowfield.xml<br>
Removed blizzard's snow fx.
___
data/gfx/fx/effect/c2_g6_s2_magiceffect.xml<br>
Removed Fusion bolt fx.
___
data/gfx/fx/effect/c2_g8_s3_skill_mana_shield<br>
Removes mana shield efffect when MS is broken.  Has entry on wings of eclipse?
___
data/gfx/fx/effect/c3_g9_s2_monster_spider12.xml<br>
Removed sulfur spider smoke fx.
___
data/gfx/fx/effect/c3_g10_s1_cloud.xml<br>
Modified Rain Casting fx.  Previously used it to remove rain clouds, which destroys and FX in Reoite.  Altered a cloud setting instead.
___
data/gfx/fx/c3_g10_s1_others.xml<br>
Removed waterfall fx.  Removed Lance Spark fx.
___
data/gfx/fx/effect/c3_g10_s2_proximity.xml<br>
Review me!
___
data/gfx/fx/effect/c3_g11_s1_others.xml<br>
Removed Rath Castle's Cerberus glowy eyes, to reduce FPS spikes from glowing effects.
___
data/gfx/fx/effect/c3_g12_s4_pet_effect.xml<br>
Removed Tiger's Eye glow effect, to remove the FPS spikke in Rath Castle when it is summoned.
___
data/gfx/fx/effect/c4_g13_dragon_summon.xml<br>
Removed dragon horn fx.
___
data/gfx/fx/effect/c4_g13_s2_pet_fx.xml<br>
Removed Crystal Deer fx.
___
data/gfx/fx/effect/c4_g14_s3_fire_horse<br>
Removed most of Firehorse's fx.  They don't seem to exist, but the files are still present so I carried the mod over from my Live version.
___
data/gfx/fx/effect/c4_g16_pet_ice_dragon.xml<br>
Removed some of Ice Dragon Pet's fx.
___
data/gfx/fx/effect/c5_boss_X_dragon.xml<br>
Removed White and Black Dragon fx.  Again, don't seem to exist but files do, so carried over from Live.
___
data/gfx/fx/effect/c5_doll_effect.xml<br>
Removed Puppet fx.
___
data/gfx/fx/effect/c5_monsters.xml<br>
Removed White Ogre and White Dragon's Fear fx.
___
data/gfx/fx/effect/cloth_effect_2016.xml<br>
Removed various wands and Pineapple Cup fx.
___
data/gfx/fx/effect/dramairia_gunner.xml<br>
Removed Gun fx.
___
data/gfx/fx/effect/dummy_effect.xml<br>
Removed "Blank Dummy" fx.
___
data/gfx/fx/effect/effect_wave.xml<br>
Removed wave fx.
___
data/gfx/fx/effect/effect_weather_rain.xml<br>
~~Decreased "rain on screen" fx.  Increased overall rain fx, making it more dense but each raindrop is smaller.~~  Increase the feeling of rain without affecting visibility or leaving long streaks in your vision.
___
data/gfx/fx/effect/fx_g5_fieldeffect.xml<br>
Removed sandstorm effects.
___
data/gfx/fx/effect/fx_magic_rolrole_ver10.xml<br>
Removed fireball explosion fx, fireball projectile still exists.  Removed mobs' self destruct fx.  Removed mobs' size change fx.  Removed IS fx.  Removed torch fire and smoke fx.  Removed taming particles.
___
data/gfx/fx/effect/glare.xml<br>
Glare removed.
___
data/gfx/fx/effect/icespear.xml<br>
Removed Ice Spear freezing and explosion fx, in an effort to remove the IS glitch icing the entire screen.
___
data/gfx/fx/effect/lightningbolt.xml<br>
Review me!
___
data/gfx/fx/effect/particles.xml<br>
~~Removed monster, NPC, and Nao spawning fx.~~<br>
Changed the little puff of smoke for enemy spawns.  Decent cloud that quickly rises.
___
data/gfx/fx/effect/particles2.xml<br>
Reworked Wisp fx.
___
data/gfx/fx/effect/particles5_ver8.xml<br>
Removed fireball explosion fx.  Removed quest waypoint fx.  
___
data/gfx/fx/effect/paticle01_c2_login.xml<br>
Removed login fx.
___
data/gfx/fx/effect/pet_bike.xml<br>
Removed fx from bike/scooter's headlight, glare, and various explosive fx.
___
data/gfx/fx/effect/pet_dragon_fire.xml<br>
Removed fx from fire dragon summon.
___
data/gfx/fx/effect/pet_dragon_thunder.xml<br>
Removed fx from thunder dragon summon.
___
data/gfx/fx/effect/ubicommon_nj.xml<br>
Removed fx from Sakura Abyss.
____
data/gfx/fx/effect/ubicommon_nj2.xml<br>
Removed fx from Kunai storm.
___
data/gfx/reflection/reflection.xml<br>
Removed all reflections.
___
data/gfx/gui/map_jpg<br>
minimap_emainmacha_eng.jpg includes location of Sky Palace.<br>
minimap_iria_connous_eng.jpg exploration map. UOTiara<br>
minimap_iria_connous_underworld.jpg is clearly marked. UOTiara<br>
minimap_iria_courcle_eng.jpg exploration map and shows some custom content spawns.  UOTiara<br>
minimap_iria_nw_tunnel_n_eng.jpg clearly marked.  UOTiara with hidden herbs by me.<br>
minimap_iria_nw_tunnel_s_eng.jpg clearly marked.  UOTiara with hidden herbs by me.<br>
minimap_iria_rano_eng.jpg exploration map. UOTiara.<br>
minimap_taillteann_abb_neagh_eng_rep.jpg Crag Cow spawn locations marked. UOTiara<br>
minimap_taillteann_jpn_rep.jpg Tail town SM potential spawns and a recommended route. Unknown Source?<br>
minimap_taillteann_sliab_cuilin_jpn_rep.jpg Sliab Cuilin SM potential spawns. UOTiara<br>
minimap_tara_jpn_rep.jpg Tara town SM potential spawns.  Includes generation spawns. UOTiara<br>
minimap_tara_n_field_jpn_rep.jpg Corrib Valley SM potential spawns. UOTiara<br>
minimap_viridius_cave.jpg Points of interest in Viridian Caverns, for raid.  Credit to kaydee for an original guide and some markings on pro forums.<br>
___
data/gfx/gui<br>
font_eng.dds and font_outline_eng.dds cleaned up.<br>
interface.dds various elements for the interface are modded.  Side-effect, when demi'd enemy icons are now orange instead of red.  Has UOTiara's Party and shop banners.
___
data/gfx/image/npc<br>
Gives Female Blunt Ego the appearance of Female Bow Ego.  Lines are still Blunt's.
___
data/gfx/image/gui_icon_skill_000.dds<br>
Changed the skill bubble for the revival feather into a crystal from FFT.
___
data/gfx/image/item_phoenix_feather.dds<br>
Changed the inventory icon for revival feather, into a crystal from FFT.
___
data/gfx/image/npcdialogue2.dds<br>
Changed the dialogue box for NPCs, to give it transparency.
___
data/gfx/image/uu_weapon_dagger001.dds<br>
Changed the inventory image for dagger, to make it easy to differentiate from a gathering knife.
___
data/gfx/scene/productionprop<br>
Makes mushrooms giant.
___
data/gfx/scene<br>
Large number of files in this directory of similar intent.  Suffice to say it servers to minimize things.  Mostly dungeon wall removal, dungeon fx/fog removal, removing small plants that are only eye candy, and cutting tops off trees.  Also includes tail and tara minimizations; primarily roped buildings.<br>
___
