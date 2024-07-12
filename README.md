Foreword:

Hi All, I'm Astri. I've been playing the Soulsborne games since Demon's Souls starting ~2010, so you may have seen or heard of me at some point. Demon's Souls was my first online game and stands as one of my favorite games of all time. I've easily poured thousands of hours into it, creating new builds, partaking in jolly co-operation, dueling, and invading. I was one of only a handful of pure mages frequenting the NA PvP scene and am primarily known for my skill with spellcasting tech. I'm also a moderator of the Demon's Souls discord, although I have not been very active there in a long time.

After the release of the Demon's Souls remake in 2020 and feeling disappointment in the shape it was left in (password summons not downscaled, negative luck, guaranteed wakeups after backstab, etc.), I decided to start the ambitious project of modding the original game. My vision was a massive overhaul to improve game balance and promote build diversity while still preserving the heart and soul of the original version (making changes that are neither detrimental to the PvE nor PvP experience). I frankly had no modding experience prior to this, nor do I have any practical background in coding, but with a lot of determination, three full restarts of the project due to file corruption, and occasional guidance from incredibly nice people in the Souls modding community like Thens and kingbore, I was able to bring this idea to fruition. All of the edits in the mod were made by my own hands, so it is truly a labor of love that I hope you all enjoy.

----------------------------------

What's in the mod:

-Improved starting classes

-Slightly changed some spells and miracles....

-Some spells and miracles replaced with new ones....

-Most weapons rebalanced/revamped

-Modified function/scaling of some upgrade paths

-Some weapon movesets slightly modified....

-Reduced backstab multipliers for all weapons except fist weapons

-Armor weights and defenses now more fashion-friendly

-Grass, spice, and status effects now percentage-based (note: status no longer displays properly because it is only calculated from flat effects)

-Grass effects changed from instantaneous healing to regen

-Status effect duration adjusted

-Misc QoL changes

-Modified some dev messages in the Nexus and Stonefang....

-Changed some enemy placement....

-Friendly scale miners are hiding throughout Boletaria....

----------------------------------

WARNING: BEFORE YOU INSTALL, PLEASE BE AWARE THAT THE CONTENTS OF THIS MOD ARE NOT APPROVED FOR USE ONLINE. THIS WOULD ONLY BE ACCEPTABLE ON A SERVER DEDICATED TO THE MOD, WHICH I DO NOT HAVE THE BANDWIDTH TO CREATE OR MANAGE.

----------------------------------

Installing the mod:

The mod files are divided into the root path they should go in. Drag and drop the files within your game folders matching their respective root paths to replace the vanilla files. On PC, it will prompt you asking if you want to replace the files for every file. DO NOT DRAG AND DROP WHOLE FOLDERS. I have NOT included the vanilla files. I've listed all of the mod files and their root paths below. Use this as a checklist to ensure you correctly install the mod.

Replace the script files listed below in Demons Souls BLUS30443>PS3_GAME>USRDIR>script:

m02.luabnd  []

m02.luabnd.dcx  []


Replace the sfx files listed below in Demons Souls BLUS30443>PS3_GAME>USRDIR>sfx:

ds_sfxbnd_commoneffects.ffxbnd  []

ds_sfxbnd_commoneffects.ffxbnd.dcx  []


Replace the anibnd files listed below in Demons Souls BLUS30443>PS3_GAME>USRDIR>chr>c0000

c0000.anibnd  []

c0000.anibnd.dcx  []

c0000_a2x.anibnd  []

c0000_a2x.anibnd.dcx  []

c0000_a3x.anibnd  []

c0000_a3x.anibnd.dcx  []

c0000_a4x.anibnd  []

c0000_a4x.anibnd.dcx  []


Replace the gameparam files listed below in Demons Souls BLUS30443>PS3_GAME>USRDIR>param>gameparam

gameparam.parambnd  []

gameparam.parambnd.dcx  []

gameparamna.parambnd  []

gameparamna.parambnd.dcx  []


Replace the text files listed below in Demons Souls BLUS30443>PS3_GAME>USRDIR>msg>na_english

menu.msgbnd  []

menu.msgbnd.dcx  []

item.msgbnd  []

item.msgbnd.dcx  []


Replace the map files listed below in Demons Souls BLUS30443>PS3_GAME>USRDIR>map>mapstudio

m01_00_00_00.msb  []

