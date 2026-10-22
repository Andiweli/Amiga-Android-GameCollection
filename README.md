# 🕹️ Amiga Games for Android

### Commodore Amiga APK Collection

**Play classic Commodore Amiga 500 games on Android with standalone APKs, Bluetooth gamepad support, touchscreen controls, save states and your own ADF disk images.**

**Amiga Android GameCollection** brings selected retro Commodore Amiga games to Android in **individual, game-specific apps**. Each APK has its own launcher icon, Android settings, input mapping and built-in lightweight Amiga emulation runtime. No separate general-purpose emulator setup is needed.

> 📦 **APK releases only.** This repository shares compiled Android applications and documentation, **not the source code or original game disks**. To play, import your own legally obtained, compatible ADF image(s). No separate Kickstart ROM file is required.

## 🎮 Available Amiga games

| Title | Amiga year | Genre | ADF files required |
| --- | --- | --- | --- |
| **Cyberzerk** | 1993 | Top-down science-fiction shooter, 1–2 players | 1 specially supported AmigaDOS ADF |
| **Jim Power in Mutant Planet** | 1992 | Run-and-gun / platform game | 2 compatible ADF disks |
| **Zeewolf** | 1994 | 3D helicopter combat / action | 1 compatible ADF |

## ✨ Features

- 📱 **Dedicated Android APK and launcher icon for every game**
- 🎮 **Gamepad, Bluetooth controller and remappable button support**
- 👆 **Touchscreen overlay**, with settings for its visibility
- 💾 **Save/load states** and optional resume support
- 🖥️ **Display customization** with scaling, smoothing and CRT-style scanlines
- 🔊 **Audio options** including stereo separation and mono
- 💿 **ADF disk import** and optional accelerated disk loading
- ⚙️ **Game-specific options:** optional cheats and, for Zeewolf, multiple speed presets
- 🌍 **Multilingual menus:** English, German, Spanish, French and Italian
- 🚫 **No separate Kickstart ROM or standalone emulator installation needed**

Available settings may differ from one game to another.

## 📲 Installation — how to play Amiga games on Android

1. Open the [Releases page](https://github.com/Andiweli/Amiga-Android-GameCollection/releases) and download the APK for the game you want.
2. Install the APK on an Android device. If prompted, allow installation from the app that opened the file.
3. Launch the newly installed game using its individual Android icon.
4. Import **your own compatible, uncompressed 880 KB Amiga ADF file(s)** using the game's file picker.
5. Connect a gamepad or use the touchscreen controls and start playing.

**ADF compatibility matters:** Modified and differently packaged disk images may not work.

## ⚙️ Android requirements

| Requirement | Configuration |
| --- | --- |
| **Minimum OS** | Android 7.0 (API 24) |
| **CPU / APK ABI** | 64-bit `arm64-v8a` and `x86_64` |
| **Screen** | Landscape |
| **Input** | Touchscreen or Android-compatible controller |
| **Game data** | User-supplied compatible 880 KB `.adf` file(s) |
| **Android TV** | TV launcher integration is configured; individual-device compatibility varies |

These are **project build settings**, not a guarantee of testing or full functionality on every phone, handheld, tablet, TV box or Android release. 32-bit-only Android devices are not supported by these builds.

## ❓ FAQ

**Are these native Android ports?**  
Not strictly. Each dedicated app runs the original Amiga game through an integrated, game-specific emulation runtime and adds native Android menus and controls.

**Does the APK include the game itself?**  
No. You must import your own legally obtained ADF disks; copyrighted game data is not hosted or distributed here.

**Do I need an Amiga Kickstart ROM (BIOS)?**  
No. The supported runtimes require no separate Kickstart file.

**Can I use a Bluetooth controller?**  
Yes, provided Android recognizes the controller. The apps include configurable button mappings.

**Can I use the touchscreen instead?**  
Yes. Each app includes configurable on-screen controls.

**Is the project open source?**  
No. Only compiled APKs and documentation are published at present.

## ⚖️ Copyright and licensing

These are **unofficial, independent fan-made Android adaptations**. They are not endorsed by the games' original developers, publishers or rights holders. Original **Cyberzerk**, **Jim Power in Mutant Planet** and **Zeewolf** program code, artwork, music, sound, graphic assets and trademarks remain subject to their respective owners' rights.

Project-owned components are distributed under the **binary-only freeware terms** in [LICENSE.md](LICENSE.md); this is **not an open-source license**. Independent third-party components, including **Musashi** and **SoftFloat**, have separate rights and conditions documented in [THIRD_PARTY_NOTICES.md](THIRD_PARTY_NOTICES.md). No rights to original Amiga game disk images are granted. Game-derived launcher artwork may also be subject to third-party rights.

---

Created and maintained by **[Andiweli](https://github.com/Andiweli)** — preserving the feel of classic Commodore Amiga gaming on modern Android devices.
