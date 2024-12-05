2.5.11
--------------
## Preface:

Nothing has changed about anything I wrote in the 2.5.9 changelog preface. If you haven't read that, I suggest you do.

I've basically spent the entirety of this year working on other things, while slowly collecting any bugs found in CC. I've fixed each one that's come up, and I added a little something extra just for fun.

## Professor Oak's Challenge:

One of the things people have told me they like about CC is how friendly the game is for challenge runs. Among the different variations lies "Professor Oak's Challenge" - the act of filling out the Dex as much as possible before each gym. Considering that the entire Dex can be completed before challenging a single gym, I thought it would be fun to add a little something for completing that.

 - Speaking to Prof. Oak with a completed Dex and zero badges on a non-New Game+ file will allow you to challenge him at his full strength. If defeated, he will pass on his special technique. This will carry over into New Game+.

## Misc changes/QoL:

A handful of Gen 1 TM moves that were incorrectly assigned to certain species have been moved to the Battle Tutor. Additionally, Politoed can now obtain Body Slam, and Hitmonchan can now obtain Mega Punch through the Kanto TM tutor. Ultimately there are no moveset changes, just minor shifts in which tutor they belong to.

 - Gym Rechallenges now have an animation for healing the party. Occasionally people would get confused about this.
 - Added a print intensity NPC in the Ruins of Alph Research Center

## Fixes:
 - Restored the stock delay to the SGB border implementation. Modern emulators now require it.
 - Fixed evolution stones and Tradeback Guy not allowing evolution if a party member is at the exact level cap in Nuzlocke Mode.
 - Hatching eggs in the Bike Shop, Modification Station, and Underground will correctly set caught location.
 - A Mewtwo hatched from Origin Plains will properly display "Hatched" on the stats screen.
 - Fixed Perish Song always failing in wild battles.
 - Fixed link battle screen displaying incorrect graphics instead of "VS".
 - Adjusted footprints on Route 1.
 - Fixed Battle Tutor teaching HM moves without HMs.
 - Fixed Genetic Fabricator not registering the species as caught.
 - Fixed shiny animation on the Dex's register screen being 8px too high.
 - Fixed Noak having two Murkrows.
 - Fixed incorrect nicknames for Cat and Grizz.
 - Fixed a typo in Sprout Tower 3F.