# soundMatik releases

soundMatik is a panel for Adobe Premiere Pro 2026. Paste a video link and it
downloads the audio (WAV or MP3) straight into your project's SOUND_EFFECTS bin.

## Download

- **macOS (Apple Silicon):**
  https://github.com/iyiailerobotu-sudo/soundmatik-releases/releases/download/darwin-latest/soundMatik-mac.dmg
- **Windows (64-bit):**
  https://github.com/iyiailerobotu-sudo/soundmatik-releases/releases/download/windows-latest/soundMatik-windows-setup.exe

These two links always serve the current version. Each version is also kept as
`mac-vX.Y.Z` and `win-vX.Y.Z` releases.

## Requirements

- Adobe Premiere Pro 2026 (26.0) or later, with the Creative Cloud desktop app
- macOS 14 Sonoma or later on Apple Silicon (M1 or newer). Intel Macs are not supported.
- Windows 11 64-bit (x64). Premiere Pro 2026 itself requires Windows 11 24H2.

## Install

- **macOS:** open the DMG, double-click "Install soundMatik", approve the
  Creative Cloud window, then restart Premiere Pro. Signed and notarized by Apple.
- **Windows:** run `soundMatik-windows-setup.exe`. The installer is not
  code-signed, so Windows may show "Windows protected your PC": click
  **More info**, then **Run anyway**.
- In Premiere Pro: **Window > UXP Plugins > soundMatik**.

The panel's **Check for updates** link (bottom of the panel) finds new versions here.

## Third-party software

The installers include these open-source programs, unmodified. soundMatik runs
them as separate programs; it does not link to them.

| Program | License | Source |
|---|---|---|
| [yt-dlp](https://github.com/yt-dlp/yt-dlp) | The Unlicense (public domain) | https://github.com/yt-dlp/yt-dlp |
| [FFmpeg](https://ffmpeg.org) (`ffmpeg`, `ffprobe`) | GNU GPL v3 (GPL build, includes x264/x265) | https://ffmpeg.org/download.html - macOS builds and their build sources: https://ffmpeg.martin-riedl.de - Windows builds and their build scripts: https://github.com/yt-dlp/FFmpeg-Builds |
| [Deno](https://deno.com) | MIT | https://github.com/denoland/deno |

FFmpeg is licensed under the GNU General Public License version 3
(https://www.gnu.org/licenses/gpl-3.0.html). You may request the exact
corresponding FFmpeg source for any soundMatik release by opening an issue in
this repository; it will be provided for at least three years after that release.

by Sevki Bugra Ozbek - catheadai.com
