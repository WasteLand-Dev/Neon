# Neon
```v20.6.0.10-Release```
```Stable``` ```1.20.1```
## Moved to codeberg
https://codeberg.org/WasteLandOrigin/Neon

Happy summer!

## About
A ```lightweight``` modpack for vanilla minecraft, with some nice tweaks and seriously raised performance. Made to play on vanilla (no mods) servers or you can create your own modpack on this.

## Steam deck and controllers compatibility
- Use [Controlify](https://modrinth.com/mod/controlify)
- Controlify comes with a huge range of settings to fine-tune each of your controllers individually, including vibration strength, every single controller input bind (no hardcoding!) and more.

### Changelog:
- Update CleanF3
- Update ImmediatelyFast
- Update betterstats
- Update fabric-api
- Update fasterrandom
- Update modernfix
- Update ComplementaryReimagined
- New! Add ComplementaryUnbound
- New! Add EpochShader
- Update snowimagined
- Update SoftVoxelsLite
- Update Voyager shader
- Update rethinking-voxels
- Update superdupervanilla

## List of optimization and bugfix mods:
```
ImmediatelyFast - generally optimizes all immediate mode rendering by using a custom buffer implementation which batches draw calls and uploads data to the GPU in a more efficient way.
Sodium - free and open-source mod for Minecraft 1.16+ clients which greatly improves rendering performance while fixing some graphical issues.
Starlight - Fabric mod for rewriting the light engine to fix lighting performance and lighting errors.
Entity Culling - Using async path-tracing to skip rendering Block/Entities that are not visible.
Memory Leak Fix - A mod that fixes multiple memory leaks in Minecraft. Both server-side & client-side
lazy-language-loader - lazy-language-loader improves loading times when changing your language by only reloading the language instead of all the game resources!
Enhanced Block Entities - aims to increase the performance of block entity rendering, as well as offer customizability via resource packs.
Model Gap FIX - This is a simple client mod that fixes https://bugs.mojang.com/browse/MC-73186
Debugify - a project that fixes over 70 bugs found on the bug tracker in Minecraft.
Faster Random - this mod is a very basic one, it just replaces every Random.Next() call in MathHelper, giving a modest performance boost, and somehow makes minecraft load faster in some cases.
Extended Clouds - This mod makes Minecraft cloud's rendering distance bound to your actual render distance. This dramatically improves the cloud's visuals with only a negligible performance difference and makes your world feel way more significant than it actually is.
Concurrent Chunk Management Engine it's about making the game better threaded and more scalable in regard to world gen and chunk io performance.
Highlight - This mod changes the visualization of specific blocks in the game that generally would have axis-bound selection boxes to have angled selection boxes to match their model and generally improve the look of the block.
Clumps - Clumps groups XP orbs together into a single entity to reduce lag when there are many in a small area. On top of this, it also makes the player immediately collect the orbs once they touch the player, so you are not stuck with a bunch of orbs in your face.
Krypton - (from Ancient Greek kryptos, "the hidden one") is a Fabric mod that attempts to optimize the Minecraft networking stack. It derives from work done in the Velocity and Tuinity projects.
Lithium - a modern, general-purpose optimization mod for Minecraft which works to improve a number of systems (game physics, mob AI, block ticking, etc) with the goal of not changing any vanilla mechanics.
LazyDFU is an optimization mod for Minecraft that defers unnecessary initialization work so that it is only performed if required. Specifically, it makes the initialization of DataFixerUpper "lazy" - that is, it will not immediately create the rules required to migrate data from older versions of Minecraft to newer versions until it actually needs to do so.
Fastload - Modifies how worlds are loaded to speed up loading times.
ModernFix - All-in-one mod that improves performance, reduces memory usage, and fixes many bugs. Compatible with all your favorite performance mods!
Alternate Current - an efficient and non-locational redstone dust implementation. Its main focus lies in reducing the lag caused by redstone dust, by optimizing the power calculations and reducing the number of shape and block updates emitted. As a side effect of these changes the block update order of redstone dust networks is predictable and intuitive rather than locational and chaotic.
FerriteCore - This mod reduces the memory usage of Minecraft in a few different ways.
Very Many Players - A Fabric mod designed to improve server performance at high playercounts.
FastAnim - Speeds up entity animation calculations!
```

```This modpack works on fabric!```
https://fabricmc.net/

[Site]: https://wlorigin.cf/
[Download]: https://wlorigin.cf/downloadmodpack.html
[Discord]: https://discord.gg/UBaauaN
[Telegram]: https://t.me/wlorigin
[Wiki]: https://wiki.wlorigin.cf

[Our site][Site] - [Download][Download] - [Our Discord][Discord] - [Our telegram channel (RU)][Telegram] - [Wiki][Wiki]

<p align="center">
    <a href="https://github.com/badges/shields/graphs/contributors" alt="Contributors">
        <img src="https://img.shields.io/github/contributors/WasteLand-Dev/modpacksodium" /></a>
    <a href="https://github.com/badges/shields/pulse" alt="Activity">
        <img src="https://img.shields.io/github/commit-activity/m/WasteLand-Dev/modpacksodium" /></a>
    <a href="https://discord.gg/UBaauaN">
        <img src="https://img.shields.io/discord/716326875613364277?logo=discord"
            alt="chat on Discord"></a>
</p>

## Work on:
![Arch](https://img.shields.io/badge/Arch%20Linux-1793D1?logo=arch-linux&logoColor=fff&style=for-the-badge)
![Manjaro](https://img.shields.io/badge/Manjaro-35BF5C?style=for-the-badge&logo=Manjaro&logoColor=white)
![Debian](https://img.shields.io/badge/Debian-D70A53?style=for-the-badge&logo=debian&logoColor=white)
![Linux Mint](https://img.shields.io/badge/Linux%20Mint-87CF3E?style=for-the-badge&logo=Linux%20Mint&logoColor=white)
![Windows](https://img.shields.io/badge/Windows-0078D6?style=for-the-badge&logo=windows&logoColor=white)

```
Совет: установите нашу иконку для установки в лаунчере (launcher_logo.png)
Совет: используйте эти параметры запуска, они помогут добиться большей эффективности :)
Совет: используйте последнюю версию fabric
```
```
Tip: install our icon to install in the launcher (launcher_logo.png)
Tip: use these launch options, they will help you to be more efficient :)
Tip: use the latest version of fabric
```

#### Launch options
```
-Xmx4096M -XX:+UnlockExperimentalVMOptions -XX:+UseG1GC -XX:G1NewSizePercent=30 -XX:G1ReservePercent=20 -XX:MaxGCPauseMillis=200 -XX:G1HeapRegionSize=8M -XX:G1HeapWastePercent=5 -XX:G1MixedGCCountTarget=4 -XX:InitiatingHeapOccupancyPercent=15 -XX:G1MixedGCLiveThresholdPercent=90 -XX:G1RSetUpdatingPauseTimePercent=5 -XX:SurvivorRatio=32 -XX:+PerfDisableSharedMem -XX:MaxTenuringThreshold=1 -XX:+UseDynamicNumberOfGCThreads -XX:+AlwaysPreTouch -XX:+ParallelRefProcEnabled -XX:+UseInterpreter -XX:+RewriteFrequentPairs

### Other mods
- [Make Bubbles Pop](https://modrinth.com/mod/make_bubbles_pop)
```
