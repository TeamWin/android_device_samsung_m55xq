# Android device tree for samsung SM-M556B (m55xq)

## Contributors
 - [Fernanda Silva](https://github.com/DevzPlayer) - Tester
 - [ErickM55](https://github.com/Samy-Snap) - Tester
 - [Pratik](https://github.com/console-ramoops) - Tester
 - [Subham Nayak](https://github.com/Ma445-cell) - Tester
 - [cd-crypton](https://github.com/cd-crypton) - Thanks to Carlo for creating the custom kernel

# How to Build
## Initialise repo
    repo init -u https://github.com/SavedByLight/platform_manifest_twrp_aosp.git -b twrp-14.1
## Repo Sync
    repo sync
## Clone M55 Tree
    git clone https://github.com/SavedByLight/android_device_samsung_m55xq -b android-14.1 device/samsung/m55xq
## Configure the m55xq
    export ALLOW_MISSING_DEPENDENCIES=true; . build/envsetup.sh; lunch twrp_m55xq-ap2a-eng;
## Repopick (my twrp-14 manifest only)
    repopick 7922
## Make Recovery Image
    mka recoveryimage

# Support
 - [Telegram](https://t.me/M55_5g)

# Known issues
 - USB-OTG is tempermental
 - Data cant be mounted, this is a known issue with samsung
```
#
# Copyright (C) 2024 The Android Open Source Project
# Copyright (C) 2024 SebaUbuntu's TWRP device tree generator
#
# SPDX-License-Identifier: Apache-2.0
#
```
