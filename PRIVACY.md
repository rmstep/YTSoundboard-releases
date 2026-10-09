# YTSoundboard Privacy Policy

_Last updated: October 8, 2026_

The **YTSoundboard Clipper** browser extension and the **YTSoundboard** desktop app do not collect, store, sell, or share personal data with the developer or any third party.

## What the extension does
On youtube.com pages, the extension shows a panel where you choose a start and end time on a video. When you click "Add to soundboard", it sends the video's address, your chosen times, the sound name, and the hotkey you picked to the YTSoundboard app **running on your own computer** (`http://127.0.0.1:38917`). That address is local to your machine; the data never leaves it through the extension.

To suggest a starting point for your clip, the extension also reads YouTube's public "Most replayed" graph for the video you are watching. It does this by requesting that video's own watch page from youtube.com, exactly as your browser does when you open the video, and reading the graph from it. The result is used on your computer to pick a default start and end time and is not stored or sent anywhere.

## What the extension does not do
- It does not collect or transmit browsing history, account information, or analytics.
- It does not use remote code, advertising, or tracking.
- It only runs on youtube.com and only talks to the local app.

## The desktop app
The app saves your sounds and settings on your computer. To make a clip it downloads the selected audio (and, if you ask, the video's thumbnail) from YouTube using the open-source yt-dlp tool, and it checks GitHub for app updates. Nothing about you is sent to the developer.

## Contact
Questions: open an issue at https://github.com/rmstep/YTSoundboard-releases/issues
