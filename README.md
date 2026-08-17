# ARGENFIFA resource pack

The texture pack the ARGENFIFA Minecraft server hands to players on join. Minecraft 26.2,
resource pack format 88.

Download: [latest release](../../releases/latest).

Nothing here is original work. It is fourteen published packs merged into one file so the
server can send a single URL, with the overlapping files resolved once instead of depending
on the order each player happened to drag them in.

## What it is made of

| Pack | Author |
| --- | --- |
| [Unique Dark Lite](https://modrinth.com/resourcepack/unique-dark) | AmongstReality |
| [Icons](https://modrinth.com/resourcepack/icons) | WeNAN Studios |
| qrafty's Capitalized Font | qrafty |
| [Weskerson's 3D Items](https://modrinth.com/resourcepack/tools-and-utils) | Weskerson |
| [Visual: Armor Trims](https://modrinth.com/resourcepack/visual-armor-trims) | Thanos |
| [Almost Vanilla Potions](https://modrinth.com/resourcepack/almost-vanilla-potions) | Delled |
| Even Better Enchants | Mythitorium |
| Low Fire, Shield & More | penetrator |
| [Vanilla Tweaks](https://vanillatweaks.net) | Vanilla Tweaks |
| [Better Lanterns](https://modrinth.com/resourcepack/better-lanterns) | Nico4play |
| [Clean Connected Glass](https://modrinth.com/resourcepack/clean-connected-glass) | 1_jammy |
| [Fresh Animations](https://modrinth.com/resourcepack/fresh-animations) + All Extensions + [Player](https://modrinth.com/resourcepack/fa-player-extension) | FreshLX |
| [Lively Turtle Helmet](https://modrinth.com/resourcepack/lively-turtle-helmet) | Angelos |

Please support the original authors on their project pages. If you are one of them and want
this taken down, open an issue and it goes.

## Optional client mods

The pack works without any mods, but three parts of it need one:

| Part | Needs |
| --- | --- |
| Fresh Animations, Lively Turtle Helmet | [Entity Model Features](https://modrinth.com/mod/entity-model-features) and [Entity Texture Features](https://modrinth.com/mod/entitytexturefeatures) |
| Clean Connected Glass | [Continuity](https://modrinth.com/mod/continuity) or OptiFine |

Without them those files are simply ignored. Nothing breaks.

## Note on fog

The Vanilla Tweaks `ClassicFog` option is deliberately left out. It replaces
`assets/minecraft/shaders/include/fog.glsl`, and Sodium draws terrain with its own
`assets/sodium/shaders/include/fog.glsl`, which no resource pack can reach. Use Sodium's own
fog settings instead.
