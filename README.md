# 🌾 AgriMedia Portal — কৃষি মিডিয়া পোর্টাল

A modern, responsive multimedia web portal that dynamically fetches and displays content from a shared Google Drive folder — built for **DAE Bangladesh** agricultural extension workers.

## ✨ Features

- 🎬 **Videos** — inline playable carousel with fullscreen support
- 📊 **Presentations** — embedded Google Slides / PPTX viewer
- 📄 **PDFs** — inline Drive PDF viewer (no redirects)
- 🖼 **Infographics** — responsive image grid with lightbox
- ⬇ **Direct Downloads** — every item has an Export button (bypasses Drive preview)
- 📱 **Fully responsive** — mobile, tablet, desktop

## 🚀 Quick Start

1. Open `index.html` in any browser (or deploy to Vercel/GitHub Pages)
2. Click **⚙** → enter your Google Drive API Key
3. Paste your Drive folder ID or URL → click **Load ▶**

## ⚙️ Setup

### Google Drive API Key
1. [Google Cloud Console](https://console.cloud.google.com) → Enable **Google Drive API**
2. Create an API Key → restrict it to **Google Drive API**
3. Enter it in the portal's ⚙ Setup panel (saved in localStorage)

### Folder Permissions
- Right-click folder in Drive → **Share** → **"Anyone with the link"** → Viewer

## 🌐 Deploy

```bash
# GitHub Pages — push this repo and enable Pages on main branch
# Vercel — import repo, deploy as static site (zero config)
```

## 🏗 Tech Stack

Single-file HTML/CSS/JS — no build step, no dependencies, no framework.
Uses Google Drive API v3 for file listing and direct download links.

---

**Department of Agricultural Extension (DAE) · কৃষি সম্প্রসারণ অধিদপ্তর**  
Built by Abu Md. Moniruzzaman · Additional Deputy Director (Horticulture) · Kurigram
