# 📲 Install Amiga Games on Android — APK & ADF Setup Guide

[← Back to Amiga Android GameCollection](../README.md)

This guide explains how to install standalone **Commodore Amiga game APKs** on Android, import your own **ADF (Amiga Disk File)** images and configure controllers.

## ⬇️ 1. Download the correct game APK

Visit the [GitHub Releases page](https://github.com/Andiweli/Amiga-Android-GameCollection/releases) and choose the APK for **Cyberzerk**, **Jim Power in Mutant Planet** or **Zeewolf** when available.

These apps install separately. They already contain the game-specific Amiga emulator runtime, but **not the copyrighted game disks**.

## 📱 2. Install the APK

1. Transfer or download the selected `.apk` to your device.
2. Open the APK with Android's file manager.
3. If Android requests permission to install unknown apps from the current source, review and approve that one-time permission.
4. Complete installation and start the app using its own game icon.

**Minimum build requirement:** Android 7.0 (API 24), on an **ARM64** (`arm64-v8a`) or **x86_64** Android device. These are build settings, not a guarantee of compatibility with every Android version or device.

## 💿 3. Import a compatible ADF file

On first launch, the app opens an import screen. Use Android's file picker to select **your own legally obtained Amiga disk image**.

| Game | Import requirement |
| --- | --- |
| **Cyberzerk** | **One** supported 901,120-byte AmigaDOS ADF containing the expected `CyberZerk` program and associated files |
| **Jim Power in Mutant Planet** | **Two** supported 901,120-byte ADFs, selected in the correct disk order |
| **Zeewolf** | **One** supported 901,120-byte AmigaDOS ADF with the expected game data |

**901,120 bytes = standard uncompressed 880 KiB Amiga ADF.** `.zip`, `.lha`, `.adf.gz`, WHDLoad packages, IPF files and other formats cannot simply be substituted for an expected standard ADF.

**Cyberzerk compatibility note:** The original commercial game was also released on two disks. This Android runtime supports a particular **single-disk AmigaDOS layout**, not every original or repacked disk variant. It validates the expected program/data file names.

The apps import game data into Android's private application storage. Do not redistribute copyrighted game files.

## 🎮 4. Configure gamepad and touch controls

- Connect a Bluetooth or USB gamepad supported by Android.
- Movement normally uses the D-pad or left analog stick.
- Open the game menu to adjust controller button mappings, sound, display, and touch-overlay visibility.
- The **Select** button is assigned to **hold to open the app menu** in the supplied default mappings; default hold duration is approximately **one second**.
- Each game has a different default button layout; see its guide.

## 💾 5. Save and resume

The apps support **save states**, **load states** and optional automatic resume, in addition to any native game behavior. Save-state data and imported ADF images are stored in app-specific storage. Uninstalling the app or clearing its storage may erase them.

## 🛠️ Troubleshooting

**“This APK cannot be installed.”**  
Check the device's OS and CPU architecture. These builds are 64-bit-only and need Android 7.0 or newer. An installed build signed with a different certificate may need to be removed first; uninstalling can delete its data.

**“Invalid disk” or an ADF import error.**  
Verify the file is an uncompressed **901,120-byte** ADF for the **correct game** and, where applicable, the correct supported disk layout. A valid ADF for an unrelated release is not necessarily compatible.

**Gamepad does not respond.**  
Confirm that Android recognizes the controller and check the game's controller-mapping menu. Different gamepads may report different key codes.

**Screen scaling or audio sounds wrong.**  
Try the game's display and stereo settings. Zeewolf also offers selectable performance presets.

**Can I download Amiga Kickstart ROMs here?**  
No, and they are not required for these supported runtimes.

## 📚 Game manuals

- [💥 Cyberzerk on Android](games/CYBERZERK.md)
- [🚀 Jim Power in Mutant Planet on Android](games/JIM_POWER.md)
- [🚁 Zeewolf on Android](games/ZEEWOLF.md)

## ⚖️ Copyright

These apps do not grant any right to commercial Commodore Amiga game files. Obtain and use your own ADF images lawfully. See the repository's [license terms](../LICENSE.md) and [third-party notices](../THIRD_PARTY_NOTICES.md).
