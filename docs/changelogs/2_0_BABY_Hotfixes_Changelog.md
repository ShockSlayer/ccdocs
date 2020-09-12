# Preface
These minor updates came out in the months after 2.0 BABY was released, but were not given a proper identifier. I consider this to have been a mistake, which caused a lot of confusion. Rather than retcon these to be something like "2.0.1", "2.0.2", etc; I've opted to instead sort them by the dates that they were added, and keep them to a single changelog.

August 3, 2019
--------------
Minor update to fix:
 - Fixed Forest of Rage map connection error with ledge tiles
 - Fixed flying to New Cinnabar causing a lot of region detection based bugs
 - Fixed Blaine's Gym Rechallenge not clearing trainers properly
 - Added Kabutops to Hydro Pump in the Battle Tutor to fix weird Gen 2 omission (could learn normally in Gen 1)
 - Oak's PC Stadium 2 Fix now requires a save file to run
 - Corrected "any more" to "anymore"
 - Fixed typo in Blackthorn Gym follower text
 - Fixed a typo in follower low HP text

 - Added "City Escape"
 - Added "Sonic X"
	* both are unlockable for music choices (wild, trainer, gym, center, bike, surf)
	* City Escape is now a radio choice
 
 - Cat's music is now City Escape, with the exception of Set 15 which is Sonic X.
	 * Set 16 also unlocks Sonic X, but does not play it in-battle.

 - Fixed a stray pixel on Doom's OW sprite.

July 14, 2019
-------------
Minor update to fix: 
 - Fix for forced radio breaking Eusine Cianwood cutscene
 - Fix for disable music not clearing forced radio settings
 - Added "BN6 Boss" and "Zero Stage 2"
 - Fixed wrong KRIS trainer constant in disallowed radio classes
 - "BN6 Boss" is now unlocked with the other two battle network battle themes
 - "Teehee Valley" is unlocked when Noak is fought
 - "Mad World" now loops.
 - Reorganized Sound of Pig tracks, and added "Zero Stage 2"
 - Decreased daycare troll text chance to 95%
 - Added additional handling to sign text in Grullo Gorge
 - Added missing events to Grullo Gorge House

July 11, 2019
-------------
Minor update to fix:
 - Fixed Training Hall using glitch data when a save isn't present (forces the player to save similar to the Lucky Number Show)
 - Fixed exiting Stats Screen instantly not restoring the volume to the proper level
 - Fixed Wise Trio not using correct palettes
 - Fixed Pryce's Set 14 Piloswine's level being off by one
 - Fixed Champion's Jolteon using incorrect hidden power
 - Updated Bird Keeper sprite
 - Perish Song now fails when used by wild mons
	 * in CC this affects scaling Celebi, Lapras, and any wild Politoed
 - Fixed missing Forest of Rage hidden ledge tiles

 - Enabled experimental perma-radio feature
	 * Press Select on any radio station to lock the current music.
	 * Persists through map changes, battles, certain events, etc.
	 * Several cutscenes _do_ disable this, but only temporarily.
	 * All settings are saved.
	 * Updated Radio GFX to support these changes
	 * (Experimental means this is likely to cause music bugs, please report any you find.)

 - Added several new tracks to "The Sound of Pig" for a total of 35
 - "The Sound of Pig" is no longer random, and pressing A now cycles through the whole tracklist.
 - Fixed Mom theme not having a channel 1 track
 - Added Cannonball to the Radio and as an unlockable track
 - Added Teehee Valley (radio only)
 - Updated Grullo Gorge cave sign text

 - Small fix for Lugia's Chamber music being overwritten by Surfing

July 3, 2019
------------
Minor update to fix:
 - Fixed incorrect Mom sprite when starting in Kanto
 - Fixed double text box during Big Rock decoration event
 - Removed redundant Azumarill Hydro Pump on Battle Tutor
 - Dodrio species text extra line fix
 - Removed extra Celadon Game Corner time event NPC
 - Fixed Maniac Gustav sight range being too long on Route 14
 - Fixed incorrect spelling of renovations on Silph Co 1F

July 1, 2019
------------
Minor update to fix:
 - Fixed Lake of Rage Gyarados having Dragon Rage twice at certain levels
 - Fixed injected Unown not showing proper form on starter select screen 
	 * always shows A if randomized, otherwise gets from injected DVs
 - Fixed Fast Ship lost child event showing follower movement during black screen
 - Fixed the following scripts not properly releasing followers after healing:
	 * Fibbef Cinnabar Tunnel
	 * Fibbef Mount Moon B2F
	 * Fibbef Route 7
	 * Fibbef Silver Cave
	 * Neph Route 28
	 * Neph Viridian Forest

June 29, 2019
-------------
Minor update to fix:
 - Injected starters not clearing PP properly
 - Leech seed being a duplicate event/battle tutor move for oddish family
 - Bill's house and Route 12 gate having incorrect palette data constants
