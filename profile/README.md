# lumia-msm8974

Android (LineageOS) for the Nokia Lumia phones built on the Qualcomm MSM8974 (Snapdragon 800).
These phones have no Android bootloader: Android starts from the Windows Phone boot manager
through BootShim and lk1st.

## Devices

| Phone | Codename | Status |
|---|---|---|
| Nokia Lumia 1520 | `bandit` | LineageOS 18.1 bring-up: builds, boot in progress |
| Nokia Lumia 930 | `martini` | coming soon |

## Repositories

| Repository | What it is |
|---|---|
| [android_device_nokia_bandit](https://github.com/lumia-msm8974/android_device_nokia_bandit) | Lumia 1520 device tree, LineageOS 18.1; ROM and TWRP releases |
| [android_vendor_nokia_bandit](https://github.com/lumia-msm8974/android_vendor_nokia_bandit) | Lumia 1520 vendor files |
| [android_kernel_nokia_msm8974](https://github.com/lumia-msm8974/android_kernel_nokia_msm8974) | Kernel 3.4 for the MSM8974 Lumias, based on LineageOS `android_kernel_oppo_msm8974` |
| [lk2nd](https://github.com/lumia-msm8974/lk2nd) | lk2nd with lk1st support for the Lumias (branch `bandit`) |
| [bandit-manifests](https://github.com/lumia-msm8974/bandit-manifests) | Local manifests to build Android for the Lumia 1520 |
| [bandit-installer](https://github.com/lumia-msm8974/bandit-installer) | Installer for Windows and Linux: partitions, boot chain, ROM |

## Credits

This work stands on other people's work; each repository lists what it uses in detail.

- [LineageOS](https://github.com/LineageOS): the OnePlus One / Oppo MSM8974 device trees and kernel this port starts from.
- KorelisLabs, [lumia-1520-mainline](https://github.com/KorelisLabs/lumia-1520-mainline): boot chain, hardware map and TrustZone findings for the 1520.
- Markynose (Mark Buchok), [lumia930-linux](https://github.com/Markynose/lumia930-linux): SMP through the stock UEFI parking mailboxes on the MSM8974 Lumias.
- imbushuo (Bingxing Wang), [boot-shim](https://github.com/imbushuo/boot-shim).
- msm8916-mainline, [lk2nd](https://github.com/msm8916-mainline/lk2nd).
- René Lergner (HeathCliff), [WPinternals](https://github.com/ReneLergner/WPinternals).
- TeamWin, [TWRP](https://twrp.me).
- [Android4Lumia950](https://github.com/Android4Lumia950) (djokcho, EpicLPer, j0sh1x, sonic011gamer and the community): the Lumia 950/950 XL Android port and installer this project follows.
