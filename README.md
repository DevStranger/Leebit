# 💖 Leebit Streaming Service 💖

A cute and customizable web-based **HLS (HTTP Live Streaming)** player built using [`hls.js`](https://github.com/video-dev/hls.js). This mini project demonstrates how to implement a media streaming player in the browser, complete with quality control, metadata display, request tracking, and optional geo-based access control.

---

## 🎯 Features (based on the requirements)

### ✅ Must-Have

- ✅ **HLS Playback** – Supports standard `.m3u8` playlist files.
- ✅ **Playlist Selector** – Dropdown menu with 2–3 predefined HLS playlists.
- ✅ **Manual Bitrate Switch** – Buttons to change video quality manually.
- ✅ **Video Info Display** – Shows bitrate, resolution, and audio/video codec info.

### ✨ Nice-to-Have

- ✨ **Request Logger** – Displays all streaming segment requests made by the player in real-time.
- ✨ **GEO-Based Access Control** – Basic IP-based region control using `geoplugin.net`.

---

## 🖥️ Demo Preview

![Zrzut ekranu 2025-05-31 155113](https://github.com/user-attachments/assets/51e42534-5316-440b-aa76-b0e0bdc1e208)
![Zrzut ekranu 2025-05-31 155123](https://github.com/user-attachments/assets/d44c4b2c-e14d-42a4-9ed3-a07b62846988)
![Zrzut ekranu 2025-05-31 155135](https://github.com/user-attachments/assets/e028c00c-15dd-4ab7-9a85-119d21ceddc3)

---

## 🚀 How to Use

### 📁 1. Clone or Download

```bash
git clone https://github.com/your-username/leebit-streaming-service.git
cd leebit-streaming-service
```

## 🌐 Serve with Local Web Server

> ⚠️ Due to CORS restrictions, `.m3u8` files must be loaded via HTTP(S) — not directly from `file://`.

### Example using Python HTTP server:

```bash
# For Python 3.x
python -m http.server
```

Then open your browser and go to:
```bash
http://localhost:8000
```
