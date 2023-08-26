### Corvus ROM ###

![CorvusROM](https://raw.githubusercontent.com/Astile97/extras/master/corvus/cover.PNG)
<p align="center">

[![Sourceforge](https://img.shields.io/sourceforge/dm/corvus-os?color=1d91f0&label=RavenLair%20downloads&style=for-the-badge&labelColor=121217&logo=github)](https://corvus-rom.github.io/)
</p>

# Initialize Local Repository #
```bash
repo init -u https://github.com/CorvusOS-Revived/android_manifest.git -b 11 --git-lfs
```

# Or Initialize Shallow Clone #
```bash
repo init --depth=1 -u https://github.com/CorvusOS-Revived/android_manifest.git -b 11 --git-lfs
```

# Syncing Repository # 
```bash
repo sync -j$(nproc --all) --force-sync --no-tags --no-clone-bundle
```

# Building Environment #
```bash   
# Set up environment
. build/envsetup.sh

# Choose a target
lunch corvus_device-userdebug

# Build the ROM
mka corvus
```
 Credits:
 =======

 * [**DirtyUnicorns**](https://github.com/DirtyUnicorns)
 * [**PixelExperience**](https://github.com/PixelExperience)
 * [**HavocOS**](https://github.com/Havoc-OS)
 * [**LineageOS**](https://github.com/LineageOS/)
