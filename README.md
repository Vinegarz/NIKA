<div align="center">

<br />

<img src="Logo.png" alt="NIKA warrior emblem" width="190" />

# NIKA

### A polished, open-source YouTube Music client for Android, web, TV, Wear OS, and browser extensions.

[![Latest release](https://img.shields.io/github/v/release/Vinegarz/NIKA?style=for-the-badge&labelColor=0d1117)](https://github.com/Vinegarz/NIKA/releases)
[![Build APK](https://img.shields.io/github/actions/workflow/status/Vinegarz/NIKA/build-nika-apk.yml?branch=rebrand%2Fnika-android&style=for-the-badge&label=APK%20build&labelColor=0d1117)](https://github.com/Vinegarz/NIKA/actions/workflows/build-nika-apk.yml)
[![License](https://img.shields.io/github/license/Vinegarz/NIKA?style=for-the-badge&labelColor=0d1117)](https://github.com/Vinegarz/NIKA/blob/rebrand/nika-android/LICENSE)

[Download](#download) · [Features](#features) · [Web app](#web-app) · [Contributing](#contributing) · [License](#license)

</div>

> [!NOTE]
> NIKA is an independent community project and is not affiliated with, endorsed by, or connected to YouTube or Google.

<div align="center">
<img src="Banner.png" alt="NIKA banner" width="100%" />
</div>

## Features

- Search, browse, and play music from YouTube Music.
- Background playback, media notifications, queue, playlists, and library.
- Lyrics from multiple providers with word-synced playback.
- Offline downloads and local music library support.
- Audio effects, equalizer integration, playback speed, crossfade, and skip silence.
- Listen Together, Spotify, Discord Rich Presence, Last.fm, and ListenBrainz integrations.
- Android Auto, widgets, Android TV, Wear OS, and browser extension support where available.
- Artwork-driven theming, animated album canvas, and Automix features.

## Download

### Android

Download the latest installable APK from the [NIKA Releases page](https://github.com/Vinegarz/NIKA/releases). Debug APK artifacts for testing are also available from [GitHub Actions](https://github.com/Vinegarz/NIKA/actions/workflows/build-nika-apk.yml).

The Android application ID is `com.nika.music`. Android 8.0/API 26 or newer is supported.

### Web app

Run the local web player from the repository:

```powershell
cd web
npx pnpm@12.11.2 install
npx pnpm@12.11.2 --filter @bitchord/app dev
```

Then open the local URL printed by Vite, normally `http://localhost:5173`.

### Browser extension

Open the [NIKA Extension source](https://github.com/Vinegarz/NIKA/tree/rebrand/nika-android/web/extension) for build instructions and Chrome/Firefox packages.

## Contributing

NIKA preserves the upstream project’s open-source licenses and third-party attributions. Please read [CONTRIBUTING.md](CONTRIBUTING.md), [ADDITIONAL.md](ADDITIONAL.md), and [CODE_OF_CONDUCT.md](CODE_OF_CONDUCT.md) before contributing.

## Disclaimer

NIKA does not host copyrighted music. It acts as a client for local files and supported public or user-authenticated services. Users are responsible for complying with applicable laws and third-party terms.

## License

NIKA is distributed under the GNU General Public License v3.0. See [LICENSE](LICENSE).

<div align="center">

Maintained on GitHub by [Vinegarz](https://github.com/Vinegarz).

</div>
