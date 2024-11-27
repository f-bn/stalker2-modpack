### General informations

This repository contains a custom merge modpack for S.T.A.L.K.E.R. 2: Heart of Chornobyl in order to improve performance and gameplay experience waiting for official patches.

#### Mods used

- [Optimized Tweaks S.2 1.67 (Base variant)](https://www.nexusmods.com/stalker2heartofchornobyl/mods/7)
- [ALife Extended Alive 1.2 x Axxii's Stealth 1.7](https://www.nexusmods.com/stalker2heartofchornobyl/mods/273)
- [Even Longer Days 0.1 (4h variant)](https://www.nexusmods.com/stalker2heartofchornobyl/mods/47)
- [No (or reduced) weight for ammo nades meds and food 1.0 (50% variant)](https://www.nexusmods.com/stalker2heartofchornobyl/mods/45)

#### How to build the modpack

Firstly, you need to [repack](https://github.com/trumank/repak) tool in order to pack and unpack Unreal Engine PAK files.

Unpack mods:

```
repak.exe unpack .\even_longer_days_4h.pak -o temp/
```

Generate modpack from "merge" folder:

```
repak.exe pack modpack/ custom_modpack_27112024_1051_P.pak
```

*TODO*

### References

- repack: https://github.com/trumank/repak