m02_00_00_00.msb  []

m02_01_00_00.msb  []

m02_02_00_00.msb  []

m02_03_00_00.msb  []

m03_01_00_00.msb  []

m03_02_00_00.msb  []

m03_03_00_00.msb  []

m04_00_00_00.msb  []

m04_01_00_00.msb  []

m04_02_00_00.msb  []

m05_00_00_00.msb  []

m05_01_00_00.msb  []

m05_02_00_00.msb  []

m06_00_00_00.msb  []

m06_01_00_00.msb  []

m06_02_00_00.msb  []


------------------------

ProjectAstri_v1.00

Weapons

-reduced upgraded Dragon Bone Smasher base AR to 200

-increased Dragon Bone Smasher strength scaling with upgrade

-reduced Bramd weight to 24

-reduced Bramd base AR to 200

-increased Bramd strength scaling with upgrade

-reduced weight for all Guillotine Axe variants to 3.5

-reduced repair cost to cap at 3 souls per durability point

-reduced strength and dex scaling for Epee Rapier to 0

-reduced Epee Rapier dex req to 12

-increased Epee Rapier base Fire AR to 110

-reduced Istarelle dex req to 14

-reduced Istarelle strength and dex scaling to 0

-increased Istarelle base Magic AR to 120

-increased Large Sword of Moonlight base Magic AR to 110

-reduced Scraping Spear corrosion effect to 5 durability per hit

-increased base AR of all Short Bow variants and upgrades

-reduced base AR of all Long Bow variants and upgrades

-increased range of Short Bow for normal and quality upgrades

-reduced range of Compound Short Bow for sticky upgrade

-reduced range of all Compound Long Bow variants

-increased strength scaling of all Quality upgraded bows

-reduced White Bow base physical AR to 20

-increased White Bow base magic AR to 60

-reduced White Bow strength and dexterity scaling to 0

-increased White Bow faith requirement to 24

-increased White Bow faith scaling to 70 + (20*upgrade level)

-reduced White Bow strength requirement to 18

-reduced White Bow dex requirement to 14

-reduced White Bow range to 30

-reduced Lava Bow base physical AR to 20

-reduced Lava Bow base fire AR to 80

-reduced Lava Bow strength and dexterity scaling to 0

-increased Lava Bow magic scaling to 160

-reduced Lava Bow strength requirement to 16

-reduced Lava Bow dex requirement to 14

-reduced all Dragon weapon physical base AR by ~59%, fire base AR by ~18%, and enabled Luck scaling

-increased Great Club strength scaling

-added 0.8%hp self-damage effect to Needle of Eternal Agony

-increased Needle of Eternal Agony base physical AR to 66, increased dex scaling to 66, reduced magic AR to 0, and reduced magic stat requirement to 0

-reduced all Secret Dagger variant base physical and magic AR to match corresponding pre-mod basic Dagger variants

-increased all basic Dagger variant base physical and magic AR to match corresponding pre-mod Secret Dagger variants

-added bleed effect to all Secret Dagger variants

-added Tearing Secret Dagger variants to weapon roster

-added Great Club upgrades to weapon roster

-decreased Dozer Axe physical AR to 140

-increased Dozer Axe fire AR to 70

-added 180 strength scaling to Dozer Axe

-added 120 faith scaling to Dozer Axe

-increased Dozer Axe faith requirement to 24

-decreased Northern Regalia base physAR and base magAR to 65, added 3 strength/dex/magic/faith scaling, and enabled Luck scaling

-decreased Soulbrandt base physAR and base magic AR to 60, added 3 strength/dex/magic scaling, and enabled Luck scaling

-decreased Demonbrandt base physAR and base magic AR to 60, added 3 strength/dex/faith scaling, enabled Luck scaling, and reduced anti-demon damage to 1.0

-increased guardpoke stamina cost of rapiers to 25

-increased guardpoke stamina cost of spears to 30

-increased Broken Sword durability to 200

-reduced all Fatal weapon throwrates to 0

-added weak lifesteal effects to fatal weapons

-increased all Fatal weapon Dexterity scaling; 60 at +1, 80 at +2, 100 at +3, 115 at +4, and 133 at +5

-reduced all upgraded Rune Sword variants base magic AR to 140 and increased magic and faith scaling equally to 10+10*upgradelevel

-increased Blind base physical AR to 90

