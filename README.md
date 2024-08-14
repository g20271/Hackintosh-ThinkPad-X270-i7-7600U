# 🍏 Hackintosh Lenovo ThinkPad X270 (i7-7600U)

Welcome to the Hackintosh build guide for the **Lenovo ThinkPad X270** powered by an **Intel i7-7600U**.  
Not compatible like 6th gen cpu.  
This repository is too many bugs and untested functions now.  

## 📋 System Overview

- **Model:** Lenovo ThinkPad X270
- **Processor:** Intel Core i7-7600U
- **macOS Version:** Monterey
- **Bootloader:** OpenCore
- **BIOS Version:** R0IET69W (1.47)

---

## ✅ What's Working

| Component            | Status        | Details                        |
|----------------------|---------------|--------------------------------|
| **CPU**              | ✔️ Working    | Fully functional with power management |
| **Graphics (Intel HD 620)** | ✔️ Working | smooth performance |
| **Wi-Fi** | ✔️ Working |  |
| **USB Ports**         | ✔️ Working    | All USB ports functional |
| **Trackpad & Keyboard**| ✔️ Working   | Multitouch gestures supported but when ctrl or meta, alt key press, cursor doesn't move |
| **Internal Display** | ✔️ Working |  |
| **Sleep/Wake**       | ✔️ Working |  |
---

## ⚠️ Known Issues

| Component            | Status        | Details                        |
|----------------------|---------------|--------------------------------|
| **External Display(HDMI)** | ⚠️ Partially Working | ok 1920x1080, 4k output doesn't work |
| **Intel Bluetooth**   | ❌ Not Working | Requires replacement or a USB dongle |
| **Audio (ALC Audio)** | ✔️ Working    | Speaker is good sound, but headphone jack is poor sound quality. |


## ❔ Untested
| Component            | Status        | Details                        |
|----------------------|---------------|--------------------------------|
| **Ethernet**          | ❔ Untested    |  |
| **Battery Management**| ✔️ Working    | See battery status in macOS  |
| **Internal SD Card Reader** | ❌ Not Working | Currently not supported |
| **Fingerprint Sensor**| ❌ Not Working | Not functional in macOS |

# Acknowledgements
- [thinkpad-x1-carbon-5th-gen-hackintosh](https://github.com/mcjimsr/thinkpad-x1-carbon-5th-gen-hackintosh)