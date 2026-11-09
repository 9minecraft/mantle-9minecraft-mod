# Mantle — The Core Engine for Tinkers' Construct

Mantle 9minecraft Mod lays the shared foundation that Slime Knights mods like Tinkers' Construct are built on, bundling the common code, in-game guide books, fluid handling, and registration tools those mods rely on into one clean library. It runs nothing on its own screen - instead it quietly powers the features, recipes, and documentation of every mod that depends on it. Because it is a library, it adds no blocks, items, or buttons of its own - it is the engine behind other mods.

## What this build is

An unofficial rebuild of **SlimeKnights**'s original work, kept running on current Minecraft releases by 9Minecraft Studios. Not affiliated with the original author and not endorsed by them.

Most of the porting work sits in the mixin layer. Each Minecraft release moves or renames the methods this mod hooks into, so the hooks are re-pointed and re-tested against that version rather than rewritten. The behaviour underneath is upstream's and is deliberately left alone — that is the part that makes the mod feel right, and it is not ours to redesign.

## Source code

Upstream is licensed **MIT**. The port tree is not mirrored here; if you want it for review, for a fork, or to build it yourself, ask at **9minecraft.net@gmail.com** and it will be sent over.

## Versions

| Minecraft | Loader |
|---|---|
| 26.3 | NeoForge |
| 26.2 | NeoForge |

## Getting the built mod

Install steps, the dependency list, the screenshot gallery and what changed in each release are kept together on the download page:

[9minecraft.net/mantle-9minecraft-mod](https://www.9minecraft.net/mantle-9minecraft-mod/)

## Credits

Original work by **SlimeKnights**. Port and maintenance by 9Minecraft Studios. Licensed MIT; the upstream licence text ships inside every build.