-reduced Makoto base physical AR to 0 for all variants, increased base magic AR to 115, added 18 magic stat requirement, and increased magic scaling to 100+20*upgradelevel

-reduced Pickaxe dexterity requirement to 6

-reversed strength and dex scaling for all Pickaxe variants

-added Simpleton's Catalyst, a wooden catalyst that has the Magical Nature special effect and 40 magic scaling

-reversed strength and dexterity scaling for all Mercury weapons except Pickaxe and War Pick

-changed Mercury War Pick scaling to a near-even split between strength and dexterity

-increased Mercury Pickaxe strength scaling and reduced dexterity scaling

-reduced Mailbreaker base AR for all variants

-increased Mailbreaker crit throw rate from 0 to 10 for all variants

-reversed dex scaling and strength scaling for all Mailbreaker variants except Mercury

-increased scaling for all Shortsword variants except Dragon

-increased fire base AR for all Dragon Shortsword variants

-increased scaling for all Longsword variants except Dragon

-increased fire base AR for all Dragon Longsword variants

-increased scaling for all Bastard Sword variants except Dragon

-increased fire base AR for all Dragon Bastard Sword variants

-increased scaling for all Rapier variants

-increased scaling for all Spiral Rapier variants

-increased scaling for all Scimitar variants

-increased scaling for all Falchion variants

-increased scaling for all Shotel variants

-increased scaling for all Battle Axe variants

-reduced scaling for all War Scythe variants

-reduced scaling for all Mirdan Hammer variants except Dragon

-reduced fire base AR for all Dragon Mirdan Hammer variants

-increased strength scaling of all Iron Knuckle variants except Dragon

-increased physical and magic base AR for all Moon Iron Knuckle variants

-increased strength and faith scaling for all Hands of God variants

-increased dex scaling of all Penetrating Sword variants

-increased scaling for all Parrying Dagger variants

-reduced scaling for all Crescent Mail Breaker variants

----------------------------------

Attack modifiers

-reduced all backstab modifiers by 10%, excluding fist weapons

-increased stamina damage of left hand large shield bash to 300

----------------------------------

Shields

-reduced Dark Silver Shield fire resistance to 30%

-removed Dark Silver Shield magical dullness effect

-reduced Dark Silver Shield stability

-reduced magic resistance to 10% for all non-dark 100% physical block shields except Tower shield, Dark Silver Shield, and Rune Shield

-reduced fire resistance to 50% for all Spiked Shield variants

-reduced repair cost to cap at 3 souls per durability point

-reduced fire resistance of all Dark-upgrade shields by 30%

-reduced Buckler stability increases on upgrade

-increased Wooden Shield magic resistance to 90%

-reduced Heater Shield, Kite Shield, and Knight Shield stability on normal and dark upgrades

-reduced Soldier's Shield stability increases on upgrade

-increased Slave's Shield magic resistance to 60%

-reduced Steel Shield and Purple Flame Shield stability on normal and dark upgrades

-increased Dark Soldier's Shield and Dark Buckler magic resistance by 2 points, plus an additional 2 points per upgrade

-increased Leather Shield magic resistance from 30% to 40%

-reduced Brushwood Shield stability

-increased Rune Shield magic AR to 40

-increased Rune Shield magic and faith scaling

-increased strength scaling of all Tower Shield variants

-increased strength scaling of all Steel Shield variants

-increased base physical AR of all Brushwood Shield variants

-increased strength scaling of all Brushwood Shield variants

-increased strength scaling of all Purple Flame Shield variants

----------------------------------

Armor

-adjusted armor weights

-adjusted armor defs

-adjusted armor resistances

-adjusted armor stamina penalties

-adjusted armor repair costs to 3 per durability point

-reduced armor blunt, slash, and thrust modifiers by 40%

-changed Saint armor set defs to match corresponding Venerable set pieces

-changed Saint armor set durability to match corresponding Venerable set pieces

----------------------------------

Rings

-reduced all ring weights to 0

----------------------------------

Hypermode

-reduced Clever Rat Ring effect to 30%

-reduced Morion Blade effect to 30%

----------------------------------

Spells

-reduced Cursed Weapon buff to 30%

-changed Cursed Weapon HP degen to 4HP/s

-increased Water Veil fire damage reduction to 80%

-changed Anti-Magic Field to Warding-like body buff with 85% magic damage reduction, MP cost of 40, and changed slot size to 1

