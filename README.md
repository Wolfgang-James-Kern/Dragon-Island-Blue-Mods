# Dragon Island Blue mods

This folder contains manifest-format mods for to be used with a Dragon Island Blue Mod
Launcher. Each mod is kept in its own self-contained folder:

- `less_rare_monsters`: raises selected rare-monster encounter chances to
  approximately 20% at their listed locations.
- `unlimited_abyss`: raises the Abyss floor and waypoint limits to the largest
  signed 32-bit integer.

## Installing a mod on Duke Lindenhurst's launcher

1. Copy the complete mod folder into the launcher's `DIB_mods` folder.
2. Start the launcher and select **Rescan** if it is already open.
3. Enable the mod.
4. Select **Apply** or **Apply & Launch**.

Do not use **Import Mod** for these ready-made manifests. That command creates a
new manifest by comparing modified game files. These mods already contain the
required `mod.json` and should be copied directly into `DIB_mods` under their own folder.