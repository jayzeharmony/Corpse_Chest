# Corpse Chest

**Version:1.0.2**

**Short description:**

Factorio mod to retain player inventory in a chest after the player dies.

**Long description:**

Normally, when your character dies in Factorio, all of your inventory is lost. This mod spawns a container (and tombstone) at the location of your character (at the time of death) and fills it with whatever you had in your inventory. All player inventories and all items are supported. Currently items in the player crafting queue are not transferred to the container upon death, they are simply lost.

**Changelog:**
- 1.0.0 - Initial release.
- 1.0.1 - Added German and Dutch localization. (Thanks to apcnc and fps_holland @ forums.factorio.com.)
- 1.0.2 - Added entity validation to corpse decay code. (Thanks to Cyber_Garret @ forums.factorio.com for the find.) Issue #9

**ToDo:**

- Make corpse visible on radar/map screen.
- Is it possible to customize the tombstone based on the player/character who spanwed it?
- Add support for items in the craft queue.
- Allow user to set "corpse decay time".
- Performance improvement: Set on_tick call to only check for corpse decay once every specified interval.
