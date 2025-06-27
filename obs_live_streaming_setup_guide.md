
# Cloudfox OBS & Live Streaming Setup Guide

This guide outlines the setup for using OBS in live scenarios, including:
- **Live streaming on YouTube**
- **Client-facing Zoom or Microsoft Teams calls**
- **Recording live-mixed content with OBS**

---

## 🎥 OBS Use Cases

| Scenario | OBS Role |
|----------|----------|
| **Live webinars / streams** | Scene switching, overlays, webcam framing |
| **Recorded training (with live transitions)** | Reduce editing with real-time layout control |
| **Zoom/Teams calls (with OBS Virtual Camera)** | Branded or enhanced webcam feed |

---

## ✅ OBS Live Streaming Setup (Optional Future Workflow)

### Hardware

| Device | Connection | Notes |
|--------|------------|-------|
| **Sony ZV-E10 II** | via **Cam Link 4K** or USB-C | Cam Link preferred for true 4K or clean HDMI |
| **Mic** | DJI Mic Mini into camera or USB interface | Ensure audio sync with video |
| **Slides/Demos** | PowerPoint or Keynote | Run in windowed mode for capture |
| **OBS Output** | Set to 1080p or 4K based on system capacity | Use hardware encoder (Apple VT H264) |
| **External Monitor** | HDMI via hub | Useful for OBS multiview or teleprompter mirroring |

---

### OBS Scenes Layout

| Scene | Layout | Use |
|-------|--------|-----|
| **Intro** | Logo + Title screen | Cold open or pre-roll |
| **Cam Only** | Full-screen ZV-E10 | Talking head segments |
| **Slide + Cam (50/50)** | Split view | Ideal for explainer sections |
| **Screen Only** | Full screen capture | Demos or walkthroughs |
| **Outro** | CTA + next video prompt | Branded end screen |

---

### OBS Settings (Recommended)

- **Resolution**: Base & Output = 1920x1080 (or 3840x2160 if your Mac handles it)
- **Encoder**: Apple VT H264 Hardware Encoder
- **Recording Format**: MKV or MOV
- **Audio**: Use one global mic source across all scenes

---

## 🧑‍💻 Using OBS with Zoom or Teams

### Step-by-Step

1. In OBS, go to `Tools > Virtual Camera` and click **Start**.
2. Open Zoom or Teams > Settings > Video > choose **OBS Virtual Camera**.
3. Run your scenes in OBS — Zoom/Teams will display the active scene.

> **Note:** Resolution may be limited to **720p or 1080p**, even if OBS is higher. Prioritise lighting and framing.

---

## 💡 Tips for Stability

- Use direct USB-C connection for ZV-E10 if not using Cam Link.
- Avoid overloading your hub: keep SSD and camera on separate buses if possible.
- Use wired Ethernet if live streaming — Wi-Fi may drop frames.

---

## OBS-Specific Folder Structure

```
obs-projects/
├── scenes/
│   ├── cam-only.obsprofile
│   ├── cam-slide.obsprofile
│   └── screen-only.obsprofile
├── overlays/
│   ├── lower-thirds/
│   └── end-screen/
├── recordings/
│   └── session-date/
├── assets/
│   └── branding, music, transitions
```

---

## 🎯 Summary

Use OBS for:
- Time-saving real-time content production
- Custom webcam scenes in calls
- High-end streaming with branding and consistency

Only introduce when you're ready to scale content or deliver live events.

