# YouTube Watch Time

A lightweight tool to generate multiple YouTube video instances for boosting watch time, built with HTML, CSS, and the YouTube IFrame API. Created by `@codebyhasan` to help creators and developers experiment with video playback in a simple, efficient way.

## Features
- **Video Playback**: Generates up to 50 instances of a YouTube video (default: 10).
- **Custom Settings**: Plays videos at 0.25x speed, muted, looped, and with captions/subtitles turned off.
- **User-Friendly UI**: Sticky header with usage guide and input fields, plus Enter key support for quick generation.
- **Reset Option**: Clear all instances and reset to defaults with one click.
- **Performance Optimized**: Limited to 50 instances max to avoid overwhelming your machine.
- **Branding**: Copyright notice with a dynamic year and link to `@codebyhasan`’s X profile.

## Usage
You can use this tool in two ways:

1. **Online Access**:
   - Visit [codebyhasan.github.io/youtubewatchtime](https://codebyhasan.github.io/youtubewatchtime)
   - Or try [youtubewatchtime.onrender.com](https://youtubewatchtime.onrender.com)

2. **Local Setup**:
   - **Clone or Download**: Get the `index.html` file from this repository.
   - **Open in Browser**: Double-click `index.html` to run it locally (no server required).

### Steps
1. **Input Details**:
   - **Video ID/URL**: Enter a YouTube video ID (e.g., `KvkmgancSr4`) or full URL (e.g., `https://www.youtube.com/watch?v=KvkmgancSr4`).
   - **Total Instances**: Set the number of video players (1-50; default is 10).
2. **Generate**:
   - Click "Generate Watch Time" **or** press Enter in either input field to start the videos.
3. **Reset**: Click "Reset" to clear the grid and restore defaults.

### Notes
- Videos play automatically at 0.25x speed, muted, and looped, with captions off by default.
- If you see an error (e.g., "Embedding not allowed"), check if the video is public and embeddable on YouTube.
- For best performance, keep the instance count low (e.g., 10-20) on slower machines.

## Why This Tool?
- **Watch Time Experiments**: Test how multiple instances affect playback (note: YouTube may not count this as official watch time due to algorithmic filters).
- **Learning**: A simple example of using the YouTube IFrame API with dynamic DOM manipulation.
- **Fun**: Create a cool grid of slow-motion videos for personal projects or demos!

## Author
- **Hasan (@codebyhasan)**  
  - X: [https://x.com/@codebyhasan](https://x.com/@codebyhasan)  
  - Built with love and coffee in 2025.

## License
© 2025 [@codebyhasan](https://x.com/@codebyhasan). All rights reserved. Feel free to use this for personal projects, but please don’t redistribute without crediting me!

---
Happy coding, brother! Let me know if you need more tweaks!
