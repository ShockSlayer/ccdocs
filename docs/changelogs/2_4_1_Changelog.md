2.4.1
--------------
**Credits:**
NeedsMoreBirds - New Fef frontsprite 

**Preface:**
This update is mostly bugfixes, and a few QoL tweaks. Fixes and changes related to the new events added in 2.4.0 are at the very bottom, so if you don't want to be spoiled on those, then avoid reading further after the "Fixes:" section.

**QoL Changes:**
 - Nickname Palettes are now case-insensitive. So for example, a suitable Wobbuffet could be named "SANDBAG", "Sandbag", or even "sAnDbAg" and all of them would use the correct nickname palette.
 - The follower is now released after the Nurse turns the player around instead of before. This should usually result in it being released beside the player instead of in front.
 - Having an active chain now prevents fleeing for any non-roaming species that has a chance to do so.
 - Any encounters that previously scaled up to level 60 will now only scale as high as level 50. This is to address not being able to rematch certain species at Lv50 for the Underground Arena, Stadium 2, etc. after collecting too many badges.
 - The Cafe meals Stat Exp yield is now 4x when infected, and 2x by default. For a usable metric, when infected, a single Cafe meal will put a party member at cap in a Nuzlocke with "Limited growth" enabled.

**Gameplay Changes:**
 - Added a small event in Viridian Forest with an injured Kangaskhan.
 - Changed Viridian Forest fishing data
 - New Game+ will carry over the unlocked E4 Rematch reroll. (beating the E4 again twice will not unlock more rerolls however.)
 - Tweaked Super Nerd Stan and Scientist Justin's teams and levels slightly.
 - Firebreather Chase and Gentleman Rene have now switched positions in New Cinnabar Gym.
 - The base yields for most trainer classes have been increased.
 - After obtaining 8 badges: 
	 * Stat Exp gain in battle is increased to 2x. When infected, it goes from 3x to 4x.
	 * Regular exp gain is boosted by 1.5x. This stacks with trades, Lucky Egg, etc.
 - This is to help offset the amount of grinding required since the second set of Gyms scales much higher.

**New Music:**
 - Spark Mandrill: https://soundcloud.com/user-927422935-571023782/mega-man-x-spark-mandrill-8-bit
 - Bass's Theme: https://soundcloud.com/user-927422935-571023782/mm7-basss-theme-8-bit

**Fixes:**
*Nuzlocke:*
 - Fixed shiny explanation text having incorrect formatting
 - Fixed Stat Exp from items not calculating correctly when level growth not limited
 - Fixed fainting in the Bug Catching Contest screwing up the party
 - Fixed fainting to Pursuit not properly removing the affected party member

*SGB Border:*
 - Fixed Color Filter making the SGB border too bright (since it is already color corrected)
 - Fixed getting an egg from the DayCare man not requesting an SGB Border update

*Misc:*
 - Fixed Set 7 for Morty being slightly overleveled
 - Fixed Chuck's Arena Shuckle having Curse as a move.
 - Fixed renaming box sprite not loading correctly
 - Fixed map alignment/blockdata issues with Pewter City and Grullo Gorge
 - Fixed printing wrong name when reusing Sweet Scent
 - Fixed Nickname palettes allowing a partial match if the name was longer.
 - Updated a handful of outdated mom reference texts

**New Events Changes/Fixes: (Spoilers ahead)**
 - The palettes for the new areas have been tweaked to be more visually distinct.
 - Possible fix for Entei Chamber puzzle textbox glitch
 - Fixed Bill not calling after catching SNOWCAP
 - Fixed a crash when trying to deposit the Unown Tablet
 - Fixed "failed to catch" events not setting for Alph Forest Unowns when losing the battle
