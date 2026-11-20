# ClipForge Lite

A free, browser-based vertical video clip editor. It uses FFmpeg WebAssembly in your browser; source video files are not uploaded to a server.

## Features
- Load a local MP4, MOV, WebM, or other browser-supported video.
- Create multiple clips using start and end times in seconds.
- Export vertical 9:16 MP4 at 720p or 1080p.
- Adjust horizontal crop position.
- Add a manually typed caption and optional opening hook.
- Download each selected moment separately.

## Use
Open the GitHub Pages URL in a modern browser. Select a video, set clip ranges, choose caption and output options, then select **Export MP4 clips**.

## Enable GitHub Pages
1. Open repository **Settings → Pages**.
2. Under **Build and deployment**, choose **Deploy from a branch**.
3. Select branch **main** and folder **/(root)**, then save.
4. Wait for GitHub Pages to publish the site. The URL will be shown on that settings page.

## Limitations
- No AI viral-moment detection or automatic transcription.
- Captions are manually entered and are not speech-synced.
- FFmpeg WebAssembly can be slow and memory-intensive, especially on phones. Start with short clips and 720p.
- Internet access is required to download FFmpeg WebAssembly on first use.
- Test with a short, non-sensitive video before relying on exports. Browser/device compatibility has not yet been verified end-to-end.

## License
MIT
