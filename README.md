# EldenRingMods
A collection of mods I've made for Elden Ring. For use with [Elden Mod Loader](https://www.nexusmods.com/eldenring/mods/117).

## Mods:
- [Unlock the framerate](https://www.nexusmods.com/eldenring/mods/216)
- [Remove chromatic aberration](https://www.nexusmods.com/eldenring/mods/179)
- [Remove vignette](https://www.nexusmods.com/eldenring/mods/177)
- [Remove black bars](https://www.nexusmods.com/eldenring/mods/175)
- [Fix the camera](https://www.nexusmods.com/eldenring/mods/118)
- [Pause the game](https://www.nexusmods.com/eldenring/mods/43)
- [Adjust the FoV](https://www.nexusmods.com/eldenring/mods/325)
- [Increase animation distance](https://www.nexusmods.com/eldenring/mods/349)
- [Disable rune loss](https://www.nexusmods.com/eldenring/mods/376)
- [Skip the intro](https://www.nexusmods.com/eldenring/mods/421)

## ModEngine2 Installation

I highly recommend this setup so you don't have to install/uninstall mod loader to play co-op or solo/online.

Drop what you want to use into your ModEngine2 folder. Do not place it under the mod folder inside.

Edit config_eldenring.toml, for example I use:

```toml
external_dlls = [
    "ersc.dll",
    "AdjustTheFov.dll",
    "CameraFix.dll",
    "IncreaseAnimationDistance.dll",
    "RemoveChromaticAberration.dll",
    "RemoveVignette.dll",
    "UltrawideFix.dll",
    "UnlockTheFps.dll"
]
```

These paths are relative to ModEngine2, and if you had these in the mod folder they would be i.e. mod/AdjustTheFov.dll.  
I didn't opt to put things in mod/ because some dll mods seem to have hardcoded expectations of where they're running from.

Start `launchmod_eldenring.bat`!

## Credits
- Thanks to **uberhalit** for his [EldenRingFpsUnlockAndMore](https://github.com/uberhalit/EldenRingFpsUnlockAndMore) code.
- Thanks to **gurrgur** for his compilation of hex edits in this repo: [er-patcher](https://github.com/gurrgur/er-patcher).
- Thanks to **iArtorias** for his [new pausing technique](https://github.com/iArtorias/elden_pause).
- Thanks to **giniyat202** for his [Linux fix](https://github.com/techiew/EldenRingMods/pull/9).
- Thanks to **techiew** for making these mods.
- Thanks to **Nordgaren** for figuring out that adding a startup delay makes these mods work.

I've only compiled these and made minor changes to save people time!
