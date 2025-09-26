# Streamly - Static Video Streaming

Streamly is a **Netflix-style static video website** that can be hosted on GitHub Pages.  
This version is fully static — no backend. Videos are stored in the `/videos/` folder, and metadata is in `videos.json`.

---

## Features

- Browse and watch videos
- Search/filter videos by title
- Simple, responsive design using Tailwind CSS
- Fully static: can host on GitHub Pages

---

## How to Use

1. Upload your **video files** to the `/videos/` folder.  
2. Add **thumbnails** for each video in the same folder (JPEG/PNG).  
3. Edit `videos.json` to include your videos, e.g.:

```json
[
  {
    "id": "1",
    "title": "Sample Movie",
    "description": "A short sample video",
    "url": "videos/sample.mp4",
    "thumbnail": "videos/sample.jpg"
  }
]
