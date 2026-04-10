# zvideo-compressor

纯前端视频压缩工具，使用 WebCodecs API + Mediabunny，视频不离开您的设备，100% 隐私安全。

## 在线访问

https://zedex.github.io/zvideo-compressor/

## 功能特性

- 🚀 **纯前端处理** - 视频文件不上传服务器，保护隐私
- ⚡ **WebCodecs API** - 高性能硬件加速编码
- 🎨 **直观界面** - 拖拽上传，实时预览
- 🔧 **自定义参数** - 分辨率、比特率、帧率可调
- 📊 **对比预览** - 压缩前后效果实时对比
- 💾 **本地下载** - 一键导出 MP4 文件

## 压缩预设

| 预设 | 分辨率 | 比特率 | 帧率 | 适用场景 |
|------|--------|--------|------|----------|
| 高压缩 | 360p | 600kbps | 15fps | 文件最小，适合快速分享 |
| 平衡 | 480p | 800kbps | 18fps | 质量与大小的平衡 |
| 高质量 | 720p | 1000kbps | 24fps | 接近原画质 |

## 文件大小限制

| 限制 | 目标帧率 |
|------|----------|
| 10MB | 15fps |
| 20MB | 18fps |
| 50MB | 20fps |
| 100MB+ | 24fps |

## 浏览器支持

需要支持 WebCodecs API 的现代浏览器：

- Chrome 94+
- Edge 94+
- 其他基于 Chromium 的浏览器

## 使用方法

1. 打开 `index.html` 或访问在线版本
2. 拖拽或点击选择视频文件
3. 选择分享平台、文件大小限制或压缩质量预设
4. 或手动调整分辨率、比特率、帧率参数
5. 点击"开始压缩"
6. 处理完成后下载压缩后的视频

## 技术栈

- HTML5 + CSS3 + JavaScript (Vanilla)
- [Tailwind CSS](https://tailwindcss.com/) - 样式框架
- [Mediabunny](https://mediabunny.dev/) - MP4 容器封装
- WebCodecs API - 视频编解码

## 本地开发

直接在浏览器中打开 `index.html` 即可使用，无需构建工具。

## 许可证

MIT License
