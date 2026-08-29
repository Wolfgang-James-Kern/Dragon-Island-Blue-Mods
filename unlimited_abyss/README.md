# Unlimited Abyss

This is a manifest-format mod for a Dragon Island Blue Mod Launcher. 
It changes two values in `Dungeon_15b.plist`:

- `creationData.lastFloor` is set to `2,147,483,647`.
- `creationData.waypointEvery` is set to `2,147,483,647`.

These are the largest signed 32-bit integer values and make the Abyss's floor
limit and waypoint interval effectively unreachable during ordinary play.

The mod changes no other dungeon data, game assets, executables, or save files.
