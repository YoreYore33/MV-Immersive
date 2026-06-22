# MV-Immersive
Play per-track music videos in Cider’s immersive view with synchronized playback, lyrics, queue, and Solarium-inspired controls.
<img width="1919" height="1079" alt="Image" src="https://github.com/user-attachments/assets/6df18c75-5e93-4ff7-a209-e1bad9a44cf5" />
<img width="1919" height="1079" alt="Image" src="https://github.com/user-attachments/assets/6597ac89-7747-46c6-aa8d-ec3ade4fda2c" />
<img width="1919" height="1079" alt="Image" src="https://github.com/user-attachments/assets/989c3ccc-4dc5-468d-bf4a-06479bd5a28a" />
<img width="1919" height="1079" alt="Image" src="https://github.com/user-attachments/assets/7f8593b5-9fdd-460e-a877-5671d3d3bd7d" />


MV Immersive adds a customizable music-video experience to Cider’s immersive player.

Assign a YouTube video to each Apple Music track and enjoy synchronized MV playback alongside Cider’s audio. Playback, pause, seeking, and track changes are synchronized automatically.

## Features

- Per-track MV URL and start-offset settings

- Synchronized playback and seeking

- Full, Compact, and Overlay lyric modes

- Solarium-inspired player controls and queue

- Per-track animated background colors

- Artwork fallback for tracks without an MV

- Settings can be edited directly from the immersive player

## Required companion

YouTube playback requires Cider MV Resolver on Windows x64:

https://github.com/YoreYore33/Cider-MV-Resolver

Install the Resolver, restart Cider, and then enable MV Immersive. The Resolver starts automatically with Windows after installation.

## Getting started

1. Install MV Immersive from https://github.com/YoreYore33/MV-Immersive/releases.

2.Extract to AppData\Roaming\sh.cider.dotnet\plugins.

3. Install Cider MV Resolver from the link above.

4. Restart Cider.

5. Select MV Immersive from the immersive layout picker.

6. Play a track and use the MV button to assign its video URL.

## Privacy

Cider MV Resolver runs locally on 127.0.0.1:3060. MV mappings are stored locally on your PC. The Resolver obtains temporary playback URLs and does not save video files.

## Compatibility

- Windows x64

- Cider sh.cider.dotnet

- Cider MV Resolver is required for YouTube playback

Please use videos in accordance with the applicable rights and service terms. This project is not affiliated with YouTube or Apple.
