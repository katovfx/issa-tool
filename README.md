<img width="307" height="307" alt="inverted_mus_ai" src="https://github.com/user-attachments/assets/f5e4c542-7a7c-4eb0-80d8-bbb0246d9837" />


# issa tool

A simple Windows app for saving video and audio from SoundCloud, YouTube, X (Twitter), TikTok and
Instagram. Paste a link, pick a format, press download.

## Features

- **Video**: MP4, MKV, MOV, WebM or AVI, from 480p up to 8K, at the original frame rate or a fixed
  one (8–60 fps, or any custom rate from 1 to 240)
- **Audio**: MP3 (best VBR, or 320/256/192/128 kbps) or WAV
- A preview of what's downloading, with a progress bar
- **Downloads** panel listing everything you've saved, with redownload and "show in folder"
- Desktop notification when a download finishes (can be turned off)
- Themes: Midnight, Sakura, Light, Ocean, Drank and Forest
- One-tap updates from this repo's releases

## Install

1. Download `issa.tool.setup.exe` from the [latest release](../../releases/latest).
2. Run it, choose where to install (any drive or folder), and pick your shortcuts.

No admin rights are needed: it installs for your Windows user only. The app needs about 220 MB.

> **"Windows protected your PC"?** The setup isn't code-signed yet, so Windows SmartScreen warns
> about it while it's new. Click **More info → Run anyway**.

## Updating

Open **Settings → Updates → Check for updates**. If there's a newer version here, the app downloads
it, installs it in the same folder and reopens. Your settings and download history are kept.

## Uninstalling

Use **Windows Settings → Apps → issa tool → Uninstall**, or run `uninstall.exe` in the install
folder. It removes only the app's own files. Your downloaded songs and videos are never touched,
and your settings are kept unless you tick "also delete my settings and download history".

## Where your things are kept

| What | Where |
| --- | --- |
| The app | the folder you chose when installing |
| Settings, download history | `%APPDATA%\issa tool` |
| Your downloads | the save folder set in **Settings → General** (default: `Music\SoundCloud`) |

## Use it responsibly

Only download content you have the right to download, such as your own uploads, content that is
free to download, or content whose owner has given permission. Respect each site's terms of service
and copyright law where you live.

## Run from source

Requires Windows 10/11 and Python 3.14.

## Build the setup

```bat
build_setup.bat
```

### About antivirus false alarms

Python apps packaged with PyInstaller share PyInstaller's prebuilt launcher with some malware, so a
few antivirus engines flag the launcher itself. This project builds with its own launcher compiled
from PyInstaller's source instead. See [bootloader/README.txt](bootloader/README.txt) for how to
compile it; without it the build still works, just with the stock launcher.

## Project files

| File | What it is |
| --- | --- |
| `issa tool.exe` | the app |
| `issa tool setup.exe` | the installer, uninstaller and updater |


# Running the app
yt-dlp[default]>=2026.8.19
imageio-ffmpeg>=0.6.0
deno>=2.9.7
Pillow>=12.3.0

# Building the installer (pinned: the project's own launcher in bootloader\ matches this version)
pyinstaller==6.22.3 


issa x- https://x.com/issa_ngas

