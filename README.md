# android_device_huawei_c8817d
TWRP Device configuration for Huawei Honor 4X with MSM8916 (c8817d, aka. che10)

## How to build

1. Download OmniROM Android Pie source code. Follow this guide: https://github.com/omnirom/android
2. Clone the dependency above.
3. Go to OmniROM source root, invoke these commands:
   
   ```
   source build/envsetup.sh
   lunch omni_c8817d-userdebug
   make recoveryimage
   ```
   
4. If success, the built system will print the recovery image's path.

## Dependency

The only dependency is the kernel source from MoKee. Go to OmniROM source root, and clone it:

```
git clone -b mkp https://github.com/MoKee/android_kernel_huawei_msm8916 kernel/huawei/msm8916
```

