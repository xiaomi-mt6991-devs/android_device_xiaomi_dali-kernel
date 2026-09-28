Copyright (C) 2025 The LineageOS Project

# Prebuilt kernel for the Redmi K80 Ultra (dali)

Prebuilt kernel artifacts for the Redmi K80 Ultra (codename _"dali"_, MT6991 /
Dimensity 9400+), extracted from stock OS3.0.305.0.WONCNXM firmware.

This repository is based on the
[dash-kernel reference tree](https://github.com/Kyuuju2/android_device_xiaomi_dash-kernel/tree/m/16.0)
(Redmi Turbo 5 Max / POCO X8 Pro Max, MT6991) and follows the same layout.

## Contents

- `Image.lz4` — kernel image extracted from `boot.img`
- `dtb/mt6991.dtb` — device tree blob from `vendor_boot`
- `dtbo.img` — stock device tree overlay image
- `vendor_ramdisk/` — kernel modules from stock `vendor_boot`
- `vendor_dlkm/` — kernel modules from `vendor_dlkm` image
- `system_dlkm/` — kernel modules from `system_dlkm` image
- `modules.load.{vendor,system,vendor_ramdisk,recovery}` — module load lists
- `kernel-headers/` — UAPI headers (kernel 6.6.56)

Kernel source: [`MiCode/Xiaomi_Kernel_OpenSource`](https://github.com/MiCode/Xiaomi_Kernel_OpenSource)
branch `bsp-dali-v-oss`.
