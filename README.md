<div align="center">

<img src="https://cratedigger.fm/app-icon.png" alt="cratedigger.fm" width="128" height="128" style="border-radius:28px" />

# cratedigger.fm — Android

### Your companion for discovering independent music on Bandcamp.
**Radio for the indie web** — hit play, lean back, and let the crates roll.

<br/>

[![Download latest APK](https://img.shields.io/badge/⬇%20Download%20latest%20APK-3ddc84?style=for-the-badge&logo=android&logoColor=white)](../../releases/latest)
[![Get cratedigger.fm via Obtainium (recommended)](https://img.shields.io/badge/↻%20Get%20via%20Obtainium%20%28recommended%29-119eff?style=for-the-badge&logoColor=white)](#obtainium)

[![Version](https://img.shields.io/badge/version-2.0.5-ff2d78?style=flat-square)](../../releases/latest)
[![Android 8.0+](https://img.shields.io/badge/Android-8.0%2B-3ddc84?style=flat-square&logo=android&logoColor=white)](#-system-requirements)
[![GrapheneOS](https://img.shields.io/badge/GrapheneOS-ready-000000?style=flat-square)](#-system-requirements)
[![Website](https://img.shields.io/badge/web-cratedigger.fm-0f0f11?style=flat-square&logo=googlechrome&logoColor=white)](https://cratedigger.fm)

</div>

---

## 🎧 What is cratedigger.fm?

cratedigger.fm is a music discovery app for anyone who wants to find new artists and releases **outside the mainstream streaming algorithms**. It surfaces curated independent labels, deep cuts, and hidden gems directly from Bandcamp — the platform where artists keep the majority of their revenue.

Think of it as a radio-style discovery engine for the indie web: hit play, lean back, and let the crates roll.

> 📦 This repository hosts the **sideload Android builds** (APKs). Grab the latest release below and install — no Play Store, no Google account required.

## ✨ Features

- **🌍 Discovery modes** — an endless feed of hand-picked releases: shuffle **All Bandcamp** by tag, spin **Curated Labels**, or tune your own **My Radio** from labels and artists you follow.
- **📂 Playlists** — save your favorite tracks into custom playlists that auto-advance release to release.
- **⭐ Favorites** — star tracks and build your personal collection.
- **🔊 Background playback** — keep listening with the screen off or while using other apps; the next track is staged ahead so transitions are gapless.
- **🔒 Lock-screen controls** — play, pause, and skip from your notification shade and lock screen.
- **🛒 Bandcamp integration** — one tap to buy the music you love, directly from the artist.
- **🌙 Dark mode** — easy on the eyes, day or night.

## 📲 Installation

<a id="obtainium"></a>

### ✅ Recommended: install with Obtainium (automatic updates)

[**Obtainium**](https://obtainium.imranr.dev/) is a free, open-source Android app that installs and **keeps other apps up to date directly from their source** — like this GitHub repo — with no app store or Google account involved. Add cratedigger.fm once and Obtainium will notify you (or auto-install) every time a new release lands here, so you never have to re-download an APK by hand.

1. **Install Obtainium** — get it from the [official website](https://obtainium.imranr.dev/) or its [GitHub releases](https://github.com/ImranR98/Obtainium/releases/latest).
2. In Obtainium, tap **Add App** and paste this repo into the *App Source URL* field:
   ```
   https://github.com/rallevondalle/cratedigger-fm-app
   ```
3. Tap **Add**, then **Install**. Obtainium auto-detects the GitHub release, grabs the latest APK, and watches for future updates. ✅

📖 More: [Obtainium website](https://obtainium.imranr.dev/) · [official usage guide & docs](https://github.com/ImranR98/Obtainium#obtainium).

> [!WARNING]
> ## 🛑 Keep Android open — sideloading is under threat
>
> **"Your phone is about to stop being yours."**
>
> From **September 2026**, Google plans to block every Android app whose developer hasn't registered with Google — handing over a government ID, paying fees, and signing agreements — on **all certified devices worldwide, including sideloaded and F-Droid apps**. There's no opt-out, and the proposed sideloading "escape hatch" is buried, slow (a 24-hour wait), and runs through Google Play Services that Google can change or revoke at any time.
>
> **Your freedom to install apps like cratedigger.fm this way is exactly what's at stake.** 71 organizations across 23 countries — including F-Droid, the EFF, the Software Freedom Conservancy, and Nextcloud — have signed an open letter opposing it.
>
> ### 👉 Learn more and take action at **[keepandroidopen.org](https://keepandroidopen.org/)**
> Install F-Droid · contact regulators · sign the petition · share the campaign.

### Manual install (single APK)

1. Download the latest APK from the **[Releases](../../releases/latest)** page.
2. Open the downloaded file on your Android device.
3. If prompted, allow installation from your browser / file manager.
4. Launch **cratedigger.fm** and start digging.

> **First time sideloading?** You'll need to enable *"install unknown apps"* for your browser or file manager. On **GrapheneOS**, the installer works out of the box — no Play Services required.

New versions install cleanly over older ones; your favorites and settings are preserved.

## 📋 System Requirements

| | |
|---|---|
| **OS** | Android 8.0 (API 26) or higher — incl. **GrapheneOS** |
| **Connection** | Internet required for streaming |
| **Storage** | ~20 MB free |

## 🔐 Permissions

| Permission | Why |
|------------|-----|
| **Internet** | Streaming audio and fetching release data |
| **Foreground Service / Media Playback** | Background audio + lock-screen controls |
| **Notifications** | Playback controls in the notification shade |
| **Wake Lock** | Keeps the device awake briefly during track transitions |

## ⚠️ Known Limitations

- **No offline playback** — tracks are streamed, not downloaded.
- **Purchase links open externally** — buying a release redirects to Bandcamp in your browser (this is expected).
- **Screen-off reliability** — on some devices with aggressive battery optimization, background playback may pause after extended periods. If this happens, disable battery optimization for cratedigger.fm in your system settings (Samsung: *Battery → Unrestricted*).

## 🐞 Filing an Issue

Found a bug or have a feature request? Please **[open an issue](../../issues/new/choose)** and include:

1. **App version** — shown in the footer / About screen.
2. **Android version** — e.g. Android 14, Samsung One UI 6, GrapheneOS.
3. **Device model** — e.g. Pixel 8, Samsung Galaxy S23.
4. **What happened** — steps to reproduce.
5. **What you expected** — the expected behavior.
6. **Screenshots / screen recordings** — if applicable, they help a lot.

## 🛡️ Privacy

- No ads.
- No third-party trackers beyond anonymous usage analytics.
- Your Bandcamp credentials are never stored by the app.
- Full [Privacy Policy](https://cratedigger.fm/privacy).

## 💜 Credits

cratedigger.fm is built with love for independent music and the artists who make it. All audio streams and purchase links are served directly by **[Bandcamp](https://bandcamp.com)**.

---

<div align="center">
<sub><em>Made for the heads, not the algorithms.</em></sub>
</div>
