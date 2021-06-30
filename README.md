# WeebProjekt

### Sync ###
```bash
repo init -u https://github.com/WeebProjekt/platform_manifest -b reborn
```
```bash
repo sync -c -j$(nproc --all) --force-sync --no-clone-bundle --no-tags
```

### Build ###
```bash
source build/envsetup.sh
lunch weeb_$device-userdebug
make weeb-prod -j$(nproc --all)
```

Credits
-------
 * [**AOSP**](https://android.googlesource.com)
 * [**HentaiOS**](https://github.com/hentaios)
 * [**LineageOS**](https://github.com/LineageOS)
 * [**StormBreakerOSS**](https://github.com/stormbreakeross)
