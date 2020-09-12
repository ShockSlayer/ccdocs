V1.1:
=====

Feature updates:
----------------
Added a "Legality Fixer" NPC for Transporter
 - Currently only works for Mew
	* This will change the OT and ID to the event Mew
 - Located in Move Deleter's house

Roaming trainer updates:
------------------------
Added Chaos to Goldenrod Radio Tower
 - Spends the weekends on New Cinnabar Island

Added Doom to National Park
 - Is lots of fun to talk to so just do it okay ( ͡° ͜ʖ ͡°)

Many improvements to existing roaming trainer scripts:
 - Now can be battled only once per day
 - Will greet you properly based on time of day
 - Remember your name, and some offer a one-time prize for battling
 - Will explain some lore to you, but only once
 - Will heal you after battle

Trainer data has also been changed to fix continuity errors after the E4
is unlocked.
 - This does not apply to SS yet.

Each set of the E4 teams have been buffed by about 10 levels
 - The first set is now more akin to the original second set.

Music updates:
--------------
 - Added Hoenn Wild Battle and Hoenn Trainer Battle themes
	* These replace the C/XD theme and the old RSE wild battle track
 - The Bazaar has its own music theme (Gen 4 mart theme)
 - Fixed tempo of Go Gym Battle theme
 - Fixed Oak's Talk music changing to the wrong song
 - Fixed incorrect music in Viridian Forest and surrounding gates

Misc updates:
-------------
 - Added FroggestSpirit's Voltorb flip to both Game Corners
	* FroggestSpirit himself is in Goldenrod and will explain the controls.
 - Added scaling data to Trainer house battle
 - New overworld sprite and trainer palette for honeybun
Lots of internal reworking for ease of expansion:
 - Organized and notated assets so the 3DS wifi patch wouldn't break
with every update
 - Overworld sprite handing is now more organized

Bugfixes:
---------
 - Fixed missing maptrigger in Goldenrod Gym
 - Fixed Blaine's script and Gym Rechallenge not clearing/resetting trainers
 - Fixed Dex not updating properly
 - Fixed Game Corner prizes not showing Dex screen
 - Fixed incorrect Rock Tunnel warps
 - Fixed incorrect Goldenrod Underground/Dept.Store warps
 - Fixed Chaos battle not using player loss text
 - Fixed Route 19/20 map connection issue
 - Fixed many Kanto overworld sprite glitches
 - Fixed Ruins of Alph wall text crashing the game
 - Fixed ITEMNAME used ITEMNAME happening in special trainer battles
 - Fixed missing setevents for a handful of trainer scripts and events.
 - Fixed being able to run from stationary Power Plant Voltorbs/Electrodes
 - Fixed Bazaar Master Ball price being too high compared to Game Corner prize
 - Fixed missing transaction sound and money display in Pewter Museum ticket seller script
 - Fixed amount of steps to next fossil not being properly handled
 - Fixed missing link mode checks in battle engine
 - Fixed missing link battle result display
 - Fixed Roamer code overflowing and screwing up link battle stats
 - Fixed forfeiting in link battles causing a desync
 - Fixed Destiny Bond breaking battles and causing a crash
 - Fixed roaming Mew jumping to Johto Route 34, and improved jumping in general.
 - Fixed Event Tutor teaching eggs moves.
 - Fixed Blaine's Gym trainers later sets being too weak in levels
 - Fixed phone calls from registered trainers talking about the wrong species
	* This has been updated to use species from the current set.

Ported over a handful of vanilla bugfixes:
(Most of these will be unnoticeable and documented better elsewhere)
 - Exp string bug
 - Park Ball bug
 - Port tileset fix
 - Massage happiness fix
 - Magikarp length fixes
 - Wild validation
 - Slot machine bugfix
 - US/JP player name length bugfix
 - Tile facing bugfix
 - Stone compatibility bugfix
 - Overworld sprite bugfix
 - NPC movement bugfix
 - Battle AI Mean Look/Toxic bugfix
 - Battle AI Nightmare heal bugfix
 - Experience underflow bugfix

Map fixes:
----------
 - Fixed incorrect Power Plant/Cinnabar Mansion collision
 - Fixed incorrect collision for fence next to Route 19 Gate
 - Fixed incorrect tile on under construction Route 4 center
 - Fixed incorrect tiles on Route 10 South and Route 12
 - Fixed Route 42 border tiles being visible
 - Fixed Route 8/Saffron connection tiles
 - Fixed Radio tower gate not being open by default
 - Fixed Elite Four hallway showing other map corner
 - Fixed HM Cut being required to get HM Cut in Kanto
	* This also opens up the Digglet's Cave shortcut earlier
 - Updated Cianwood/Route 41 tiles
 - Fixed two National Park NPCs not using Gameboy kid sprites
 - Fixed IVAN wandering around too much
 - Fixed New Cinnabar Gym Guy looking up instead of down
 - Fixed a red Zubat in Cerulean City
 - Changed Time Capsule "other player" sprite to RED

Moved many NPCs around:
 - Lavender Town
 - Pallet Town
 - Route 25
 - Route 38
 - Route 44
 - Whirl Islands

Text fixes:
------
 - Fixed missing sign text in Bazaar/Lavender/Celadon/Saffron/Viridian/Route 4/Route 10 North
 - Fixed outdated Slowpoke reference in Azalea Gym
 - Fixed Lavender town gramps text error
 - Fixed Cinnabar Mansion text overflowing
 - Fixed Kanto FLASH text going outside of the box
 - Fixed Cerulean Gym guy text going outside of the box
 - Fixed "beliving" in PIGY
 - Fixed Safari Zone incorrectly named area
 - Fixed Kurt's son text improper punctuation
 - Fixed Viridian Forest duplicate signs
 - Fixed "People and Places" referencing trainers that it shouldn't
 - Fixed Saffron Gym Guy assuming it's not your first Gym
 - Removed Gym badge obedience level and stat boost references
 - Removed reference in Azalea to skinny trees
 - Removed reference in Route 35 Goldenrod Gate to weird tree
 - Removed reference to fainting from poison
 - Updated Route 13 reference to Pikachu text
 - Updated Lake of Rage NPC text slightly
 - Updated Trainer House/Saffron Center/Vermilion port "JOHTO" text
 - Updated Goldenrod Dept.Store "can't rename nicknamed mon" text
 - Updated Goldenrod Evolution Solutions NPC text
 - Updated reference to Cerulean Cave
 - Added a special badge check for Morty's text
 - Added text to the sign in the Celadon Game Corner Prize Room
 - Lots of other minor text fixes
