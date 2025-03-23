# YouTube Watch Time

[![YouTube Watch Time Hero Image](https://img.recraft.ai/19dc4H8DlWRWzffrnhv02FkpHqJFCh3D-lfgzCYzYVs/rs:fit:1820:1024:0/q:95/g:no/plain/abs://prod/images/c9a4998e-7056-450f-8f15-ab555e043f5d@svg)](https://youtubewatchtime.onrender.com)

A lightweight tool to generate multiple YouTube video instances for boosting watch time, built with HTML, CSS, and the YouTube IFrame API. Created by `@codebyhasan` to help creators and developers experiment with video playback in a simple, efficient way.

## Features
- **Video Playback**: Generates up to 50 instances of a YouTube video (default: 10).
- **Custom Settings**: Plays videos at 0.25x speed, muted, looped, and with captions/subtitles off.
- **User-Friendly UI**: Sticky header with inputs; supports Enter key, "Generate Watch Time," and "Reset" buttons.
- **Forced Reloads**: Every action (Enter, Generate, Reset) reloads the page for a fresh state, persisting inputs via URL.
- **Instance Limits**: Strictly enforces a maximum of 50 instances, clamping higher values for performance.
- **Link Preview**: Open Graph tags with a custom image for sharing on platforms like X.
- **Branding**: Dynamic copyright year and link to `@codebyhasan`’s X profile.

## Usage
You can use this tool in two ways:

1. **Online Access**:
   - [codebyhasan.github.io/youtubewatchtime](https://codebyhasan.github.io/youtubewatchtime)
   - [youtubewatchtime.onrender.com](https://youtubewatchtime.onrender.com)
   - [youtubewatchtime.pages.dev](https://youtubewatchtime.pages.dev)

2. **Local Setup**:
   - **Clone or Download**: Get the `index.html` file from this repository.
   - **Open in Browser**: Double-click `index.html` to run it locally (no server required).

### Steps
1. **Input Details**:
   - **Video ID/URL**: Enter a YouTube video ID (e.g., `KvkmgancSr4`) or URL (e.g., `https://www.youtube.com/watch?v=KvkmgancSr4`).
   - **Total Instances**: Set the number of video players (1-50; default is 10).
2. **Generate**:
   - Click "Generate Watch Time," press Enter in either field, or adjust inputs—page reloads with updated videos.
3. **Reset**:
   - Click "Reset" to revert to default values (`KvkmgancSr4`, 10 instances) and reload.

### Notes
- Each action reloads the page, ensuring a clean slate; input values persist via URL (e.g., `?video=...&instances=...`).
- Videos play at 0.25x speed, muted, and looped automatically.
- If an error occurs (e.g., "Embedding not allowed"), check the video’s public status and embedding permissions.
- For best performance, keep instances low (e.g., 10-20) on weaker machines.

## Why This Tool?
- **Watch Time Experiments**: Test playback with multiple instances (note: YouTube may not count this as official watch time).
- **Learning**: Explore the YouTube IFrame API and dynamic DOM manipulation.
- **Fun**: Create a grid of slow-motion videos for projects or demos.

## Author
- **Hasan (@codebyhasan)**  
  - X: [https://x.com/@codebyhasan](https://x.com/@codebyhasan)  
  - Built with love and coffee in 2025.

## License
© 2025 [@codebyhasan](https://x.com/@codebyhasan). All rights reserved. Use this for personal projects, but please credit me if sharing!
