Unknown Open Source Project
=======
```bash

# Initialize local repository
repo init -u https://github.com/UOSP/android_manifest -b Eleven

# Sync
repo sync -c -j$(nproc --all) --force-sync --no-clone-bundle --no-tags
```

