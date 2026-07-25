# 3D SBS Image Viewer

A browser-based viewer for full SBS 3D images, designed for use on 3D displays that require half SBS images.  
No installation required — just open the HTML file and go.

https://ntm-3d.github.io/3DSBSImageViewer

---

## Features

- **Single-file app** — one `.html` file, no server, no dependencies
- **SBS image rendering** — correctly converts full SBS images into half SBS
- **Slideshow mode** — auto-advance with configurable interval (1–60 seconds)
- **Zoom & pan** — mouse wheel to zoom, click and drag to pan
- **Folder support** — load an entire folder (including subdirectories) at once
- **Flexible sorting** — sort images by name, date, or file size (ascending or descending)
- **On-screen display (OSD)** — 3D play/pause and skip indicators rendered with configurable depth
- **Image info overlay** — shows filename, date, resolution, aspect ratio, and file size; expandable for full detail
- **Auto-hiding cursor** — hides after 2 seconds of inactivity in fullscreen mode
- **Fullscreen** — automatically enters fullscreen on start

---

## Getting Started

1. Download `3D_SBS_Image_Viewer_v1_3.html`
2. Open it in a Chromium-based browser (Chrome, Edge, etc.)
3. Select your SBS image files or a folder
4. Configure settings and click **Start Viewer**

> **Note:** Folder selection requires a browser that supports the [File System Access API] (Chrome/Edge recommended). Firefox and Safari users can still use file select.

---

## Settings

| Setting | Description |
|---|---|
| **Slideshow interval** | Seconds between auto-advancing images (1–60) |
| **Sort order** | Name, date, or size — ascending or descending |
| **OSD 3D depth** | Parallax offset for the on-screen display icons (-30 to +30) |

---

## Controls

| Input | Action |
|---|---|
| `→` / `←` Arrow Keys | Next / previous image |
| Mouse Back / Forward buttons | Next / previous image |
| `Space` or Middle mouse button | Start / stop slideshow |
| `I` or Right-click (1st) | Toggle image info overlay |
| `O` or Right-click (2nd) | Expand / collapse info details |
| Right-click (3rd) | Hide info overlay |
| `0` | Reset zoom and pan |
| Mouse wheel | Zoom in / out |
| Click & drag | Pan image |
| `Escape` | Exit fullscreen and return to settings |

---

## Browser Compatibility

| Browser | File select | Folder select |
|---|---|---|
| Chrome / Edge (Chromium) | ✅ | ✅ |
| Firefox | ✅ | ❌ |
| Safari | ✅ | ❌ |
