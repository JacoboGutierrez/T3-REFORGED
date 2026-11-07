# T3: REFORGED

Created with T3-ModTools Generate mod pack.

## Included mods (highest priority first)

1. Dual WM-32 Plasma (wm32_dual), version 1.0.5
2. Dual WM-27 Plasma (wm27_dual), version 1.0.1
3. WM-32 Plasma (wm32_plasma), version 1.0.0
4. WM-27 Plasma (wm27), version 1.1.0
5. T3 - Enhanced SFX (t3_enhanced_sfx), version 1.2.2
6. T-900 Heavy Assault (t900_heavy_assault), version 0.11.30
7. Fixed Weapons (fixed_weapons), version 1.3.0
8. T3 Original Soundtracks (t3_original_soundtracks), version 1.0.0
9. T3 - Enhanced Units (t3_enhanced_units), version 1.0.0

Contains 337 asset files and 339 executable patches. The highest enabled source owns duplicate internal paths. MERGE_REPORT.json records sources, file hashes, resolved overlaps, and the original IDs of executable patches.

## Using this pack

This is a static snapshot. Its source mods are disabled after creation and their folders are retained. Use Build Mods + Modded EXE to compile it. Creating a pack does not rebuild the currently installed game outputs.

Executable patches are validated together against the original binaries; incompatible writes abort creation. Runtime generators are synchronized before the snapshot; the pack includes their static patch output. Verified legacy ANM patches are replaced by the compiler's automatic animation support, not copied as obsolete writes. Animation variant configuration is preserved in anm_variants.json when present. Create a new pack to include future source updates. Development scripts and other files outside files/ are not bundled, except the patch manifest and animation variant configuration. Runtime files loaded directly from a source mod folder still require that folder at its original location; the snapshot does not relocate external DLLs embedded in patches.
