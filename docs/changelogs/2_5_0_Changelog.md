2.5.0
--------------
## Special Thanks:

This update wouldn't be possible without a lot of people. Thanks to the bug testers as always for finding all the obvious stuff that makes me wonder if I can code, Rangi for help with optimization, those of you who showed up to the streams to keep me company and let me bounce ideas around, and of course the people who submitted their feature requests.

## Preface:

Early in December, 2021, I opened up a feature requests channel in the Discord to see if anyone could come up with anything good. And to my surprise, there were a handful of decent suggestions, from minor tweaks to major gaps that needed to be filled. Naturally I didn't get to everything, but I was able to tackle a few that I'm certain everyone will enjoy. Don't worry, I didn't take anything that compromises the vision of the game or breaks compatibility. I also took this as a chance to get to a few things that have been bothering me personally; either things I've seen the community struggle with, or things I tried to do in previous versions but ended up canning for any variety of reasons.

There's a ton of backend work on this update, music optimization, gfx compression, unused code/gfx removal, etc. Space is certainly getting tighter, but I have just enough at the moment for the likely handful of bugfixes that will follow this update.

Last thing - this changelog is a bit spoilery, so if you want to experience everything without existing knowledge of what it's about, just update and put Tohjo Falls and the Whirl Islands on your "to visit" list.

# New Areas:

![](images/2_5_0_Changelog/image_2.png)

**Expanded Tohjo Falls**
 - Now has a lost book which may contain some important hints...
 - More waterfalls which enter the upper level

**Added Tohjo Falls 2F**
 - Has Ice Rock Smash encounters
 - Another place to catch Squirtle, Sneasel, and Delibird
 - Overworld Starmie event (resettable via E4)
 - Exit to the top of Route 27 (which now has some hidden ledge tiles)
 - A few hidden items you won't want to miss

**Added Lake Tohjo**
 - Is a new landmark (reflected in the Town Map layout)
 - While surfing, the party will be healed after every encounter.
 - Has several swarming overworld encounters
	 * first visit will always be Stantler, after that they reset daily
	 * boosted shiny odds, scale with badges, and come with bonus moves
	 * Smeargle uniquely always gets a random move
 - There is a small camera panning event to see the swarm from the mountain after entering (for resetting easier)
	 * Activated from the top corner of the ledge to the far right
 - Has a central island surrounded by whirlpools that starts the **Origin Plains** event

**Added Origin Plains**
 - Is a new landmark (reflected in the Town Map layout)
 - There are 4 different unlock conditions that change the area drastically.
 - Resettable via E4
 - You'll have to discover the rest yourself. Have fun!

# New Events:

**Victory Road:**
 - Added a new event in Victory Road, that gives a new item!
 - Added an NPC in the Victory Road Gate to hint at the event
 - Added 3x Rare Candies as an item prize at the end of Victory Road

Added two additional fruit trees in the overworld
 - Berry on Route 39
 - Gold Berry on Route 3

Added a GATE KEY somewhere in Fuchsia City

# Quality of Life:

![](images/2_5_0_Changelog/image_1.png)

Added 5 more RGB Tweaker palette slots
 - The Dex now has an extended UI to more effectively manage slots

Gym Statues now display the level cap before the badge is earned

Added Deleveler NPC in Modification Station
 - Can set level 100 down to 98
 - Can set level 51+ down to 50

When chaining during the Bug Catching Contest, chains build 5x faster (so +5 for every battle instead of the usual +1)

Flash is no longer needed for the Whirl Islands

Removed some ledges in Whirl Islands (North East)
 - This allows a path to Lugia when coming from the residence

# Shadow Lugia:

