

<img width="341" height="328" alt="image" src="https://github.com/user-attachments/assets/79c4e72c-bf71-4629-8601-b5a91fc96125" />








# ISSA TOOL

A simple tool for video editors (WILL ADD MORE)

## Features

- **Video**: MP4, MKV, MOV, WebM or AVI, from 480p up to 8K, at the original frame rate or a fixed
  one (8–60 fps, or any custom rate from 1 to 240)
- **Audio**: MP3 (best VBR, or 320/256/192/128 kbps) or WAV
- A preview of what's downloading, with a progress bar
- **Downloads** panel listing everything you've saved, with redownload and "show in folder"
- Desktop notification when a download finishes (can be turned off)
- Drag a link onto the window to download it; downloads can be paused or cancelled
- Themes: Midnight, Sakura, Light, Ocean, Drank and Forest
- One-tap updates from this repo's releases

### Other tools

- **Recording tool**: record any window (even behind others) with the sound your PC plays, at
  10–120 fps or a custom rate up to 240. Export as H.264 or H.265 (graphics card), AV1, VP9, ProRes,
  DNxHR, lossless FFV1 / UT Video, or a Windows codec installed on your PC (e.g. Lagarith, HuffYUV).
  Slow codecs record losslessly first and convert after you stop, so nothing is dropped.
- **Depth**: a depth map version of a recording, or a live depth viewer, from AI (Depth Anything V2,                         
<img width="341" height="328" alt="image" src="https://github.com/user-attachments/assets/ab7382a7-cae4-4446-ac6d-de18ad0a1f0f" />


  on the graphics card) or straight from a game set up in ReShade Changer. Depth level slider.
- **ReShade Changer**: sets ReShade up inside a single-player game for you (any version from 4.9.1
  to the latest; IW4x picks one that works with it), with issa tool's add-on that sends the game's
  real depth to the recording tool without changing what's on screen, plus the most used effects.
- **ProRec**: drag clips in to convert them to Xvid, ProRes, PNG or TGA, with pause and stop.

## Install

1. Download `issa.tool.setup.exe` from the [latest release](../../releases/latest).
2. Run it, choose where to install (any drive or folder), and pick your shortcuts.

<img width="341" height="328" alt="image" src="https://github.com/user-attachments/assets/135694e2-176a-4a96-a690-a184e1108d4a" />


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


## Project files

| File | What it is |
| --- | --- |
issa tool.exe	the app
issa tool setup.exe	the installer, uninstaller and updater