-changed Antidote miracle to Flame Weapon buff, which scales with faith, is cast with talismans, has 130 base damage, costs 50000 souls from Follower of God NPC shop OR 30000 souls from Saint Urbain NPC shop, deals self-damage at a rate of 0.2%MaxHP per 0.5sec, and costs 60MP to cast

-changed Resurrection miracle to Cloud of Flies miracle; creates fly explosion with 220 physical AR, inflicts flies status effect on hit that deals 0.7%hp/sec for 20sec, costs 50 mp, and costs the Dirty Colossus Soul to obtain

-changed Homing Soul Arrow bullet effect to Maneater Homing Soul Arrow, removed floating stage for faster cast, reduced MP cost to 30, reduced magicAR to 75, and reduced number of bullets to spray of 3 with improved homing ability; now costs Maneater Soul to obtain

-changed Banish miracle to Penitent Nails miracle; knocks enemies in the vicinity down to the ground, ignoring guard and inflicting strong bleed; has 170 base physical AR and costs 21 MP; the caster pays the cost of 20% of their HP, but regains 10% per living target hit

-changed Recover soul cost to Maiden Astraea's Soul

-changed Firespray from continuous cast to single cast spell; now shoots 5 orbs of fire in a fan in front of the caster, increased mp cost to 18, and added light stagger

-changed Poison Cloud to Torpefy, an ignite-like spell with 100 physical AR that causes buildup of strong bleed

-changed Firestorm effect to lava eruptions around the caster, changed knockdown to medium stagger, and reduced fire AR to 150

-changed Protection to Rock Throw, a spell that conjures and hurls a boulder in an arc in front of the caster; has 238 physical AR on direct hit and 88 physical AR on splash damage, costs 20mp, and is obtained by trading in the Soul of a Miner with either Freke or Freke's Apprentice

-changed Acid Cloud to Sludge Toss, a spell that lobs sludge in an arc in front of the caster; has 66 physical AR, costs 24mp, degrades equipment by 30 durability, and deals 90 buildup of poison that deals 0.6%hp/sec

-reduced slot length of Second Chance to 1

-changed Death Cloud to Wind Slice, a spell that creates a lacerating blade of wind that pierces enemies; has 150 magic AR, costs 18mp, and costs Allant's soul to obtain

-reduced slot length of Soul Thirst to 2, reduced MP cost to 100, and added 15% attack buff and 30% defense debuff

----------------------------------

Status

-changed status special effects to HP%

-some status special effects buffered with minor flat HP effect

-reduced poison duration to 90s

-reduced plague stamina penalty to -5

-reduced plague duration to 180s

-similarly adjusted corresponding environmental status

-similarly adjusted corresponding status inflicted by mobs

-increased bleed tier for all Broadsword variants by 1

-increased bleed tier for all Morning Star variants by 1

-increased bleed tier for all Flamberge variants by 2

-decreased bleed tier for all Spiral Rapier variants by 1

-decreased bleed tier for all Uchigatana variants by 1

-decreased bleed tier for all Hiltless variants by 1

-decreased bleed tier for all War Scythe variants by 1

-decreased bleed tier for all Fatal weapons with bleed effect by 1

-decreased bleed tier for all Mercury weapons with bleed effect by 1

-decreased bleed tier for all Tearing Uchigatana variants by 1

-decreased bleed tier for all Tearing War Scythe variants by 1

-decreased bleed tier for all Tearing Kilij variants by 1

-increased bleed tier for all Tearing Scimitar variants by 1

-increased bleed tier for all Tearing War Pick variants by 2

-increased bleed tier for all Tearing Pickaxe variants by 2

-added new bleed effect for Great Club (Bleed_10 with 40 buildup)

-added bleed effect to Needle of Eternal Agony with 0.2% dps

-added new poison effect to Needle of Eternal Agony with 90s duration, 70% healing cut, (0.3% - 1) dps, and 3 stamina regen penalty

----------------------------------

Regen

-reduced blessed weapon regen

-reduced Adjudicator Shield regen

-reduced Regenerator Ring regen

-reduced motion intervals for crescent weapon MP regen

-reduced motion intervals for Phosphorescent Pole MP regen

-increased Meat Cleaver HP drain effect to 2.5%

-created new HP drain speffects for fatal weapons; weak effect to daggers and rapiers, stronger effect to spears

----------------------------------

