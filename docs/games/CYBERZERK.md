# 💥 Cyberzerk for Android — Commodore Amiga Top-Down Shooter APK

[← Game collection](../../README.md) · [APK installation](../INSTALLATION.md) · [GitHub Releases](https://github.com/Andiweli/Amiga-Android-GameCollection/releases)

**Cyberzerk (1993)** is a classic **Commodore Amiga 500 top-down science-fiction action shooter**, originally developed by **Century Interactive** and published by **Boeder Software**. This unofficial Android adaptation provides a standalone APK, tailored controller mapping, touch controls and a dedicated Amiga runtime.

## 🕹️ What is included in the Android app?

- Standalone game icon, menu and emulator runtime
- Android-compatible gamepad and remappable controls
- Local two-player controller support (with a compatible game image)
- Touchscreen overlay, save states and resume option
- Fullscreen scaling, smoothing, CRT scanlines and Amiga audio options
- Optional gameplay assists for energy, time, bombs and missiles

**Original game data is not included.**

## 🎮 Default gamepad mapping

| Input | Action |
| --- | --- |
| Left analog stick / D-pad | Move |
| **A** or **R2** | Fire (hold to fire a missile) |
| **B** or **L1** | Smart bomb |
| **X** or **R1** | Autofire |
| **Y** | Toggle music |
| **Start** | Pause |
| **Select (hold ~1 second)** | Open Android app menu |
| **R3** | Abort / Escape |

Controller assignments can be customized in the app. A second controller can be used for the second player where supported by the game data.

## 💿 Compatible Cyberzerk ADF disk image

The supplied Android code imports **one** standard **901,120-byte (880 KiB) AmigaDOS ADF** and checks for a supported disk layout containing the `CyberZerk` program and expected numbered data files.

**Important:** The commercial Amiga release is commonly catalogued as a **two-disk game**. Do not assume any retail disk or arbitrary ADF repack will be accepted by this game's Android importer. The supported Android layout is specific; it is not a universal Cyberzerk disk loader.

No separate Kickstart ROM is needed. You must provide your own lawfully obtained compatible disk image.

## 📱 Android compatibility

The example project targets **Android 7.0+** with **64-bit ARM or x86_64** APK binaries and a landscape layout. Actual compatibility is device-dependent; there is no guarantee that every Android device has been tested.

## 🔗 Downloads and related guides

- [Download official APK releases](https://github.com/Andiweli/Amiga-Android-GameCollection/releases) (when published)
- [Install Amiga games on Android](../INSTALLATION.md)
- [Jim Power for Android](JIM_POWER.md)
- [Zeewolf for Android](ZEEWOLF.md)

## ⚖️ Rights notice

Cyberzerk, its original game assets and associated artwork remain subject to their respective rights holders. This is an **unofficial fan-made Android adaptation**, not a licensed re-release of the original game.
