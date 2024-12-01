### General informations

This repository contains a custom merge modpack for S.T.A.L.K.E.R. 2: Heart of Chornobyl in order to improve performance and gameplay experience waiting for official patches.

#### Mods used

- [Optimized Tweaks S.2 2.04 (Base variant)](https://www.nexusmods.com/stalker2heartofchornobyl/mods/7)
- [ALife Extended Alive 1.3 x Axxii's Stealth 1.7](https://www.nexusmods.com/stalker2heartofchornobyl/mods/273)
- [Even Longer Days 0.1 (4h variant)](https://www.nexusmods.com/stalker2heartofchornobyl/mods/47)
- [No (or reduced) weight for ammo nades meds and food 1.0 (50% variant)](https://www.nexusmods.com/stalker2heartofchornobyl/mods/45)
- [Reasonable Weapon Degradation by VAXIS](https://www.nexusmods.com/stalker2heartofchornobyl/mods/33)

#### How to build the modpack

Firstly, you need to [repack](https://github.com/trumank/repak) tool in order to pack and unpack Unreal Engine PAK files.

Once the tool is downloaded and installed, you can generate the modpack from the "modpack" folder containing merged mods:

```powershell
repak.exe pack modpack/ custom_modpack_27112024_1051_P.pak
```

Then, create a `~mods` directory in the following game directory (**the tilde character in folder name is mandatory**): 
  - ***Steam*** - `path\to\SteamLibrary\steamapps\common\S.T.A.L.K.E.R. 2 Heart of Chornobyl\Stalker2\Content\Paks`

Finally, copy the generated PAK file in the `~mods` directory created above:

```powershell
cp "path\to\custom_modpack_27112024_1051_P.pak" `
  "path\to\SteamLibrary\steamapps\common\S.T.A.L.K.E.R. 2 Heart of Chornobyl\Stalker2\Content\Paks\~mods"
```

### References

- repack: https://github.com/trumank/repak
