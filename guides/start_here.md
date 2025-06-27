# Start Here Guide

This is your entry point for Cloudfox video production. It covers naming conventions, folder setup, and the full project workflow checklist.

## Episode Naming Convention

Use the following format for folders and files:

```text
YYYY-MM-epXX-descriptive-title/
```

**Examples:**
- `2024-07-ep01-optimising-hubspot-pipeline/`
- `2024-08-ep02-common-finance-mistakes/`

## File Naming Inside

| Type | Example |
|------|---------|
| Camera footage | `ep01-camA-take01.MP4` |
| Screen recording | `ep01-screen-raw.mov` |
| Slide images | `ep01-slides-001.png` |
| DJI mic audio | `ep01-audio-dji.wav` |
| Resolve project | `ep01-edit-v01.drp` |
| Exported video | `ep01-master-1080p.mp4` |
| Thumbnail | `ep01-thumbnail-v1.png` |

## Folder Structure

Organise your project folders as follows:

```text
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

Quick script to create this structure:

```bash
mkdir -p raw-camera-footage screen-recordings slides audio b-roll music stock resolve-projects deliverables
```

## Full Project Checklist

- Brainstorm topic and research
- Draft script (include visual cues for slides and B-roll)
- Create slides in Keynote or PowerPoint
- Transfer script to Elgato Teleprompter
- Set up lights, camera, and audio
- Record A-roll and screen as needed
- Offload files to project folder
- Organise files as above
- Edit in DaVinci Resolve
- Export and review final video
- Upload and publish

For detailed setup and editing workflow, see the [Production Setup Guide](video_production_setup_guide.md). For live streaming, see the [OBS Live Streaming Guide](obs_live_streaming_setup_guide.md).
