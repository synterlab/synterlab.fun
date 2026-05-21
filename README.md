<div align="center">
  <img src="https://synterlab.space/og-image.png" alt="SYNTERLAB" width="100%" style="border-radius:8px"/>
</div>

<br/>

<div align="center">

# SYNTERLAB

**Professional audio plugins for DAW producers.**

[![Live Site](https://img.shields.io/badge/Live%20Site-synterlab.space-white?style=flat-square&logo=safari&logoColor=black)](https://synterlab.space)
[![Follow on X](https://img.shields.io/badge/Follow-%40Synterspace-black?style=flat-square&logo=x&logoColor=white)](https://x.com/Synterspace)
[![License](https://img.shields.io/badge/License-Proprietary-333?style=flat-square)](https://synterlab.space)
[![Plugins](https://img.shields.io/badge/Plugins-6-white?style=flat-square)](#plugins)
[![Formats](https://img.shields.io/badge/Formats-VST3%20%7C%20AU%20%7C%20AAX-555?style=flat-square)](#compatibility)

</div>

---

## Overview

SYNTERLAB makes precision audio plugins for professional DAW producers. Six instruments built from the ground up — native, offline, and loading in under 200ms.

No subscriptions. No iLok. Yours forever.

**Live at [synterlab.space](https://synterlab.space)**

---

## Plugins

| Plugin | Category | Description |
|---|---|---|
| **SynTuner Pro** | Tuner | Chromatic tuner, plus/minus 1 cent accuracy, 8 historical temperaments |
| **HarmonicDrift** | Pitch Processor | Vintage pitch manipulation and harmonizer for expressive layering |
| **PolyString** | String Engine | Multi-articulation bowed and plucked string synthesis engine |
| **PercMatrix** | Percussion | World percussion drum machine with deep velocity and round-robin sampling |
| **AirFlute** | Woodwind Synth | Cinematic woodwind synthesizer with breath modeling and vibrato control |
| **ResoChord** | Chord Engine | Resonant chord and overtone generator for lush harmonic textures |

---

## Formats and Compatibility

**VST3 / AU / AAX / Standalone**

Works with: Ableton Live, FL Studio, Logic Pro, Pro Tools, Reaper, Cubase, Studio One, Bitwig

---

## Pricing

| Plan | Price | Includes |
|---|---|---|
| Free | $0 | SynTuner Lite — basic chromatic tuner |
| Essential | $29 | SynTuner Pro + 2 plugins of choice, lifetime license |
| **Studio** | **$69** | All 6 plugins, VST3/AU/AAX, lifetime updates, priority support, future plugins |

[Get Studio Bundle](https://synterlab.space/#pricing)

---

## Tech Stack

This landing page is a **single self-contained HTML file** with no runtime dependencies except Google Fonts.

```
artifacts/synterlab/index.html   — complete landing page (CSS + JS inline)
```

- **Font**: Space Grotesk + Space Mono (Google Fonts)
- **Interactive demos**: Web Audio API (microphone pitch detection, polyphonic synth)
- **Tuner**: Autocorrelation pitch detection with live oscilloscope and spectrum analyzer
- **Synth**: Polyphonic sawtooth + filter synthesizer with reverb, chord presets, QWERTY keyboard
- **Animations**: IntersectionObserver scroll reveal, CSS keyframe EQ bars, canvas particles
- **Mobile**: Touch-enabled piano keyboard, responsive layout

---

## Development

```bash
pnpm --filter @workspace/synterlab run dev
```

Served at the port defined by the `PORT` environment variable.

---

## License

Proprietary. All rights reserved. (c) 2025 SYNTERLAB.

---

<div align="center">
  <a href="https://synterlab.space">synterlab.space</a> &nbsp;|&nbsp;
  <a href="https://x.com/Synterspace">@Synterspace on X</a>
</div>
