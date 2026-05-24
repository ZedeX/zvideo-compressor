# Frontend Video Compress

A pure frontend video compression tool using WebCodecs API. Videos never leave your device - 100% privacy secure.

## Live Demo

https://zedex.github.io/Frontend-video-compress-codex/

## Features

- 🚀 **Pure Frontend Processing** - Videos are processed locally, never uploaded to any server
- ⚡ **WebCodecs API** - High-performance hardware-accelerated encoding
- 🎨 **Intuitive Interface** - Drag and drop upload with real-time preview
- 🔧 **Customizable Parameters** - Adjustable resolution, bitrate, and frame rate
- 📊 **Comparison Preview** - Side-by-side comparison before and after compression
- 💾 **Local Download** - One-click export to MP4 file

## Platform Presets

Built-in presets for popular platforms:

| Platform | Max Size | Resolution | Notes |
|----------|----------|------------|-------|
| WeChat Moments | 10MB | 1080p | Portrait recommended |
| WeChat Chat | 100MB | 720p | - |
| Xiaohongshu | 500MB | 4K | Portrait recommended |
| TikTok/Douyin | 500MB | 4K | Portrait required |
| Bilibili | 4GB | 8K | Supports 120fps |
| YouTube | 128GB | 8K | - |
| Twitter/X | 512MB | 1080p | Max 2min 20sec |
| Instagram | 100MB | 1080p | Portrait recommended |
| Discord | 25MB | 720p | Nitro: 500MB |
| Telegram | 2GB | 4K | - |

## Compression Presets

| Preset | Resolution | Bitrate | Frame Rate | Use Case |
|--------|------------|---------|------------|----------|
| High Compression | 360p | 600kbps | 15fps | Smallest file size |
| Balanced | 480p | 800kbps | 18fps | Quality vs size balance |
| High Quality | 720p | 1000kbps | 24fps | Near original quality |

## Browser Support

Requires modern browsers with WebCodecs API support:

- Chrome 94+
- Edge 94+
- Other Chromium-based browsers

## Usage

1. Open `index.html` or visit the live demo
2. Drag and drop or click to select a video file
3. Choose a platform preset, file size limit, or compression quality
4. Or manually adjust resolution, bitrate, and frame rate
5. Click "Start Compression"
6. Download the compressed video when complete

## Tech Stack

- HTML5 + CSS3 + JavaScript (Vanilla)
- [Tailwind CSS](https://tailwindcss.com/) - Styling framework
- [Mediabunny](https://mediabunny.dev/) - MP4 container muxing
- WebCodecs API - Video encoding/decoding

## Local Development

Simply open `index.html` in your browser. No build tools required.

## Files

- `index.html` - Main application (Mediabunny version)
- `index-mp4-muxer.html` - Alternative version using mp4-muxer
- `favicon.svg` - Site icon

## License

MIT License
