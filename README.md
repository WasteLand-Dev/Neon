# modpacksodium
```v9.2.7.53-Release```
```Stable```

### Changelog:
- Removed incompatibility log message for older eating animations versions.
- Fixed spawn eggs and goat horns cits with no model not appearing correctly.
- Added a way to check the amount of elements in an nbt list by matching the list's count element.
- Fixed parity with the enchantment speed and rotation defaults.
- Updated cloth-config. (Fix possible crash)
- Use YetAnotherConfigLib (Debugify)
- Updated FastLoad
- Updated Presence footsteps:
    Removed Herobrine
    Sounds are now distance attenuated.
    Fixed incorrect subtitles appearing for queaky copper (waxed copper blocks)
    Fixed translation for the auto stance tooltip
    Added the option to play footsteps for players and hostile mobs only
    Updated the primitive map for all vanilla sound types. Fixes mod support in many cases.
    Fixed sound mapping for carpets
    Primitive mappings are now included as part of the block report
    The debug hud will now display matching primitive mappings for the target block in     addition to all the other sounds
    Updated translations: ru_ru, yz_cn, ko_kr
    Updated Kirin to 1.11.1
- finally adding the long-awaited PBR support.
- fixes old hand lighting on SEUS Renewed and similar packs.
- Jar Signing Capabilities have been removed, due to obsolete technology (CraftPresence)
- Added &worldday& as a new sub-argument for &worldinfo&
- Breaking: Biomes now use an identifier based system, similar to how the dimension module works
- This means any custom entries in the Biome Settings will need to migrate to these names
- Fixed a rare issue where initialization can occur while the minecraft session is null
- Fixed an issue where the starting page in Paginated Screens was incorrect, causing various issues
- Backend: Fixed the formatToId param from StringUtils#formatIdentifier being ignored when converting from legacy->modern naming
- Iris hotfix
- YACL improvements

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
