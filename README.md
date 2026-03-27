# RSPA AI Video — "5 Things You Didn't Know AI Can Do"

A bite-size (3-5 min) video project showcasing 5 live AI demos across Claude, ChatGPT, and Gemini. Targeted at RSPA members and retail technology professionals.

**Author:** Ed Crotty, Datacap Systems, Inc. — Claude Certified Architect

## The 5 Demos

| # | Demo | AI Model |
|---|------|----------|
| 1 | Photo → AI explains it | Gemini |
| 2 | Multi-file upload → AI-generated report | Claude |
| 3 | Hand-drawn sketch → AI-generated image | ChatGPT (GPT-4o) |
| 4 | Image → AI-generated video | Gemini (Veo) |
| 5 | Live camera → AI-guided pinpad debugging | Gemini Live |

## Production Stack

- **Screen recording:** Loom (or similar)
- **Video editing/assembly:** [Cardboard](https://www.usecardboard.com/) (AI-powered)
- **Target format:** 1x full video (3-5 min) + 5x individual clips for social media

## Repo Structure

```
.
├── README.md
├── docs/
│   └── superpowers/
│       └── specs/
│           └── 2026-03-27-rspa-ai-video-design.md   # Full design spec
├── script/
│   └── talking-points.md          # Reference script for recording
├── assets/
│   ├── sketch/                    # Hand-drawn sketch photos (Demo 3 input)
│   ├── docs-for-upload/           # Sample docs for Demo 2
│   └── outputs/                   # AI-generated images/videos from demos
├── recordings/
│   └── raw/                       # Raw screen recordings & phone clips
├── cardboard/
│   └── assembly-brief.md          # Prompt/instructions for Cardboard
└── final/
    ├── full-video/                # Final assembled 3-5 min video
    └── clips/                     # Individual demo clips for social
```

## Quick Start

1. Read the [design spec](docs/superpowers/specs/2026-03-27-rspa-ai-video-design.md) for the full plan
2. Review the [talking points](script/talking-points.md) for your recording reference
3. Run through the [recording checklist](script/talking-points.md#recording-checklist)
4. Record, upload to Cardboard, ship it

## Links

- [RSPA AI Best Practices Article](https://www.gorspa.org/ai-misconceptions-best-practices/)
- [Cardboard — AI Video Editor](https://www.usecardboard.com/)
