# TWRP Samsung Galaxy A10
![Galaxy A10](https://fdn2.gsmarena.com/vv/bigpic/samsung-galaxy-a10.jpg "Galaxy A10")
# How-to install dependencies
```
# How-to clone source and device tree:
mkdir -p ~/twrp && cd ~/twrp
```
$ repo init --depth=1 -u git://github.com/minimal-manifest-twrp/platform_manifest_twrp_omni.git -b twrp-9.0
```
# Clone a10 repo
```
$ git clone https://github.com/JuananInt/android_device_samsung_a10 -b twrp device/samsung/a10
```
# Sync
$ repo sync --no-repo-verify -c --force-sync --no-clone-bundle --no-tags --optimized-fetch --prune -j`nproc`
```
# How-to build:

cd twrp; export ALLOW_MISSING_DEPENDENCIES=true; . build/envsetup.sh; lunch omni_a10-eng; mka recoveryimage
```
## How to find the image built
```
`cd /out/target/product/a10`
```
see recovery.img
```
# Device Tree for Samsung Galaxy A10 (SM-A105FN)
```
Device Tree Made by JuananInt
```
# Specs
|---------------------------------------------------------------------------------|
|      Component        |          Specification                                  |
|:----------------------|:--------------------------------------------------------|
| Dimensions            | 155.6 x 75.6 x 7.9 mm (6.13 x 2.98 x 0.31 in)           |
| Weight                | 168 g (5.93 oz)                                         |
| Type                  | IPS LCD                                                 |
| Size                  | 6.2 inches, 95.9 cm2 (~81.6% screen-to-body ratio)      |
| Resolution            | 720 x 1520 pixels, 19:9 ratio (~271 ppi density)        |
| OS                    | Android 9.0 (Pie), upgradable to Android 11, One UI 3   |
| Chipset               | Exynos 7884 (14 nm)                                     |
| CPU                   | Octa-core (2x1.6 GHz Cortex-A73 & 6x1.35 GHz Cortex-A53)|
| GPU                   | Mali-G71 MP2                                            |
| Internal              | 32GB 2GB RAM eMMC 5.1                                   |
| USB                   | microUSB 2.0, OTG                                       |
| Battery               | Li-Ion 3400 mAh, non-removable                          |
| Status                | Available. Released 2019, March 19                      |
|---------------------------------------------------------------------------------|
