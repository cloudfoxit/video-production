# Video Production Setup Guide

This guide details the standard recording workflow, equipment, and editing process for Cloudfox video content.

## Equipment & Pre-Recording Checklist

- Sony ZV-E10 II with Sigma 16mm f1.4
- DJI Mic Mini (charged and paired)
- Elgato Teleprompter set up
- Tripod + SmallRig cage mounted
- Lighting (Godox E45 + Ulanzi fill)
- MacBook Air M1 with UGREEN Revodok Pro 108 hub
- Samsung T7 SSD connected
- SD card inserted and formatted (V90, 128GB)

## Script & Slides

- Script drafted in Word or Markdown
- Slides completed in Keynote or PowerPoint
- Slides exported as PNGs (optional for Resolve)
- Teleprompter script loaded

## Audio/Video Check

- Set camera to 4K30 and manual audio level
- Perform a quick “clap” for sync
- Frame and light scene
- Check storage paths and record location (T7 SSD)

## Editing Workflow (DaVinci Resolve)

### Timeline Layout

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

## Reusable Assets Table

| Asset | Use | Reusability |
|-------|-----|-------------|
| Lower thirds | Branding & ID | Save as compound clip or Fusion preset |
| PIP overlay | Cam + slide layout | Use as frame + transform in Resolve |
| Intro animation | Standard opener | Store in Power Bin |
| Outro CTA | Subscribe + next video | Reuse with updated link overlays |
| Logo watermark | Subtle brand | Overlay at low opacity |
| Audio profile | Consistent voice tone | Save EQ/compression preset |
| LUTs | Colour grading | Consistent visual feel |

## Equipment & Hub Port Assignment

| Device | Connection | Notes |
|--------|------------|-------|
| Sony ZV-E10 II | USB-C directly to Mac | Cleanest video path |
| Samsung T7 SSD | USB-C on UGREEN hub | Fast storage, reliable |
| Stream Deck | USB-A on UGREEN hub | Low load |
| Elgato Teleprompter | USB-A on UGREEN hub | Minimal bandwidth |
| HDMI monitor | HDMI on UGREEN hub | Use 1080p for performance |
| Power | Apple USB-C charger to hub PD | Pass-through to MacBook |

For folder setup and project workflow, see the [Start Here Guide](start_here.md). For live streaming, see the [OBS Live Streaming Guide](obs_live_streaming_setup_guide.md).
