Project Astri - Lost Soul Arts Mod

Foreword:

Hi All, I'm Astri. I've been playing the Soulsborne games since Demon's Souls starting ~2010, so you may have seen or heard of me at some point. Demon's Souls was my first online game and stands as one of my favorite games of all time. I've easily poured thousands of hours into it, creating new builds, partaking in jolly co-operation, dueling, and invading. I was one of only a handful of pure mages frequenting the NA PvP scene and am primarily known for my skill with spellcasting tech. I'm also a moderator of the Demon's Souls discord, although I have not been very active there in a long time.

After the release of the Demon's Souls remake in 2020 and feeling disappointment in the shape it was left in (password summons not downscaled, negative luck, guaranteed wakeups after backstab, etc.), I decided to start the ambitious project of modding the original game in May 2021. My vision was a massive overhaul to improve game balance and promote build diversity while still preserving the heart and soul of the original version (making changes that are neither detrimental to the PvE nor PvP experience). I frankly had no modding experience prior to this, nor do I have any practical background in coding, but with a lot of determination, after three full restarts of the project due to file corruption, and with occasional guidance from incredibly nice people in the Souls modding community like ariane_des and georgekingbore, I was able to bring this idea to fruition.

This is not a very flashy mod, nor was it meant to be. The changes were designed to blend in with the rest of the game as much as possible, **as if they were always meant to be there**. All of the major file edits were made by my own hands using DS Anim Studio, DS Map Studio, Wulf's BND Rebuilder, and True Ancestor 1.65, using assets that already exist in the game to create the new spells and moveset modifications. I modified existing icons for some of the new spells and made some new ones with a DDS unpacker, Clip Studio Paint, and Gimp. It is truly a labor of love that I hope you all enjoy.

----------------------------------

What's in Lost Soul Arts:

-Improved starting classes

-New spells and miracles designed with utility in mind and to fill previously unoccupied niches

-Most weapons rebalanced/revamped

-Modified function/scaling of some upgrade paths

-Some weapon movesets slightly modified....

-Armor weights and defenses now more fashion-friendly

-Revamped healing mechanics for grass and spice to improve game balance and provide a more challenging experience

-Revamped status effect potency and adjusted durations

-Respec at will with a new consumable item

-Modified some dev messages in the Nexus and Stonefang....

-Slightly changed some enemy placement....

-Changed some treasure locations and NPC loot

-Changed the behavior and equipment of some NPC's

-Added new NPC black phantoms

-Changed the movement properties of the poison swamp in the Valley of Defilement

-Added friendly scale miners, who are hiding throughout Boletaria....

I'll spare you all the essay and simply say that there is so much under the hood of this mod. Explore new progression paths. Use the respec item to experiment with character stats and make the most out of the new tools at your disposal. Most importantly, journey through Boletaria with fresh eyes. Leave no stone unturned.

***Tip: Read item and weapon descriptions. A lot has changed. Some changes may not be immediately obvious.***

----------------------------------

**Known Issues:**

-Some spells and miracles do not show up in shops at the right time (after defeating the boss whose soul you use to purchase them).

-Status does not display properly on weapons.


***I'm working on all of these, but may not be able to fix them if they're hardcoded.***

----------------------------------

*Monetization/Reuse/Collaboration Terms:*

*The contents of this mod are not to be modified, reused, redistributed, recreated, or monetized except by the original creator and authorized collaborators with express permission to do so. This was a solo project carefully tailored to fit a very specific vision and provide a refreshing new take on an old game.*

*Please do not request or offer to collaborate on this project unless you are able to address any of the known issues above.*

*If you have an idea for the project or wish to report a bug or other problem, please submit it on the GitHub Issues page.*

----------------------------------

**BEFORE YOU INSTALL:**

***FIRST WARNING: PLEASE BE AWARE THAT THE CONTENTS OF THIS MOD ARE NOT YET APPROVED FOR USE ONLINE. THIS WOULD ONLY BE ACCEPTABLE ON A SERVER DEDICATED TO THE MOD, WHICH I DO NOT HAVE THE BANDWIDTH TO CREATE OR MANAGE.***

***SECOND WARNING: IT IS RECOMMENDED THAT YOU START WITH FRESH SAVES. THERE IS A CHANCE THAT TRYING TO USE PRE-MODDED SAVES WILL CAUSE THEM TO BREAK. EX. MY CHARACTER FROM AN OLD SAVE HAD PERMANENTLY-EMPTY SPELL SLOTS.***

----------------------------------

Installing the mod:

The mod files are divided into the root path they should go in. Drag and drop the files within your game folders matching their respective root paths to replace the vanilla files. On PC, it will prompt you asking if you want to replace the files for every file. DO NOT DRAG AND DROP WHOLE FOLDERS. I have NOT included the vanilla files. I've listed all of the mod files and their root paths below. Use this as a checklist to ensure you correctly install the mod.


Replace the menu files listed below in Demons Souls BLUS30443>PS3_GAME>USRDIR>menu

menu.tpf  []

menu.tpf.dcx  []


Replace the script files listed below in Demons Souls BLUS30443>PS3_GAME>USRDIR>script:

m02.luabnd  []

m02.luabnd.dcx  []

m02.luabnd.dcx.sdat  []

m03.luabnd  []

m03.luabnd.dcx  []

m03.luabnd.dcx.sdat  []

m04.luabnd  []

m04.luabnd.dcx  []

m04.luabnd.dcx.sdat  []

m06.luabnd  []

m06.luabnd.dcx  []

m06.luabnd.dcx.sdat  []


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
