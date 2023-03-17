# Extra Lives - Extended

### Requires version 0.G+

## **Features:**

Every scenario will start with you with 2 extra lives, which is also the maximum you can have.

Every 30 days you remain alive an extra life will be granted to you, up to your maximum extra lives.

Strange Stone Circles (SSC) can be found rarely in the wilderness, which contain statues that can be examined to set your current position as a respawn point. Only the most recently created respawn point is saved.

## **When you die:**

No matter what kind of respawn you undergo, you will always drop all worn, wielded and carried items upon death. An extra life is spent if available, and then you will be respawned; Healing your entire body, removing all negative conditions, resetting all needs to satisfied, etc. CBMs and mutations are retained, as is any mutagenic material inside you. There are 3 kinds of respawns you will experience:

1. **Respawning with extra lives available and an SSC respawn point set:** You may respawn where you died, or at your SSC respawn point. If you respawn where you died, you will gain 30 seconds of invisibility, incorporeality, 100% increased speed and will push back surrounding enemies 1-2 tiles.

2. **Respawning with extra lives available and no SSC respawn point set:** You will respawn where you died. Gain the same respawn benefits as above.

3. **Respawning with no extra lives available:** You will respawn very, **VERY** far away from where you died, in an unexplored region of the map. This will be a normal field, so you are not granted the respawn benefits. Can be as far as 800 overmap tiles away.

## **Notes:**

*The statues in the Strange Stone Circles are incredibly heavy, but not impossibly immovable...

*The random respawn takes some time to find a location to respawn you at. It's normal for the game to freeze up for a few moments while searching.

*While Incorporeal, you are not able to interact with most things or pickup items, but you are completely immune to all damage.

*The 30-day counter for an additional extra life is not affected by dying, or any other factor. You will reliably regain an extra life every 30 days.


## **Changelog**

**v1.0.2:** 
- Fixed logic with extra lives being set at 3 instead of 2.

**v1.0.1:** 
- Optimization and code formatting.
- Moved heal/condition reset to an EoC and call it per respawn function instead of defined in each respawn EoC.

**v1.0.0:** 
- Initial public release.