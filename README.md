# Claude Animated Shorts

[![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg)](LICENSE)
[![Maintainer](https://img.shields.io/badge/Maintainer-Abdullah%20Formuli-orange.svg)](https://github.com/authrain-cloud-abdullahformuli)
[![Standard](https://img.shields.io/badge/Standard-Agent%20Skills-green.svg)](https://agentskills.io)
[![Stack](https://img.shields.io/badge/Stack-Remotion%20%7C%20Three.js%20%7C%20Python-blueviolet.svg)](#whats-inside)

Autonomous Claude Code skill for producing viral 55–70s vertical animated story shorts. Renders 2D cartoon characters in vivid 3D worlds with ink outlines, painted environments, lens blur, dynamic gliding cameras, procedural march scores, and custom sound design.

Everything is rendered deterministically using Three.js inside [Remotion](https://www.remotion.dev/) on your local machine — with **zero third-party AI video APIs**.

---

## 📦 What's Inside

| Path | Description |
|---|---|
| `SKILL.md` | The core agent skill: end-to-end production pipeline, composition rules, timing standards, and QA checks |
| `templates/bridge/` | Complete production source code: 3D scene shaders, camera choreography (`story.ts`), ink passes, lens blur, and lighting |
| `templates/audio/` | Procedural sound design: synthesized SFX, orchestral march score generator, loudness normalization, and audio ducking |
| `templates/scripts/` | Frame-by-frame QA helpers, contact sheet generators, side-by-side comparators, and automated render stitches |
| `references/STYLE_BIBLE.md` | Comprehensive visual and pacing formula analyzed across 20 reference shorts |
| `references/reports/` | Empirical analysis reports: motion curves, scene depth, texture shaders, character meshes, lighting, and color grading |
| `references/frames/` | 38 full-resolution reference keyframes (540×960) for style calibration |
| `references/sheets/` | 20 master contact sheets (60 frames each, 1,200 total frames) documenting shot pacing |

---

## ⚡ Quick Install

### Option 1: Via Claude Code

Paste this directly into Claude Code:

```text
Install this skill for me: https://github.com/authrain-cloud-abdullahformuli/claude-animated-shorts
```

### Option 2: Manual Installation

Clone directly into your Claude skills directory:

```bash
git clone https://github.com/authrain-cloud-abdullahformuli/claude-animated-shorts "$HOME/.claude/skills/cartoon-3d-short"
```

### Prerequisites

- [Node.js 22+](https://nodejs.org)
- Python 3.10+
- [FFmpeg](https://ffmpeg.org)
- [Remotion](https://www.remotion.dev/) with `@remotion/three`

---

## 🎬 How It Works

Once installed in Claude Code, trigger the workflow:

```text
Use the cartoon short skill and make a short about the 1831 Broughton Suspension Bridge
```

The skill executes an autonomous 7-step pipeline:

```
  ┌────────────────────────────────────────────────────────┐
  │                 ANIMATION PIPELINE                     │
  ├────────────────────────────────────────────────────────┤
  │ 1. RESEARCH     Historical cause & physical analogy    │
  │ 2. SCRIPT       Pacing: Hook → Action → Snap → Conseq  │
  │ 3. VOICE        Narration + word-level words.json sync │
  │ 4. SCENE        Three.js shaders, ink outlines, meshes │
  │ 5. CAMERAS      Dynamic gliding paths & impact kicks   │
  │ 6. AUDIO DSP    Synthesized SFX + march music mixing   │
  │ 7. QA AUDIT     Frame verification against 38 refs     │
  └────────────────────────────────────────────────────────┘
```

Exports a crisp 2K vertical master: **1440×2560 @ 30 fps** (`--scale 1.3333`).

---

## 🛡 Maintenance & Governance

This repository is maintained solely by:

- **[Abdullah Formuli](https://github.com/authrain-cloud-abdullahformuli)** (`authrainmedia@gmail.com`)

Maintained solely by Abdullah Formuli. No external contributions accepted.

---

## 📄 License

[MIT](LICENSE) © 2026 Abdullah Formuli. Reference frames and sheets are included for educational and stylistic comparison.
