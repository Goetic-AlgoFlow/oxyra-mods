# Oxyra mods

The mod library of [Oxyra](https://github.com/Goetic-AlgoFlow/Oxyra), a personal build of
Horizon (Minecraft: Java Edition 26.3 rewritten in Rust), played from the
[Lithar](https://github.com/Goetic-AlgoFlow/Lithar) launcher.

Lithar reads [`index.json`](index.json) beside Horizon's own registry: on an Oxyra instance, these
mods show in **Browse content** and on the instance's mods page, with their author, and install in
one click. They are native mods: Lithar compiles them into the instance's game before its next
launch, on Oxyra's source.

| Mod | What it does |
|---|---|
| Oxyra API | The library the other mods share: their settings on their page in Options > Mods. Required by the others. |
| BetterF3 | The F3 screen as coloured modules in two columns. Port of cominixo's and TreyRuffy's BetterF3 (MIT). |
| Immersive Portals | See through Nether and End portals and cross them without a loading screen. After qouteall's Immersive Portals. |
| Mod Menu | A Mods button on the title screen and the pause menu; Options > Mods as Mod Menu lays it out. After TerraformersMC's Mod Menu. |
| Mouse Tweaks | Drag and wheel controls in inventories. After YaLTeR's Mouse Tweaks. |
| Particle Core | Draws only the particles you can see. |
| Physics | Broken blocks, explosions and dead mobs fall apart; doors and trapdoors swing. Inspired by haubna's Physics Mod (its behaviour only). |
| ShulkerBoxTooltip | A container's contents in its tooltip. Port of MisterPeModder's ShulkerBoxTooltip (MIT). |

Each mod's file is the release `<id>-<version>`. The mods are under the MIT license; a port keeps
its original's license notice inside its file.
