
# 📽️ YouTube Project Getting Started Guide

This guide outlines the complete process for planning, recording, and editing your YouTube or training videos using DaVinci Resolve and your full production setup.

---

## 🧠 Episode Naming Convention

Use the following format for folders and files:
```
YYYY-MM-epXX-descriptive-title/
```

### Examples:
- `2024-07-ep01-optimising-hubspot-pipeline/`
- `2024-08-ep02-common-finance-mistakes/`

### File Naming Inside:
| Type | Example |
|------|---------|
| Camera footage | `ep01-camA-take01.MP4` |
| Screen recording | `ep01-screen-raw.mov` |
| Slide images | `ep01-slides-001.png` |
| DJI mic audio | `ep01-audio-dji.wav` |
| Resolve project | `ep01-edit-v01.drp` |
| Exported video | `ep01-master-1080p.mp4` |
| Thumbnail | `ep01-thumbnail-v1.png` |

---

## 🎞️ Resolve Timeline Layout

### Video Tracks
- **V5** – Overlays / lower thirds
- **V4** – Logos / PIP frames
- **V3** – Camera footage
- **V2** – Slide PNGs or screen capture
- **V1** – Backgrounds / B-roll

### Audio Tracks
- **A3** – Music / SFX
- **A2** – Voiceover (optional)
- **A1** – Camera audio / main sync

Use markers for structure: intro, chapters, CTA.

---

## ✅ Full Project Checklist
see Gabriel VIP [Complete YouTube Recording Process](https://www.youtube.com/watch?v=8PjJHfJq_ws) for video version

### Process Transformation
Understand your video’s purpose (educational, value-driven, branded).

### Idea & Research
- Brainstorm topic aligned with audience problems or searches.
- Validate keywords if applicable.
- Create bullet list of key teaching points.

### Scripting
- Draft script in Word (include visual cues for slides and B-roll).
- Time sections to avoid overlong takes.
- Create slides in Keynote or PowerPoint.

### Script Uploading
- Transfer to Elgato Teleprompter.
- Check pacing and highlight key phrases for delivery.

### Lights
- Godox E45 as key
- Ulanzi RGB as fill/background

### Camera Settings
- Sony ZV-E10 II: 4K30, manual exposure, autofocus on face

### Audio Settings
- DJI Mic Mini 2 set to -6dB or -12dB pad
- Manual level in camera
- Monitor sound test before rolling

### Recording Process
- Record A-roll to SD card
- Screen record with QuickTime if needed
- Clap to sync audio (optional)

### File Downloading
- Offload SD card to project folder
- Save QuickTime file to screen-recordings/

### Files Organisation
Organise into:
```
raw-camera-footage/
screen-recordings/
slides/
audio/
b-roll/
music/
stock/
resolve-projects/
deliverables/
```
### script to create this structure:
cd into your video project directory and run:
```bash
mkdir -p raw-camera-footage screen-recordings slides audio b-roll music stock resolve-projects deliverables
```

### A-Roll Editing
- Cut gaps and mistakes
- Assemble base timeline

### B-Roll
- Add overlays, screenshots, relevant video clips

### Colour Correction & Grading
- Add LUT if applicable
- Adjust exposure/white balance for consistency

### Audio Processing
- Normalize volume
- Optional EQ / denoise

### Video Export Settings
- Format: MP4 H.264
- 1080p or 4K depending on final output
- Target bitrate: 15,000–30,000 kbps

### The Great Result
- Review final video
- Export thumbnails
- Upload and add YouTube end screens / description

---

Ready to roll.
