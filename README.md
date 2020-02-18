# ion #

### Sync ###
```bash

# Initialize local repository
repo init -u https://github.com/Android-Raphael -b ionzer-ten

# Sync
repo sync -c -j$(nproc --all) --force-sync --no-clone-bundle --no-tags

```

### Build ###
```bash

# Set-up environment
$ . build/envsetup.sh

# Choose a target
$ lunch ion_$device-userdebug

# Build the code
$ mka bacon -j$(nproc --all)

```
