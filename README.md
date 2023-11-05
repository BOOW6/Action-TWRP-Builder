# Use Github Action to compile Recovery

- Support TWRP, SHRP compilation and production

- OrangeFox is [here](https://github.com/azwhikaru/Action-OFRP-Builder)

## Parameter Description

| Name | Description | Example |
| ------------ | -------------------- | ------------ |
| `MANIFEST_URL` | Source address | https://github.com/minimal-manifest-twrp/platform_manifest_twrp_aosp.git |
| `MANIFEST_BRANCH` | Source branch | twrp-12.1, twrp-11 |
| `DEVICE_TREE_URL` | Device address | https://github.com/TeamWin/android_device_asus_I003D |
| `DEVICE_TREE_BRANCH` | Device branch | android-12.1, android-11 |
| `DEVICE_PATH` | Device location | device/asus/I003D |
| `COMMON_TREE_URL` | Common tree address | https://github.com/TeamWin/android_device_asus_sm8250-common |
| `COMMON_PATH` | Common tree location | device/asus/sm8250-common |
| `DEVICE_NAME` | Model name | I003D |
| `MAKEFILE_NAME` | Makefile name | twrp_I003D |
| `BUILD_TARGET` | Build Target Partition (boot/recovery/vendorboot) | recovery, boot, vendorboot |

-----

## Compilation results
Can be downloaded at [Release](../../releases)

-----
## Remark

- TeamWin Recovery Project: https://github.com/minimal-manifest-twrp/platform_manifest_twrp_aosp
- SKYHAWK Recovery Project: https://github.com/SHRP/manifest
- OrangeFox Recovery Project: https://gitlab.com/OrangeFox/Manifest
