# Extra Lives - v1.2.0

### Requires Experimental Build cdda-windows-with-graphics-and-sounds-x64-2024-11-26-0822 or newer! 

## **Features:**

A choice of 5 difficulty levels, providing different amounts of starting lives, maximum extra lives, maximum extra lives cap, possible respawn options and the frequency of lives gained over time.

Every scenario will start with you with a number of extra lives, which is also the maximum you can have. This maximum can be increased in-game, to a cap.

Every 14/21/28/35 days you remain alive an extra life will be granted to you, up to your maximum extra lives, depending on your difficulty level.

Strange Stone Circles (SSC) can be found rarely in the wilderness, which contain altars that can be examined to set your current position as a respawn point. Only the most recently created respawn point is saved.

## **When you die:**

No matter what kind of respawn you undergo, you will always drop all worn, wielded and carried items upon death. An extra life is spent if available, and then you will be respawned; Healing your entire body, removing all negative conditions, resetting all needs to satisfied, etc. CBMs and mutations are retained, as is any mutagenic material inside you. There are 3 kinds of respawns you will experience:

**Here:** You respawn right where you died. You gain 60 seconds of great speed, invisibility, no fall damage, waterbreathing and 30 seconds of incorporeality (immune to most things but you cannot interact with physical matter). You also emit waves of force for 5 seconds, continually knocking back nearby enemies.

**At Strange Stone Circle:** Same effects as respawning Here, except you are only given this option if you have previously found and activated an altar in a Strange Stone Circle. Brings you back to that location.

**Randomly:** A random location  far away from your place of death in an unexplored region is selected and you are respawned there. You are granted 5 minutes of greater speed, invisibility, water breathing and fall damage immunity, and a temporary metaphysical body suit that provides cold climate protection (covers all parts of the body and can have anything worn over it).

## **Notes:**

- The altars in the Strange Stone Circles are incredibly heavy, but not impossibly immovable...

- The random respawn takes some time to find a location to respawn you at. It's normal for the game to freeze up for a few moments while searching.

- While Incorporeal, you are not able to interact with most things or pickup items, but you are completely immune to almost all damage.

- The day counter for an additional extra life is not affected by dying, or any other factor. You will reliably regain an extra life every 14/21/28/35 days, depending on difficulty.


## **Changelog**

**v1.2.0:** 
- Updated code to function in newer releases of the game

**v1.1.0:** 
- Complete overhaul of the mod's internal functions: There are now 5 difficulty levels to choose from, affecting factors such as extra lives, max extra lives, max extra lives cap, respawn options and life-gain-over-time.
- Added logic to respawning that factors in certain variables and states when offering you your respawn options.
- New location added, related to increasing maximum extra lives and/or gaining an extra life.
- Random respawn now gives you a special, metaphysical bodysuit that provides protection from cold climates. Anything can be worn over it and it does not count towards encumbrance. Note however, that it cannot be removed once worn, and it lasts only a few hours before disintegrating. Previous system of cold protection did not work as intended.
- Added missions adapted to the purpose of finding your corpse/dropped items, and showing the location of your selected respawn point.
- Added Respawn Info Tablet, crafted with a single rock while near a respawn altar. Shows you your difficulty setting, info about your current, max and cap on extra lives, and shows you your respawn point via mission menu / map.
- Various small tweaks and number changes.

**v1.0.3:** 
- Added temperature resistance to respawn effects. 5 minutes for respawns with an extra life available, and randwom respawn grants 2 hours worth.

**v1.0.2:** 
- Fixed logic with extra lives being set at 3 instead of 2.

**v1.0.1:** 
- Optimization and code formatting.
- Moved heal/condition reset to an EoC and call it per respawn function instead of defined in each respawn EoC.

**v1.0.0:** 
- Initial public release.