Healing consumables

-changed Crescent Moon Grass duration to 4 seconds, motion interval to 0.2, healing to 1%HP+7HP, and healing rate to 80%

-changed Half Moon Grass duration to 8 seconds, motion interval to 0.3, healing to 2%HP+6HP, and healing rate to 60%

-changed Late Moon Grass duration to 16 seconds, motion interval to 0.4, healing to 3%HP, and healing rate to 40%

-changed Full Moon Grass duration to 30 seconds, motion interval to 0.5, healing to 5%HP, and healing rate to 20%

-changed New Moon Grass duration to 80 seconds, motion interval to 0.8, healing to 10%HP, and healing rate to 10%

-changed Spice MP recovery from flat to MP%

-reduced Dark Moon Grass healing effect to 10% HP, maintaining instantaneous effect

-added regeneration aura and status icon for active grass effects

----------------------------------

Non-healing consumables

-reduced weight of all throwables to 0.1

-reduced Holy Arrow magic AR to 80

-reduced White Arrow physical AR to 0 and increased magic AR to 100

-increased Heavy Arrow physical AR to 115

-added Soul of a Miner to 2-1 treasure corpse

----------------------------------

Ore

-reduced all ore weights to 0

-increased drop rates and quantities for ores from crystal lizards

-increased drop rates for ores from various mobs

----------------------------------

Miscellaneous consumables

-reduced brass telescope weight to 0

-reduced consumable weapon buff weights to 0.1

-added Voidstone, an item that reduces the player character's soul level by one

----------------------------------

NPC's/Enemies

-added ring of magical dullness to Garl's equipment

-added ring of flame resistance to Garl's equipment

-added ring of great strength to Garl's equipment

-added ring of the eternal warrior to Garl's equipment

-removed Garl's immunity to poison and bleed

-changed White Bow NPC black phantom secondary weapon to Large Sword of Moonlight, swapped wooden catalyst out for talisman of god, swapped Firestorm for Penitent Nails Miracle, changed armor to Mirdan set, equipped Ring of Great Strength, and increased faith stat to 24

-changed Scraping Spear NPC black phantom weapon to Fatal Winged Spear

-changed Penetrator NPC black phantom weapon to Crescent Flamberge+5, changed AI to match Scirvir black phantom, equipped Talisman of Beasts, equipped Homing Soul Arrow, Firestorm, Torpefy, Recovery, and Regenerate, changed armor to Monk's Head Wrap with Saint's Robes, increased magic to 30, increased faith to 24, increased vit to 30, and increased intelligence to 99

-changed Female Barbarian NPC black phantom equipment to Dozer Axe, full Chain armor set, removed Steel Shield, equipped Ring of Great Strength, increased strength to 30, and increased faith to 24

-replaced Stone of Ephemeral Eyes Follower of God NPC gift with Talisman of God

-removed Allant's plague immunity

-increased Penetrator's magic defense to 132 and decreased fire defense to 97

----------------------------------

Shops

-added Monk's Head Wrap in Former Royal's Wife NPC shop and set cost to 100000 souls

-removed purchase limit and event flag for White Arrows in Patches the Hyena NPC shop

-removed purchase limit for Dark Moon Grass in Patches the Hyena NPC shop

-changed Fresh Spice to Old Spice in Patches the Hyena NPC shop

-changed Half Moon Grass to Augite of Guidance from Patches the Hyena NPC shop

-added Chunk of Dragonstone in Filthy Man NPC shop and set cost to 10000 souls

-added Chunk of Moonlightstone in Once-Royal Mistress NPC shop and set cost to 10000 souls

-added Chunk of Greystone in Filthy Man NPC shop and set cost to 10000 souls

-added Chunk of Clearstone in Filthy Man NPC shop and set cost to 10000 souls

-added Chunk of Spiderstone in Filthy Man NPC shop and set cost to 10000 souls

-added Chunk of Faintstone in Filthy Woman NPC shop and set cost to 20000 souls

-added Chunk of Darkmoonstone in Bilge NPC shop and set cost to 15000 souls

-added Chunk of Cloudstone in Bilge NPC shop and set cost to 10000 souls

-added Shard of Bladestone in Bilge NPC shop and set cost to 2000 souls

-added Chunk of Bladestone in Bilge NPC shop and set cost to 10000 souls

-added Shard of Mercurystone in Once-Royal Mistress NPC shop and set cost to 3000 souls

