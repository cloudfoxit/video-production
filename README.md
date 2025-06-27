# Cloudfox Video Production Repository

Welcome to the Cloudfox Video Production repository! This guide brings together all the essential information, workflows, and best practices for planning, recording, and editing professional YouTube and training videos for property and SaaS professionals.

---

## 📽️ Getting Started

This repository is designed to help you:

- Plan and script engaging video content
- Set up your recording and editing environment
- Organize your files and assets for efficient production
- Follow best practices for consistent, high-quality output

---

## 🧠 Episode Naming & Folder Structure

**Naming Convention:**

```text
YYYY-MM-epXX-descriptive-title/
```

**Examples:**

- `2024-07-ep01-optimising-hubspot-pipeline/`
- `2024-08-ep02-common-finance-mistakes/`

**File Naming Inside:**

| Type            | Example                     |
|-----------------|----------------------------|
| Camera footage  | `ep01-camA-take01.MP4`     |
| Screen recording| `ep01-screen-raw.mov`      |
| Slide images    | `ep01-slides-001.png`      |
| DJI mic audio   | `ep01-audio-dji.wav`       |
| Resolve project | `ep01-edit-v01.drp`        |
| Exported video  | `ep01-master-1080p.mp4`    |
| Thumbnail       | `ep01-thumbnail-v1.png`    |

**Recommended Folder Structure:**

```text
video-projects/
├── _global-assets/
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
│   │   ├── project-files/
│   │   ├── deliverables/
│   │   └── reused-assets/
```

**Quick script to create a new project structure:**

```bash
mkdir -p raw-camera-footage screen-recordings slides audio b-roll music stock resolve-projects deliverables
```

---

## 🎬 Preferred Workflow

All content is initially created using:

- **Sony ZV-E10 II** camera (4K to SD card)
- **Screen recorded via QuickTime**
- **Slides prepared in PowerPoint/Keynote**
- **Script written in markdown and used with Elgato Teleprompter**
- **Audio recorded directly to camera using DJI Mic Mini 2**
- **Editing done in DaVinci Resolve**
- **OBS only introduced later for live content or scene testing**

---

## ✅ Pre-Recording & Project Checklist

### Equipment

- Sony ZV-E10 II with Sigma 16mm f1.4
- DJI Mic Mini (charged and paired)
- Elgato Teleprompter set up
- Tripod + SmallRig cage mounted
- Lighting (Godox E45 + Ulanzi fill)
- MacBook Air M1 with UGREEN Revodok Pro 108 hub
- Samsung T7 SSD connected
- SD card inserted and formatted (V60, 128GB)

### Script & Slides

- Script drafted in markdown or Word
- Slides completed in Keynote or PowerPoint
- Slides exported as PNGs (optional for Resolve)
- Teleprompter script loaded

### Audio/Video Check

- Set camera to 4K30 and manual audio level
- Perform a quick “clap” for sync
- Frame and light scene
- Check storage paths and record location (T7 SSD)

### Project Process

- Brainstorm topic aligned with audience problems or searches
- Validate keywords if applicable
- Create bullet list of key teaching points
- Draft script (include visual cues for slides and B-roll)
- Time sections to avoid overlong takes
- Create slides in Keynote or PowerPoint
- Transfer script to Elgato Teleprompter
- Read through script out loud to check flow and adjust
- Check pacing and highlight key phrases
- Set up lights, camera, and audio
- Record A-roll and screen as needed
- Offload files to project folder
- Organise files into:
  - raw-camera-footage/
  - screen-recordings/
  - slides/
  - audio/
  - b-roll/
  - music/
  - stock/
  - resolve-projects/
  - deliverables/

---

## 🎞️ DaVinci Resolve Timeline Layout

**Video Tracks:**

- V5 – Overlays / lower thirds
- V4 – Logos / PIP frames
- V3 – Camera footage
- V2 – Slide PNGs or screen capture
- V1 – Backgrounds / B-roll

**Audio Tracks:**

- A3 – Music / SFX
- A2 – Voiceover (optional)
- A1 – Camera audio / main sync

Use markers for structure: intro, chapters, CTA.

---

## ♻️ Reusable Assets Table

| Asset           | Use                    | Reusability                        |
|-----------------|-----------------------|------------------------------------|
| Lower thirds    | Branding & ID         | Save as compound clip or Fusion preset |
| PIP overlay     | Cam + slide layout    | Use as frame + transform in Resolve |
| Intro animation | Standard opener       | Store in Power Bin                 |
| Outro CTA       | Subscribe + next video| Reuse with updated link overlays   |
| Logo watermark  | Subtle brand          | Overlay at low opacity             |
| Audio profile   | Consistent voice tone | Save EQ/compression preset         |
| LUTs            | Colour grading        | Consistent visual feel             |

---

## 🔌 Equipment & Hub Port Assignment

| Device             | Connection              | Notes                      |
|--------------------|------------------------|----------------------------|
| Sony ZV-E10 II     | USB-C directly to Mac  | Cleanest video path        |
| Samsung T7 SSD     | USB-C on UGREEN hub    | Fast storage, reliable     |
| Stream Deck        | USB-A on UGREEN hub    | Low load                   |
| Elgato Teleprompter| USB-A on UGREEN hub    | Minimal bandwidth          |
| HDMI monitor       | HDMI on UGREEN hub     | Use 1080p for performance  |
| Power              | Apple USB-C charger to hub PD | Pass-through to MacBook |

---

## 🎯 Additional Notes

- Keep camera audio for ease unless advanced post is needed.
- Use OBS only once base workflow is solid.
- Always test your full setup before batch recording.
- Review final video, export thumbnails, upload, and add YouTube end screens/description.

---

## 📚 References & Resources

- [Complete YouTube Recording Process (Gabriel VIP)](https://www.youtube.com/watch?v=8PjJHfJq_ws)

---

Ready to roll!
