# Third-party assets

## Kenney — service yards and parking additions

- Author: Kenney. License: [CC0 1.0 Universal](https://creativecommons.org/publicdomain/zero/1.0/).
- [Car Kit](https://kenney.nl/assets/car-kit): `van`, `delivery-flat`, `tractor-shovel`, stored as `vehicle-van.glb`, `vehicle-flatbed.glb`, `vehicle-loader.glb`.
- [Factory Kit](https://kenney.nl/assets/factory-kit): `machine-fortified`, `box-wide`, `conveyor-long-stripe`, `catwalk-stairs`, stored as `prop-generator.glb`, `prop-cargo-case.glb`, `prop-conveyor.glb`, `prop-metal-stairs.glb`.
- Downloaded from the author's website. Palette textures embedded; materials use rough, lit surfaces for the existing night lighting. Geometry preserved. Collision sections generated offline from these GLBs.

## Zsky — Shotgun Ammo

- Source: [Shotgun Ammo by Zsky](https://poly.pizza/m/7VSzqHwebM)
- License: [Creative Commons Attribution 3.0 Unported](https://creativecommons.org/licenses/by/3.0/)
- Local file: `assets/models/pickup-shotgun-shells.glb`.
- Modification: removed the source model's box primitives and rearranged one red shotgun cartridge with its brass base into three enlarged shells (two standing, one lying) above the game's ammunition box; scaled by standing-shell height for the pickup display.

## Quaternius — Zombie Apocalypse Kit

- Source: <https://quaternius.com/packs/zombieapocalypsekit.html>
- Author: Quaternius
- License: [CC0 1.0 Universal](https://creativecommons.org/publicdomain/zero/1.0/)
- Local files: `assets/models/*.gltf`
- Uses: animated infected variants, pickup, truck, barrels, first-person pistol, and AR.
- Multiplayer operators: `player-matt.gltf` and `player-lis.gltf`, from `Characters_Matt_SingleWeapon.gltf` and `Characters_Lis_SingleWeapon.gltf`. [Pack mirror](https://github.com/agentkaerf/FreeModels/tree/main/Zombie%20Apocalypse%20Kit%20-%20March%202024/Characters/glTF), used because the author's Drive download quota was exceeded. Original embedded geometry, textures and clips retained. Runtime hides handheld props, selects basic locomotion clips, and adds a seeded color patch and optional backpack. No first-person body is rendered.

The source pack permits use in personal and commercial projects. Attribution is not required by CC0, but the source is retained here for provenance.

## Quaternius — Ultimate Monsters

- Source: <https://quaternius.com/packs/ultimatemonsters.html>
- GLB repack: <https://github.com/Hakhyun-Kim/constellation-defense/tree/main/assets/models>
- Author: Quaternius
- License: [CC0 1.0 Universal](https://creativecommons.org/publicdomain/zero/1.0/)
- Local files: `assets/models/enemy-*.glb`
- Uses: animated alien, demon, orc, skull-orc, yeti, green-blob and mushroom-king enemy silhouettes.

The repack preserves the original geometry, materials, and animations while packaging each character as a self-contained GLB.

## Quaternius — Bullets Pickup

- Source: <https://poly.pizza/m/bTEYFxKHF9>
- Author: Quaternius
- License: [CC0 1.0 Universal](https://creativecommons.org/publicdomain/zero/1.0/)
- Local file: `assets/models/pickup-bullets.glb`
- Use: detailed ammunition displayed on pistol and rifle pickup boxes.

## Pichuliru — Katana

- Source: <https://poly.pizza/m/15A7InejC7>
- Author: Pichuliru
- License: [CC0 1.0 Universal](https://creativecommons.org/publicdomain/zero/1.0/)
- Local file: `assets/models/katana.glb`
- Use: dedicated first-person katana with a procedural three-strike attack sequence.

## Pichuliru — Reflex Sight

- Source: <https://poly.pizza/m/MiM3JXxODE>
- Author: Pichuliru
- License: [CC0 1.0 Universal](https://creativecommons.org/publicdomain/zero/1.0/)
- Local file: `assets/models/reflex-sight.glb`
- Use: rail-mounted reflex sight on the first-person AR.


## Kenney — environment expansion

Author: Kenney. License: [CC0 1.0 Universal](https://creativecommons.org/publicdomain/zero/1.0/).
Downloaded from the original author packs; the listed filenames identify the source models.

| Pack / source | Source models | Local files |
| --- | --- | --- |
| [City Kit Industrial](https://kenney.nl/assets/city-kit-industrial) | `building-a`, `building-c`, `building-g`, `shipping-container-a` | `building-warehouse.glb`, `building-workshop.glb`, `building-factory.glb`, `prop-container.glb` |
| [City Kit Suburban](https://kenney.nl/assets/city-kit-suburban) | `building-type-b` | `building-house.glb` |
| [Car Kit](https://kenney.nl/assets/car-kit) | `sedan`, `suv`, `ambulance`, `garbage-truck` | `vehicle-sedan.glb`, `vehicle-suv.glb`, `vehicle-ambulance.glb`, `vehicle-garbage.glb` |
| Car Kit | `debris-tire`, `debris-door`, `debris-bumper`, `box`, `cone` | `prop-tire.glb`, `prop-car-door.glb`, `prop-bumper.glb`, `prop-box.glb`, `prop-cone.glb` |
| [Retro Urban Kit](https://kenney.nl/assets/retro-urban-kit) | `detail-dumpster-open`, `pallet`, `planks`, `detail-bricks-type-a` | `prop-dumpster.glb`, `prop-pallet.glb`, `prop-planks.glb`, `prop-bricks.glb` |

All local files are under `assets/models/`. Pack-specific textures were embedded as data URIs inside each GLB to avoid external dependencies and collisions between identically named palette textures. Retro Urban materials were changed from unlit to rough, nonmetallic lit materials for the night scene; geometry was preserved. Some vehicle instances receive additional color tints.


## Kenney — Blaster Kit

- Source: <https://kenney.nl/assets/blaster-kit>
- Author: Kenney
- License: CC0 1.0 Universal
- Source models: `blaster-n.glb`, `grenade-a.glb`
- Local files: `assets/models/weapon-shotgun.glb`, `assets/models/pickup-grenade.glb`
- Uses: fourth weapon and grenade drops / projectiles. Palette textures are embedded locally.

## Lucide — interface icons

- Source: <https://lucide.dev/license> and <https://github.com/lucide-icons/lucide>
- License: ISC, with the included MIT notice for inherited Feather icons.
- Local SVGs and full license notices: `assets/icons/`.
- Uses: centered touch-control icons and grenade inventory indicator.

Bullet impact textures, soil noise and blood effects are generated by project code, without external image dependencies.


## Nekis5_3D — Military Equipment Pack

- Source: [Military Equipment Pack – Helmets, Vests & Backpacks (FREE)](https://nekis5-3d.itch.io/military-equipment-pack-helmets-vests-backpacks-game-ready).
- Author: Nekis5_3D. The author permits personal and commercial use; credit is appreciated.
- Archive: `military ammunition.zip`; source scene: `bulletproof vest.fbx`, selected mesh: `Cube002`.
- Local file: `assets/models/pickup-armor.glb`.
- Use: floating body-armor pickup in all game modes.
- Adaptation: extracted the vest from the combined scene, baked its static pose, removed unused skin attributes, normalized its height, and applied matte olive materials for the game's night lighting. No source textures are required at runtime.
- Reproducible conversion: `scripts/import-armor-model.cjs` with the extracted archive directory and a local Vite server.
- Full archive inventory: [MILITARY_EQUIPMENT_PACK.md](MILITARY_EQUIPMENT_PACK.md).

## Recorded weapon handling audio

Pump-action and reload clips in `assets/audio/` use CC0 recordings by **zer0_sol** and **SpringySpringo**. Sources, exact original filenames, licensing and adaptations are documented in [assets/audio/LICENSE.md](assets/audio/LICENSE.md). Only mechanical handling sounds are taken from these recordings.

Grenade blasts use **Joth**'s [Chunky Explosion](https://opengameart.org/content/chunky-explosion), licensed CC0 1.0, edited for a shorter, softer high-frequency tail. See [assets/audio/LICENSE.md](assets/audio/LICENSE.md) for the conversion details.

Lis/Matt breathing and pain, and all creature voices, use CC0 recordings by AuraVoice, Ashe Kirk / Owlish Media, qubodup, Joseph SARDIN / BigSoundBank and Ogrebane. The 17 local clips, source links and adaptations are documented in [assets/audio/voices/LICENSE.md](assets/audio/voices/LICENSE.md); exact excerpts and source hashes are in `assets/audio/voices/provenance.json`. Profiles and extensible variant arrays live in `src/config/voices.js`.

## Field upgrade icons

Source: [Game-icons.net](https://game-icons.net/) / [SVG repository](https://github.com/game-icons/icons).
License: [Creative Commons Attribution 3.0](https://creativecommons.org/licenses/by/3.0/).
Local files: `assets/icons/upgrades/`.

- Delapouite: [running-shoe](https://game-icons.net/1x1/delapouite/running-shoe.html), [jump-across](https://game-icons.net/1x1/delapouite/jump-across.html), [shotgun-rounds](https://game-icons.net/1x1/delapouite/shotgun-rounds.html), [heart-beats](https://game-icons.net/1x1/delapouite/heart-beats.html).
- Lorc: [auto-repair](https://game-icons.net/1x1/lorc/auto-repair.html), [strong](https://game-icons.net/1x1/lorc/strong.html).
- sbed: [ammo-box](https://game-icons.net/1x1/sbed/ammo-box.html).

SVG shapes are unchanged; their black backgrounds are removed for transparent cards and CSS applies the game's yellow tint.
