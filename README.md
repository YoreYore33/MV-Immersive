# MV Immersive

Add a new immersive style to Cider with synced music videos.

> **Cider MV Resolver is required for YouTube playback.**
> Installing this plugin alone will not enable YouTube playback. Install and run the companion app for Windows x64:
> [Download Cider MV Resolver](https://github.com/YoreYore33/Cider-MV-Resolver)

## Overview

Assign a YouTube video to each Apple Music track and watch it alongside Cider’s audio. Video playback follows pause, resume, seeking, and track changes automatically. Adjust the video’s start offset to match the song.

For tracks without an MV, enjoy album artwork, lyrics, and customizable backgrounds instead.

## Screenshots

![MV Immersive screenshot 1](https://github.com/user-attachments/assets/6df18c75-5e93-4ff7-a209-e1bad9a44cf5)

![MV Immersive screenshot 2](https://github.com/user-attachments/assets/6597ac89-7747-46c6-aa8d-ec3ade4fda2c)

![MV Immersive screenshot 3](https://github.com/user-attachments/assets/989c3ccc-4dc5-468d-bf4a-06479bd5a28a)

![MV Immersive screenshot 4](https://github.com/user-attachments/assets/7f8593b5-9fdd-460e-a877-5671d3d3bd7d)

## Features

- **Per-track videos:** Save a YouTube URL and start offset for each song.
- **Synchronized playback:** Video follows playback, pause, resume, seeking, and track changes.
- **Three lyric modes:** Choose Full, Compact, or Overlay.
- **Playback queue:** Show or hide the queue alongside your video or lyrics.
- **Custom backgrounds:** Set animated background colors for each song.
- **Background grain:** Add subtle texture with adjustable strength, set to 3% by default.
- **Artwork fallback:** Display album artwork when no MV is configured.
- **Remembered layouts:** Keep separate layout preferences for tracks with and without an MV.
- **In-player settings:** Edit video URLs, timing, and appearance directly from the immersive player.
- **Error guidance:** See connection guidance and retry when video playback fails.

## Getting Started

1. Install **MV Immersive** from the Cider Marketplace.
2. Download [Cider MV Resolver](https://github.com/YoreYore33/Cider-MV-Resolver).
3. Extract the Resolver ZIP and run `install.cmd`.
4. Restart Cider.
5. Select **MV Immersive** from the immersive layout picker.
6. Play a song, open the **MV** button, and save its YouTube video URL.
7. Adjust the start offset if the video and song begin at different points.

After installation, the Resolver starts automatically when you sign in to Windows.

## Troubleshooting

### The Resolver cannot be reached

If you have not installed it, follow the instructions on the [Cider MV Resolver page](https://github.com/YoreYore33/Cider-MV-Resolver).

If it is already installed, launch:

```text
%LOCALAPPDATA%\CiderMvResolver\CiderMvResolver.exe
```

Then use **Retry** in the plugin. Also check that the configured Resolver address is correct. The default is `http://127.0.0.1:3060`.

### A video fails to load

Check the saved video URL, your internet connection, and whether the Resolver’s bundled yt-dlp needs updating. Expand the error details in the plugin for more information.

## Privacy

MV assignments and settings are stored locally on your PC.

Cider MV Resolver listens on `127.0.0.1:3060` and connects to YouTube to obtain temporary playback URLs. It does not save completed video files.

## Compatibility

- Windows x64
- Cider `sh.cider.dotnet`
- Cider MV Resolver for YouTube playback

## Notice

Please use videos in accordance with the applicable rights and service terms.

This project is not affiliated with YouTube or Apple.
