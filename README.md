![RebellionOS](https://github.com/betallionos/manifest/raw/pie/logo.png)

# RebellionOS #

### Sync ###

```bash

# Initialize local repository
repo init -u https://github.com/RebellionOS/manifest -b pie

# Sync
repo sync -c -f --force-sync --no-clone -jx
```

### Build ###

```bash

# Set up environment
$ . build/envsetup.sh

# Choose a target
$ lunch rebellion_$device-userdebug

# Build the code
$ mka carthage -jX
