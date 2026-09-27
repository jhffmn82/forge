# Forge of the Elements — Beta 1.3

**September 27, 2026.** Beta 1.3 release notes for the public beta, playtest and itch.io builds.

## Graphics and presentation

- Refreshed environment floors, walls, fixtures, props, traps and vegetation using detailed source art across the dungeon, later biomes and elemental planes. Terrain contours, generated layouts and object footprints are preserved.
- Replaced the old low-resolution pebble decoration layer, including the scattered stones beside walls.
- Crates, pots and barrels show one detailed object per placement instead of a group. Their collision and loot are unchanged.
- Corrected the new Goblin family artwork's facing, including Grukk, attack animations and corpses.
- The Crypt Shambler has new artwork and animated idle, dragging walk, attack and death poses. Its fallen body, revival and combat behavior are preserved.
- Moss patches have organic edges and fine 128px texture. Crypt floor stains no longer trace the old floor's coarse grout pattern.
- Pots and skeletal remains are 20% smaller, keeping their existing placement and interaction footprint.
- Floor chains are half their previous size.
- Cavern kobold crates also draw as one object; removed a separate renderer that still duplicated them into clusters.
- Cavern crystal pylons are 45% smaller, with matching sparkle effects, so they fit alongside doors and other scenery.
- Cave bridges use detailed painted planks, metal fastenings and rope, rendered in continuous 128px sections along their existing crossings.
- Natural Cavern and Underdark walls use detailed rock artwork with blended face shading, retaining each biome's colors and the existing room shapes.
- Cave walls in all six elemental planes use the detailed 128px rock material, with each plane's colors and mineral veins.
- Nearby light reaches 20% farther into visible Cavern and Underdark rock, making the wall detail easier to read while retaining fog of war and the existing floor lighting.
- Underdark temple and natural floors use newly painted sources with true 128px detail per tile, including mixed-region boundaries. Existing floor layouts and hazards are preserved.
- Open doors use their matching wood or iron artwork, with visible floor through the opening. Sideways doors stay attached to their hinge instead of leaving a detached plank across the wall.
- Fixed thin bright Dungeon wall seams at fractional camera positions by baking the existing wall shading into cached textures, in both the preview and ordinary runs.
- Enemy outline and ambient silhouette effects use half their former opacity, keeping sprites and world light sources unchanged.
- Underdark volcanic caves use the Plane of Fire's basalt ground material, with their existing cave walls, shadows and lava hazards.
- Nine ordinary trap types now use their refreshed sprites, retaining their discovery rules, triggers and animated effects.
- The Unmaker's three beam pylons have dedicated sprites with separate idle and charging animations.
- The local Sandbox inspector can open directly with a revealed map, frozen enemies and click-to-teleport. Its Depth selector covers all 25 floors and six elemental planes; inspection stays separate from adventure saves.
- Block Art is available in Options and remembers your choice. Map scenery, actors, doors, traps, remains and special features follow the same block display mode.

## Changes

- The title screen uses the instrumental menu theme and continues it into character creation. Level-up and victory sound effects play at half their previous volume, preserving your chosen volume settings.
- Replaced Grukk's first-boss music with a subdued ambient loop of low sustained tones and quiet dungeon sounds, leaving combat audio clear.
- Cursed rings apply their intended penalties. Mending drains life rather than silently doing nothing, Keen Eyes worsens trap spotting, and old cursed rings with positive upgrade values no longer grant benefits. Item descriptions reflect these effects.
- Amulet curses stay hidden when equipped. Using one reveals the curse, spends a charge and triggers a random trap instead of the normal ability. Explicit identification can still reveal the curse safely; a revealed cursed amulet must be cleansed before removal.
- Ordinary Goblins have 11 HP instead of 16 on floors 1–2, shortening the opening fights. Rats keep their original 8 HP. Existing saves receive the Goblin adjustment without healing wounded enemies; later floors and stronger variants keep their health.
- Single-target spells trigger general on-hit effects, including weapon enchantments, elemental bonuses and combinations, Molten Ring, and Sylla's Web and concealed opening strike. Magic Missile and divine bolts follow the same rules. Secondary damage cannot trigger these effects again; area and piercing spells retain their existing scope.
- Damage labels consistently use physical, poison, light, shadow, frost, fire, magic and lightning. Fixed Air attacks being labeled as air damage, mixed-element bonus labels, and repeated spells using the wrong damage type or applying resistance twice.
- Dungeon Rats and Goblins hit less hard on the first floor, making the opening fights more forgiving. Their damage on later floors is unchanged.
- The final Forge of the Elements has dedicated animated artwork, with six elemental sources feeding its anvil. Existing final-chamber saves receive the new art.
- Victory and defeat screens show your final score, build and accomplishments, with a score breakdown. Previous Runs keeps a local high-score list with winners first. Sandbox runs are excluded.
- Scoring rewards XP and essence earned relative to turns taken, together with depth, level and faith progress. Winning multiplies the result, and spending essence does not reduce earned essence. Earlier scores remain in their own groups; older saves clearly label estimated earnings.
- Previous Runs and Settings are available from the title screen. Character creation has a Back button, and audio, display and key bindings can be adjusted before starting a run. Motion preferences now persist.
- The Unmaker calls reinforcements throughout the battle. In phase two, three crystal pylons independently charge beams while the boss attacks other areas. Distinct warning colors and charge bars show overlapping threats; the marked floor remains free of numbers.
- Boss cores land on reachable ground, separately from other treasure, even when a boss dies outside its lair. Affected saves recover missing or inaccessible cores.
- A loot-filled Caverns boss chamber still opens its exit instead of ending the adventure early.
- Fixed lethal reflected damage leaving the Light realm stuck. Saves interrupted by that bug recover at one HP; completed deaths remain final.
- Glimmer and Light mastery create matching Holy Ground with consistent healing, protection, damage and visuals. Overlapping fields use the stronger effect, and Glimmer's healing boon applies consistently.
- Dawn damages visible enemies as well as blinding and revealing them. Blinded enemies are vulnerable to surprise attacks.
- Glacial Tomb blasts nearby enemies while entombing its central target. Upheaval's rising walls damage and Root nearby enemies and summons, while sparing the caster. Both show their full targeting areas; Upheaval spends nothing when no walls can be created.
- Rooted, stunned and incapacitated creatures lose their Evasion until they recover. Combat and character displays use the same effective value.
- Light weapon enchantments improve critical chance, replacing their previous accuracy and extra damage bonuses.
- Fortitude recovers more often and is not wasted on fully absorbed blows. Selected nimble creatures have more Evasion, making Accuracy more useful.
- Rock Slimes spit rooting stone, Shades chill with their touch, and Lens Bearers fire blinding Light beams. Elemental attack damage respects defenses; the entire Light-realm roster is vulnerable to Shadow.
- Fixed omitted Vellum equipment bonuses and matching item descriptions. Clarified Reginald's universal bonuses and standardized ability and item descriptions to use %.
- Tourists start with a Hawaiian Shirt and dedicated artwork. Invalid puzzle sigils no longer spawn; existing malformed sigils are repaired when loaded.
- Fixed the Deep Maw's pit overlap and exit rectangle, corrected the female Gloomling's raised weapon positions while walking, and made magical summons dissipate without leaving borrowed corpses.

These notes describe the completed changes included in Beta 1.3.