[![Shadow Lugia](images/2_5_0_Changelog/thumbnail.png)](https://www.youtube.com/watch?v=MOkQgotLMlw "Shadow Lugia")

[(Youtube Video)](https://www.youtube.com/watch?v=MOkQgotLMlw "Shadow Lugia")

Ever since the discovery of Nickname Palettes, trainers have often tried and failed to capture the dark essence of XD001. Even with all that power, the technical limitations of the sprite medium kept the world safe from such a terrifying beast. Unfortunately for the world, there are now shadowy methods for trainers to close the door Lugia's heart and awaken the darkess within.

Earthquakes beneath the waves have jeopardized the balance of the Whirl Islands, exposing 3 glowing orbs, pondered by many to be crucial keys to the stability of the region, and the forces that guard them. There are those nearby who may be able to offer some insight in to what goes on in the caves. One shudders to think what might happen if they're not protected.

Legends speak of the guardian of the seas being seen during the night of a storm, and that it was capable of calming it. The power to manipulate the weather would be quite an edge in battle, drawing the eyes of many power-seeking trainers with ill intent. Perhaps those ill intentions have been made manifest elsewhere within the world, but hopefully they'll stay buried.

---

XD001 is the first (and likely only) Nickname Form - an alternate set of sprites loaded when a certain nickname is present. However, due to the unique nature of the nickname, it is unobtainable by simply visiting the Name Rater. Additionally, it is NOT a nickname palette - this means that not only can you apply any colors of your choosing, but it can also be shiny hunted. There wasn't really canon data for what a shiny would look like so I tried to come up with something unique.

Aside from having a bonus follower interaction, Shadow Lugia functions identically to a regular Lugia with one notable exception - when leading with it(and only when leading with it,) the battle will start with Rain Dance active. This will also override any other battles that may start with weather. The rain will last for over 250 turns, but can be replaced with other standard weather.

# Misc Tweaks:

![](images/2_5_0_Changelog/image_3.png)

Swapped Sabrina and Janine on the trainer card screen

Level now prints in the top right corner and with the :L icon on the switch moves/move deleter screen

Fleshed out the machines in Acetrainer HQ with some more text

Added battle start weather
 - E4 trainers will have different weather depending on their team
 - Battling wild Ho-Oh will have Sun, and Lugia will have Rain

Fuchsia City now uses the Cerulean music

Added SKULKRAKEN nickname palette for Gyarados (Max Shiny DVs)

Added a custom palette set for the Whirl Islands

Tweaked Doom's E4 team

# New Music:

While optimizing, I ended up tweaking Dynamo's theme and replacing Together We Ride with a new version entirely.

[Dynamo's Theme](https://soundcloud.com/user-927422935-571023782/mmx5-dynamos-theme-8-bit-v2)

[Together We Ride](https://soundcloud.com/user-927422935-571023782/fire-emblem-remix-8-bit)

[Blood Drain Again](https://soundcloud.com/user-927422935-571023782/blood-drain-again-8-bit)
 - Cedsi now uses this as his battle theme

[Lake Tohjo](https://soundcloud.com/user-927422935-571023782/crystal-clear-lake-tohjo-8-bit)

[Origin Plains](https://soundcloud.com/user-927422935-571023782/crystal-clear-origin-plains)

[Ho-Oh Appears](https://soundcloud.com/user-927422935-571023782/heart-gold-ho-oh-appears-8-bit)

[After Lugia Appears](https://soundcloud.com/user-927422935-571023782/soul-silver-after-lugia-appears-8-bit)

# Fixes:
 - Fixed Unown Tutor not having correct table start entry
 - SGB border refreshes properly after receiving an egg
 - Hatching an Unown egg will display the proper form. (Vanilla bug!)
 - Fixed some "recieved" spelling errors
 - Fixed using the Ancient Pick not updating sprites properly
 - Gyms no longer overwrite other specialphonecalls
 - NPC trades now validate the party's held items when in Nuzlocke Mode 
 - Fixed overworld Town Maps sometimes loading the wrong region
 - Fixed Bill not calling after catching Suicune if the box is full
 - Sprout Tower 3F will now always load the default NPC configuration when entering from the back after obtaining the Rainbow Wing
 - Using the Luster or Booster Ball will now reduce the target to 1HP (fixes the max HP from DVs changing)
 - The SGB border will now properly load the vanilla palettes when loading the game if that dex option is set
 - Sweet Scent will now properly check if the Bug Catching Contest is over before allowing the player to reuse it
 - When purchasing a residence, the time of day palettes will not update while Randy's face is present.
 - Fixed Lugia Chamber music persisting when exiting the map
 - Radio can no longer be opened in areas that don't allow forced music
