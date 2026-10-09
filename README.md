# YTSoundboard

A hotkey soundboard for Windows. Clip a moment from any YouTube video, give it a key, and play it into your microphone (Discord, games, OBS) and your speakers at the same time. Works with Stream Deck.

## Download

Get **YTSoundboard Setup** from the [latest release](../../releases/latest) and run it. It installs for your user only and needs no admin rights. The app updates itself from this repository.

Windows may show a "Windows protected your PC" (SmartScreen) notice because the installer isn't code-signed yet. Click **More info → Run anyway**.

## Setup

1. Open YTSoundboard and click **Install virtual mic (VB-Cable)**. The app downloads VB-Cable from vb-audio.com, verifies its signature, and starts its installer. Approve the Windows prompt, click **Install Driver**, and reboot if asked.
2. Choose your real microphone under **Real microphone**. The virtual mic is selected automatically.
3. In Discord, OBS or your game, set the microphone to **CABLE Output**.
4. Install the [YTSoundboard Clipper extension from the Chrome Web Store](https://chromewebstore.google.com/detail/ytsoundboard-clipper/cdcjmelhnjmfgekefemeiklnlomilhhe) (the app's **Get the Chrome extension** button opens it). It also works in Edge and other Chromium browsers.
5. On a YouTube video, click **YTSoundboard** (bottom right), pick a start and end time, assign a key, and add it.

## Stream Deck

Click **Install Stream Deck plugin** in the app, then drag **Play Sound** onto a key.

## Source code and license

YTSoundboard is open source under the MIT license: https://github.com/rmstep/YTSoundboard

## Third-party software

- [VB-Cable](https://vb-audio.com/Cable/) is the property of VB-Audio Software and is **not** included; it is downloaded from VB-Audio on request.
- [yt-dlp](https://github.com/yt-dlp/yt-dlp) (Unlicense) is bundled.
- [FFmpeg](https://ffmpeg.org) (GPLv3 build from the [ffmpeg-static](https://github.com/eugeneware/ffmpeg-static) project) is bundled; its source is available at those links.
- Built with [Electron](https://www.electronjs.org) (MIT).

Only clip audio you have the right to use.
