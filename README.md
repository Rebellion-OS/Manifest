![RebellionOS](https://github.com/betallion-os/manifest/raw/pie/logo.png)

# RebellionOS    [![Download RebellionOS](https://img.shields.io/sourceforge/dt/rebellionos.svg)](https://sourceforge.net/projects/rebellionos/files/latest/download)

### Sync ###


#### Initialize local repository
```
repo init -u https://github.com/Rebellion-OS/manifest -b pie
```

#### Sync
```
repo sync -c -f --force-sync --no-clone -jx
```

### Build ###

#### Set up environment
```
$ . build/envsetup.sh
```

#### Choose a target
```
$ lunch rebellion_$device-userdebug
```

#### Build the code
```
$ mka carthage -jX
```

### Credits ###

- PixelExperience (AOSP Base Done by @jhenique and team)
- LegionOS
- RevengeOS
- COSP
- LineageOS
- AICP
- AOKP
- BootleggersROM
- AospExtended
- GZOSP
- AOSZP
- Havoc OS
- Arrow OS
- AOSCP
- DescendantOS
- MSM-Xtended
- NitogenOS
- CarbonROM
- ValidusOS