-added Chunk of Mercurystone in Once-Royal Mistress NPC shop and set cost to 15000 souls

-added Shard of Suckerstone in Filthy Woman NPC shop and set cost to 2000 souls

-added Chunk of Suckerstone in Filthy Woman NPC shop and set cost to 10000 souls

-added Shard of Marrowstone in Filthy Woman NPC shop and set cost to 2000 souls

-added Chunk of Marrowstone in Filthy Woman NPC shop and set cost to 10000 souls

-added Shard of Meltstone in Filthy Man NPC shop and set cost to 3000 souls

-added Voidstone in Blacksmith Boldwin NPC shop and set cost to 150 souls

----------------------------------

Cheat Gear

-all game-breaking cut-content weapons nerfed

-changed Garl's armor to match regular Dark Silver armor set

-changed Garl's shield to match Dark Silver Shield

----------------------------------

Movesets

-changed greatsword push attacks to kick; still needs testing

-changed greataxe/greathammer push attacks to kick; still needs testing

-changed polearm 1h push attack to kick; still needs testing

-changed polearm 1h first r1 attack to spear thrust; still needs testing

-changed spear 1h push attack to kick (game references polearm animation for push attack); still needs testing

-changed fist weapon headbutt to kick; still needs testing

-changed Mail Breaker type and moveset to dagger

-changed Needle of Eternal Agony moveset and properties to act like a dagger

-changed fist weapon R2 attack animation to right hook

-changed greatsword 1h R2, first 2h R1, 2h running R1, and 1h rolling R1 knockdown to heavy stagger

-changed greatsword second 2h R2 from heavy stagger to knockdown

-increased stamina damage of greatsword second 2h R1 and third 2h R1

-increased attack multipliers of greatsword third 2h R1 and second 2h R2

-changed fist weapon R2 stagger from moderate to heavy

----------------------------------

Text

-changed name of "storied" souls to "fabled" souls

-changed description of White Bow to describe new scaling

-changed description of White Arrows to describe new scaling

-changed description of Dragonstone to hint at new scaling

-changed description of Cloudstone to note reduction in fire block stat

-changed description of Great Club to describe new bleed effect and how to upgrade it

-changed description of all Grasses to describe healing changes

-changed description of Spices to describe new effect

-changed name and description of Anti-Magic Field to Anti-Magic Barrier to describe new effects with lore context

-added description of Flame Weapon

-changed description of Dozer Axe to describe new effects with lore context

-changed description of Marrowstone to describe new lifesteal effect

-changed description of Northern Regalia to describe new scaling

-changed description of Soulbrandt to describe new scaling

-changed description of Demonbrandt to describe new scaling

-changed name and description of Resurrection to Cloud of Flies to describe new effects with lore context

-changed name and description of Banish to Penitent Nails to describe new effects with lore context

-changed description of Homing Soul Arrow to describe new effects with lore context

-changed description of Recover to fill lore context for new boss soul cost

-changed description of Firestorm to describe new effect with lore context

-changed description of Firespray to describe new effect with lore context

-changed name of Poison Cloud to Torpefy and describe new effect with lore context

-changed description of Needle of Eternal Agony to describe new effects with lore context

-changed description of Dark Silver Shield to imply reduced fire resistance

-changed description of Lava Bow to imply increased magic scaling

-added description of Voidstone to describe effect

-changed name and description of Acid Cloud to Sludge Toss to describe new effect with lore context

-changed name and description of Death Cloud to Wind Slice to describe new effect with lore context

-changed description of Soul Thirst to describe new effect

-added description of Simpleton's Catalyst

-changed description of Mercurystone to describe scaling changes

-changed description of Mailbreaker to describe scaling and weapon class changes

-corrected typo in vanilla description of basic Dagger

-changed description of Secret Dagger to describe new bleed effect

-changed description of Broadsword to describe bleed effect

-changed description of Shotel to describe bleed effect

-changed description of Hiltless to describe bleed effect

-changed description of Blind to describe bleed effect

-changed description of Large Sword of Searching to imply bleed effect

-changed description of War Scythe to describe bleed effect

----------------------------------

Starting Classes

-reduced Soldier class Magic and Luck stats

-increased Soldier class Vitality, Intelligence, and Dexterity

-reduced Magician class Endurance and Luck

