# modpacksodium
```v9.2.7.51-Release```
```Stable```

### Changelog:
- Fixed rare cases of GUI Issues caused by multiple key's being pressed at the same time
- Miscellaneous Tweaks for Linux/MacOS Dependencies (JUnixSocket)
- Add HealthOverlay mod
- Fix cloth config dependency not allowing v8 (CullLessLeaves)
- Rename and validate Mixin class names (Fabric API)
- Add many more transitive access wideners (Fabric API)
- Necessary Fabric API modules are now bundled with the NoChatReports itself
- The mod now features optional integration with Mod Menu and Cloth Config API, allowing for in-game configuration when both are installed on client (NoChatReports)
- Updated Polish translation (NoChatReports)
- Updated Spanish translation (NoChatReports)
- Added Danish translation (NoChatReports)
- Added Slovakian translation (NoChatReports)
- ServerData is now remembered in automatic reconnects. Should fix the bug with Xaero's Worldmap resets
- Lower memory usage of biome cache

```This modpack works on fabric!```
https://fabricmc.net/

[Site]: https://wlorigin.cf/
[Download]: https://wlorigin.cf/downloadmodpack.html
[Discord]: https://discord.gg/UBaauaN
[Telegram]: https://t.me/wlorigin

[Our site][Site] - [Download][Download] - [Our Discord][Discord] - [Our telegram channel (RU)][Telegram]

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
```
