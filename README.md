<div align="center">

<img src="./logo.png" width="120" height="120" alt="TerapPlay Logo" />

# TerapPlay

**Stream and download your Terabox videos — beautifully, privately, and fast.**

[![Platform](https://img.shields.io/badge/Platform-Android%20%7C%20Linux-6C63FF?style=for-the-badge)](https://github.com)
[![Release](https://img.shields.io/github/v/release/yourusername/teraplay?style=for-the-badge&color=00D4FF)](https://github.com)
[![License](https://img.shields.io/badge/License-Proprietary-FF6B6B?style=for-the-badge)](https://github.com/amanhackedyou)

</div>

---

## What is TerapPlay?

TerapPlay is a sleek, privacy-first media client that lets you stream and download videos from your Terabox account — no ads, no bloat, no Terabox app required. Paste a share link and start watching in seconds.

<!-- ---

## Screenshots

> *(Coming soon — screenshots will be added with the first stable release)*

--- -->

## Features

### Streaming
- Paste any Terabox share link and instantly stream the video
- Choose from all available qualities — **360p, 480p, 720p, 1080p**, and beyond
- Streams load fast with adaptive quality selection

### Video Player
- Sleek full-screen player with gesture controls
- **Horizontal swipe** to seek anywhere in the video
- **Swipe left** to adjust brightness · **Swipe right** to adjust volume
- **Double-tap** left/right to skip ±10 seconds
- **Loop mode** — repeat your video endlessly
- **Sleep timer** — auto-pause after 10, 15, 30, 45, 60, or 90 minutes
- **Aspect ratio** cycling — Fit / Fill / Stretch / Fit-W / Fit-H
- **Playback speed** — 0.25× to 3.0× with your preference remembered
- **Audio track** selector for multi-language videos
- **Subtitle track** selector with on/off toggle
- **Screenshot** — capture any frame directly from the player
- **Lock screen** — lock all controls with a single tap to prevent accidental touches
- **Resume where you left off** — every video remembers your last position
- Full keyboard support on desktop (Space, J/L, arrows, F, M, Escape)
- Mouse hover to reveal controls on desktop

### Downloads *(Android)*
- Download videos in any available quality for offline viewing
- Downloads run **in the background** — even after swiping the app away
- Queue multiple downloads simultaneously (up to 2 at a time)
- Pause, resume, and retry downloads at any time
- Grid and list view for your download library
- Search and sort by name, date, or size
- Tap any completed download to play it instantly

### History
- Every link you analyze is saved to your history
- Tap any history item to watch or download again with fresh stream links
- Search through your history
- Swipe to delete individual entries

### Privacy
- **PIN protection** — lock the Downloads and History screens behind a PIN
- Downloads are saved in your chosen folder in the app's own format

### Platform Support
| Feature | Android | Linux Desktop |
|---|:---:|:---:|
| Streaming | ✅ | ✅ |
| Video player | ✅ | ✅ |
| Downloads | ✅ | — |
| Background downloads | ✅ | — |
| History | ✅ | ✅ |
| PIN protection | ✅ | ✅ |

---

## Installation

### Android

> **Minimum:** Android 6.0 (API 23) or higher

1. Go to the [**Releases**](https://github.com/amanhackedyou/teraplay/releases/latest) page
2. Download the `.apk` file for your device:
   - `app-arm64-v8a-release.apk` *(33.1 MB)* — most modern phones (recommended)
   - `app-armeabi-v7a-release.apk` *(30.0 MB)* — older 32-bit phones
   - `app-x86_64-release.apk` *(37.9 MB)* — x86 emulators / some tablets
   - `app-universal-release.apk` — if unsure, use this
3. Open the downloaded file on your phone
4. If prompted, allow installation from unknown sources:
   - Go to **Settings → Apps → Special app access → Install unknown apps**
   - Enable it for your file manager or browser
5. Tap **Install**

---

### Linux Desktop

> **Minimum:** Ubuntu 20.04 / Debian 11 or any equivalent distro with GTK 3

**Debian/Ubuntu package**
```bash
sudo dpkg -i teraplay_amd64.deb
```

---

## How to Use

1. **Open the app** and tap the search/home screen
2. **Paste a Terabox share link** into the input field
3. Tap **Analyze** — the video info loads in seconds
4. Tap **Watch** to stream, or **Download** to save offline
5. Choose your preferred quality from the sheet that appears

That's it.

---

## Requirements

### Android
- Android 6.0+
- Internet connection for streaming
- Storage permission for downloads

### Linux
- 64-bit x86 processor
- GTK 3.0+
- OpenGL-capable GPU (for video playback)
- `libmpv` — install if not present:
  ```bash
  # Ubuntu / Debian
  sudo apt install libmpv-dev

  # Fedora
  sudo dnf install mpv-libs

  # Arch
  sudo pacman -S mpv
  ```

---

## FAQ

**Q: Do I need a Terabox account?**
No. You only need a Terabox **share link**. No login, no account.

**Q: Why does the app ask for storage permission on Android?**
Only to save downloaded videos to your chosen folder. The app never accesses any other files.

**Q: Can I set a custom download folder?**
Yes — go to the **Downloads** tab and tap the folder icon in the top bar.

**Q: The video won't play / shows an error. What do I do?**
Share links expire. If a link fails, paste it again to fetch fresh stream URLs. Links from Terabox are time-limited.

**Q: I forgot my PIN. How do I get back in?**
Tap **Forgot PIN** on the PIN entry screen. You'll be prompted to enter the recovery password you set during PIN creation.

**Q: Downloads keep failing. Why?**
Stream links are time-limited. If a download was queued a while ago, cancel it and start it again — this fetches a fresh link.

**Q: Why does the player show a blue screen on Linux?**
This is a GPU driver compatibility issue. Make sure your GPU drivers are up to date. TerapPlay automatically falls back to software rendering on Linux when needed.

---

## Troubleshooting

| Problem | Solution |
|---|---|
| "No streams found" error | The share link may be expired, private, or from a region-locked account |
| App crashes on launch (Android) | Ensure you're on Android 6.0+ and have granted storage permission |
| Video stutters | Lower the quality in the player (tap the HD icon) |
| Download stuck at 0% | Cancel and re-add — the stream URL has likely expired |
| Controls hide too fast (Linux) | Move your mouse — controls reappear on mouse movement |
| Black screen in player | Try changing the aspect ratio (tap the ratio label in the player) |

---

## Changelog

### v1.0.0 *(Initial Release)*
- Full streaming support with quality selection
- Feature-rich video player with gesture controls
- Background downloads with queue management *(Android)*
- Watch history with search
- PIN privacy lock *(Android)*
- Linux desktop support with keyboard shortcuts

---

## Disclaimer

TerapPlay is an independent, unofficial media client. It is not affiliated with, endorsed by, or connected to Terabox or its parent company in any way. Users are responsible for ensuring they have the right to access and download any content they interact with through this app. The developers take no responsibility for how the app is used.

---

## Support & Bug Reports

Found a bug or have a suggestion? Open an issue on the [GitHub Issues](https://github.com/amanhackedyou/teraplay-app/issues) page.

Please include:
- Your device / OS version
- The version of TerapPlay you're using
- Steps to reproduce the issue
- Any error messages you see

---

<div align="center">

Made with ❤️ for people who just want to watch their videos.

</div>
