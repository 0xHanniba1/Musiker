# Musiker

A skeuomorphic web-based music player with Web Audio API.

## Features

- **Waveform Visualization** — Real-time waveform display with click-to-seek
- **Playback Controls** — Play/pause, stop, previous, next
- **Loop Modes** — List repeat, single repeat, shuffle
- **Level Meters** — Real-time L/R channel visualization
- **EQ Presets** — Normal, Bass Boost, Vocal, Rock
- **Volume Control** — Adjustable gain
- **Drag & Drop** — Drop audio files directly onto the player
- **File Info** — View sample rate, channels, duration, file size

## Supported Formats

MP3, WAV, FLAC, OGG, AAC (browser-dependent)

## Usage

1. Open `index.html` in a modern browser
2. Drag an audio file onto the player, or click "Browse File"
3. Use the jog wheel or control buttons to play/pause
4. Click on the waveform to seek
5. Press EFFECT to change EQ presets
6. Press SYSTEM to view file metadata

## Keyboard Shortcuts

| Key | Action |
|-----|--------|
| `Space` | Play / Pause |
| `←` | Seek -5s |
| `→` | Seek +5s |

## Tech Stack

- HTML5 / CSS3 / Vanilla JavaScript
- Web Audio API (AudioContext, AnalyserNode, BiquadFilterNode)
- Single file, no dependencies

## License

MIT
