# 🌸 ProjectSakura GSI — Feels Like Spring 🌸

> *Blossom into a new Android experience. Light, fresh, and alive.*

[![Build Status](https://github.com/Doze-off/ProjectSakura_gsi/actions/workflows/build.yml/badge.svg)](https://github.com/Doze-off/ProjectSakura_gsi/actions/workflows/build.yml)
[![Android 16](https://img.shields.io/badge/Android-16-green.svg)](https://developer.android.com/about/versions)
[![Project Treble](https://img.shields.io/badge/Project-Treble-blue.svg)](https://android-developers.googleblog.com/2017/05/here-comes-treble-modular-base-for.html)

---

## 🌷 About

**ProjectSakura GSI** is a Generic System Image based on [ProjectSakura](https://github.com/ProjectSakura), bringing a clean, bloat-free Android 16 experience to any [Project Treble](https://android-developers.googleblog.com/2017/05/here-comes-treble-modular-base-for.html) compatible device.

The **Feels Like Spring** update brings a refreshed, lively aesthetic — think cherry blossoms in full bloom: smooth, vibrant, and full of life.

---

## 🌸 What's New — Feels Like Spring

- 🌼 **Spring-themed wallpapers** — Fresh floral and nature-inspired artwork
- 🍃 **Refreshed UI accents** — Soft pastel colour palette inspired by cherry blossoms
- 🌱 **Android 16 base** — Built on the latest Android platform for maximum compatibility
- 🦋 **Performance improvements** — Lighter, faster, and smoother than ever
- 🌤️ **Updated system apps** — Latest security patches and app updates
- 🌺 **Sakura animations** — Subtle spring-inspired motion effects throughout the UI

---

## 📦 Downloads

Check the [**Releases**](https://github.com/Doze-off/ProjectSakura_gsi/releases) page for the latest builds.

| Variant      | Architecture | Description                     |
|--------------|--------------|---------------------------------|
| `arm64`      | ARM64        | For most modern 64-bit devices  |
| `arm64-ab`   | ARM64 A/B    | For A/B partition devices       |

---

## 📋 Requirements

- **Project Treble** compatible device
- **Unlocked bootloader**
- A custom recovery (e.g. TWRP) or `fastboot` access
- At least **3 GB RAM** recommended
- **Android 9+** firmware on the device (for Treble support)

---

## 🔧 Installation

1. Download the latest GSI image from the [Releases](https://github.com/Doze-off/ProjectSakura_gsi/releases) page.
2. Boot into fastboot mode:
   ```bash
   adb reboot fastboot
   ```
3. Flash the GSI:
   ```bash
   fastboot flash system ProjectSakura-<version>-arm64.img
   ```
4. Wipe userdata (recommended for clean install):
   ```bash
   fastboot -w
   ```
5. Reboot and enjoy the blossoms! 🌸

> **Note:** Installation steps may vary by device. Always back up your data before flashing.

---

## 🛠️ Building from Source

This repository uses **GitHub Actions** to build the GSI automatically. To trigger a build:

1. Fork this repository.
2. Go to **Actions** → **Build ProjectSakura GSI**.
3. Click **Run workflow** and select your desired options.

To build locally, clone the repository and run:

```bash
./build.sh
```

---

## 🐛 Bug Reports

Found an issue? Please open a [GitHub Issue](https://github.com/Doze-off/ProjectSakura_gsi/issues) with:
- Device name and model
- Firmware version
- Description of the issue
- Logcat (if available)

---

## 🤝 Contributing

Pull requests are welcome! For major changes, please open an issue first to discuss what you would like to change.

---

## 📜 Credits

- [ProjectSakura](https://github.com/ProjectSakura) — The upstream ROM source
- [phhusson](https://github.com/phhusson) — Treble patches and GSI know-how
- All contributors and testers 🌸

---

## 📄 License

This project is licensed under the [Apache License 2.0](LICENSE).

---

<p align="center">Made with 🌸 and lots of ☕</p>