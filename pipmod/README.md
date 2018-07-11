A rather simple mod that rebalances weapons and adds some modified ships.

Most weapons will now deal roughly half their previous damage. Missiles have been reworked, most deal higher damage than guns.

Modified freighters with fighter or drone slots have been added. They appear in the shipyard. I would have preferred to make this as an outfit, but unfortunately outfits cannot add gun, turret or fighter/drone slots.

Full changelog within.

Download[www.dropbox.com]


If anyone knows a better workaround for modifying how many slots a ship has, let me know.



airtroopthreeninetwo  has Endless Sky Nov 27, 2015 @ 11:10pm 
Works great, but why are some of the values weird?
Case in point, the Screamer pod has 137.14 shield damage/s, 325.71 hull damage/s, 8.5714 shots/s... so forth.

EDIT: found some typos, will list here

pipmod ships.txt
"Most commony used by pirates or bounty hunters" -- Mod. Hauler II
"reduction in structural integrity" -- to struct. integ?, Mod. Hauler III

pipmod weapons.txt
"Named for it's distinctive" -- no apos., Screamer Pod
"which is ironically also the designed of the Anti-Missile Turret" -- Tomahawk Launcher



Pipsqueak  has Endless Sky Nov 28, 2015 @ 12:18am 
Thanks, updated to fix that. Ships and variants should also be outfitted with the correct missile weapons.
The Sidewinder II Magazine has been added, an option for larger ships to bring the Sidewinder II Launcher back up to 14 mass and 50 capacity.

The Screamer's strange weapon stats are an artifact of how firerates are handled in-game. Instead of having a firerate of 8.5, it has a reload of 7, which means 7 frames in-between launches. There is no neat way to get exactly 8.5 shots/s.