-increased Magician class Vitality, Intelligence, Strength, Dexterity, and Magic

-reduced Barbarian class Magic, Faith, and Luck

-increased Barbarian class Vitality, Endurance, and Strength

-reduced Hunter class Magic and Luck

-increased Hunter class Endurance and Dexterity

-replaced Hunter class Battle Axe with Scimitar, moved bow to left hand subweapon, and added Secret Dagger to right hand subweapon

-increased Thief class Intelligence, Endurance, and Dexterity

-decreased Thief class Strength, Faith, and Luck

-replaced Thief class Buckler with Claws, added Silver Catalyst to left hand subweapon, and added Demon's Prank and Cloak to spell slots

-renamed Thief class to Assassin

-increased Wanderer class Intelligence, Magic, and Faith

-decreased Wanderer class Endurance, Strength, Dexterity, and Luck

-replaced Wanderer class Falchion with Broken Sword, removed Dagger right hand subweapon, added Wooden Catalyst to left hand subweapon, and added Enchant Weapon to spell slot

-renamed Wanderer class to Arcanist

-replaced Priest class Antidote/Flame Weapon miracle with Hidden Soul

-added 2 Fresh Spice to Arcanist starting inventory

-replaced Barbarian Wooden Shield with Slave's Shield

-moved Royalty silver catalyst to left hand

-moved Magician wooden catalyst to left hand

----------------------------------

Maps

-changed some enemy placement in 1-1

-changed some enemy placement in 1-2

-changed some enemy placement in 1-3

-changed some enemy placement in 2-1

-changed some enemy placement in 2-2

-changed some enemy placement in 3-2

-added 2 hidden scale miners in the Nexus

-added 1 hidden scale miner Below the Nexus

-added 3 hidden scale miners in 1-1

-added 2 hidden scale miners in 1-2

-added 2 hidden scale miners in 1-3

-added 2 hidden scale miners in 1-4

-added 1 hidden scale miner in 2-3

-added 6 hidden scale miners in 3-1

-added 8 hidden scale miners in 3-2

-added 2 hidden scale miners in 3-3 (only one visible)

-added 2 hidden scale miners in 4-1

-added 3 hidden scale miners in 4-2

-added 1 hidden scale miner in 4-3

-added 2 hidden scale miners in 5-1

-added 8 hidden scale miners in 5-2

-added 1 hidden scale miner in 5-3

-changed the text and/or locations of some developer messages in the Nexus and Stonefang

----------------------------------
----------------------------------

Ideas for later:

-change moveset for 2h L1/L2? Likely not possible without affecting shields as well

-add riposte vulnerability during guardbreak? May be hardcoded and very difficult/impossible to mod

-deactivate backstab grab for 3sec after backstab? Likely requires advanced coding

-menu option to send items back to Thomas when exceeding item max (deposit only)? Likely requires advanced coding

-increase ladder climbing speed? Likely requires advanced modding

-add 3-5sec i-frame window after player spawn? Likely requires advanced coding

-fix bad enemy AI? Likely requires advanced coding

-add ring to allow normal movement in swamp? Likely tied to NPC-exclusive effect

-blue sentinel type of security mod? Requires advanced programming

-eliminate spellswap? Likely not possible, since this is a problem with input queues in the game engine

-nerf rapier rollpokes?

-replace offhand weapon block with diff attack? Would likely affect shields as well

----------------------------------

To-do:

-reduce weapon base AR at lower levels?

-fix Shotel chip?

-further reduce rapier class crit multiplier?

-change catalyst strike attack

-fix polearm kick recovery cancel; fixed? needs testing

-add kick to 1h large sword moveset?

-increase miracle and spell slots?

-increased vulnerability window for guardbreaks? needs testing

-shortened recovery after UGS/GA/GH kick? needs testing

-increase large shield bash guardbreak; full moveset needs to be done

-eliminate pushlock; delay after L1 or delay after push?

-change fist r2 to more useful attack?

-new 2h katana r2 animation

-new spell ideas: bearbug explosion, leachmonger leach ball, tower knight javelin, lava throw, some kind of short-mid range spear thrust spell?

-false moonlight weapon?

-old point of abuse: greatweapon knockdown guarantees free miracle use, consider reducing duration of knockdown or exchanging it for a heavy blow on some attacks?

-change hitstun animation priority for fire weapons?

-remix enemy locations/types; add new NPC invaders as well?
