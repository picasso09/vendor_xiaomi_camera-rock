# proprietary_vendor_xiaomi_camera

Prebuilt stock MIUI Camera to include in custom ROM builds.

Extracted from rock MIUI package (refer proprietary-files.txt for version).

### Supported devices
* Redmi 11 Prime 4G / POCO M5 (rock)

### How to use?

1. Clone this repo to `vendor/xiaomi/camera`

2. Inherit it from `device.mk` in device tree:

```
# Camera
$(call inherit-product-if-exists, vendor/xiaomi/camera/miuicamera.mk)
```
