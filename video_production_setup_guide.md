
# Cloudfox Video Production Setup Guide

This guide outlines the standard recording workflow and setup for two types of content:
- **Training videos for HubSpot Growth Engine**
- **YouTube videos for business/property insights**

---

## 🎬 Preferred Workflow (Option 2)

All content is initially created using:
- **Sony ZV-E10 II** camera (4K to SD card)
- **Screen recorded via QuickTime**
- **Slides prepared in PowerPoint/Keynote**
- **Script written in Word and used with Elgato Teleprompter**
- **Audio recorded directly to camera using DJI Mic Mini 2**
- **Editing done in DaVinci Resolve**
- **OBS only introduced later for live content or scene testing**

---

## ✅ Pre-Recording Checklist

### Equipment
- [ ] Sony ZV-E10 II with Sigma 16mm f1.4
- [ ] DJI Mic Mini (charged and paired)
- [ ] Elgato Teleprompter set up
- [ ] Tripod + SmallRig cage mounted
- [ ] Lighting (Godox E45 + Ulanzi fill)
- [ ] MacBook Air M1 with UGREEN Revodok Pro 108 hub
- [ ] Samsung T7 SSD connected
- [ ] SD card inserted and formatted (V60, 128GB)

### Script & Slides
- [ ] Script drafted in Word
- [ ] Slides completed in Keynote or PowerPoint
- [ ] Slides exported as PNGs (optional for Resolve)
- [ ] Teleprompter script loaded

### Audio/Video Check
- [ ] Set camera to 4K30 and manual audio level
- [ ] Perform a quick “clap” for sync
- [ ] Frame and light scene
- [ ] Check storage paths and record location (T7 SSD)

---

## ♻️ Reusable Assets Table

| Asset | Use | Reusability |
|-------|-----|-------------|
| Lower thirds | Branding & ID | Save as compound clip or Fusion preset |
| PIP overlay | Cam + slide layout | Use as frame + transform in Resolve |
| Intro animation | Standard opener | Store in Power Bin |
| Outro CTA | Subscribe + next video | Reuse with updated link overlays |
| Logo watermark | Subtle brand | Overlay at low opacity |
| Audio profile | Consistent voice tone | Save EQ/compression preset |
| LUTs | Colour grading | Consistent visual feel |

---

## 🔌 Equipment & Hub Port Assignment

| Device | Connection | Notes |
|--------|------------|-------|
| **Sony ZV-E10 II** | USB-C directly to Mac | Cleanest video path |
| **Samsung T7 SSD** | USB-C on UGREEN hub | Fast storage, reliable |
| **Stream Deck** | USB-A on UGREEN hub | Low load |
| **Elgato Teleprompter** | USB-A on UGREEN hub | Minimal bandwidth |
| **HDMI monitor** | HDMI on UGREEN hub | Use 1080p for performance |
| **Power** | Apple USB-C charger to hub PD | Pass-through to MacBook |

---

## 📁 Folder Structure
```
video-projects/
├── _global-assets/                  # Master reusable files
│   ├── lower-thirds/
│   ├── overlays/
│   ├── music/
│   └── logos/
├── 02-youtube-business/
│   ├── 2024-07-ep1-first-topic/
│   │   ├── zv-e10/
│   │   ├── b-roll/
│   │   ├── stock-footage/
│   │   ├── screen-recordings/
│   │   ├── slides/
│   │   ├── project-files/           # Resolve projects, synced bins
│   │   ├── deliverables/
│   │   └── reused-assets/           # Local copies if modified for this project
```

---

## 🎯 Notes
- Keep camera audio for ease unless advanced post is needed.
- Use OBS only once base workflow is solid.
- Always test your full setup before batch recording.
