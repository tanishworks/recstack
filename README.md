# RECSTACK
> Built for creators who care about performance, control, and clean audio workflows.

A minimal, performance-focused recording stack for Linux.

Designed for low overhead screen capture with separate microphone recording, enabling better control during post-processing.

---

## Why not OBS?

OBS is powerful, but often overkill for simple recording setups and can introduce unnecessary overhead.

recstack focuses on:
- minimal resource usage
- smooth capture via gpu-screen-recorder
- separate mic recording for flexible editing

---

## Features

- GPU-accelerated screen recording
- Separate microphone capture
- Lightweight CLI workflow
- Low CPU/GPU usage

---

## Dependencies

- gpu-screen-recorder
- PipeWire / PulseAudio
- pactl
- parecord
- ffmpeg (optional, for merging/post-processing)

---

## Usage

### Clone
```bash
git clone https://github.com/tanishworks/recstack
cd recstack
```
### Make an executable
```bash
chmod +x recorder
```
### Run
```bash
./recorder
```
## Output
`name.mkv` — screen + system audio
<br />
`name.wav` — microphone audio
