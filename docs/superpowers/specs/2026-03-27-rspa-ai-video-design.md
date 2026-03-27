# RSPA AI Video Project — Design Spec

**Author:** Ed Crotty, Datacap Systems, Inc. (Claude Certified Architect)
**Date:** 2026-03-27
**Status:** Approved

---

## Overview

A bite-size (3-5 minute) video showcasing 5 things most people don't know AI can do, demonstrated live across Claude, ChatGPT, and Gemini. Targeted at RSPA members — retail technology VARs and ISVs. Produced using Cardboard (usecardboard.com) for AI-assisted editing. Can be broken into 5 individual social media clips.

## Audience

RSPA members and the broader retail technology channel — VARs, ISVs, and partners who have heard the AI buzz but haven't seen hands-on demonstrations of what's possible today. Tone is conversational, credible, and practical — not hype.

## Production Approach

**Modular Clips (Approach B):** Each demo recorded as a separate clip (~2-4 min raw each). Talking head intro + outro recorded separately. All clips uploaded to Cardboard with an assembly brief. Cardboard handles trimming, captions, transitions, and silence removal.

### Recording Setup

- **Demos 1-4:** Screen recording (Loom or similar TBD) with voiceover as you go. Each demo as its own recording for modularity and easy retakes.
- **Demo 5:** Phone camera footage pointed at a physical pinpad
- **Intro + Outro:** Talking head on phone camera (tripod/propped, decent lighting, eye-level)
- **Total raw recording time:** ~30-45 min including retakes
- **Output files:** Up to 7 clips (4 screen recordings, 1 phone pinpad video, 1 talking head intro, 1 talking head outro). Cardboard assembles them all.

### Aspect Ratio

- **Primary format:** 16:9 landscape (LinkedIn, YouTube, RSPA website)
- **Secondary cuts:** Ask Cardboard to also produce 9:16 vertical versions of the 5 individual clips for Instagram Reels / YouTube Shorts / TikTok if desired

---

## Video Structure

| # | Segment | Final Duration | Model | Description |
|---|---------|---------------|-------|-------------|
| 0 | Intro (talking head) | ~20 sec | — | Ed introduces himself and the premise |
| 1 | Photo → Explain | ~30-40 sec | Gemini | Photograph something, AI identifies and explains it |
| 2 | Multi-file → Report | ~45-60 sec | Claude | Upload 2-3 docs, AI analyzes and produces a report |
| 3 | Sketch → Image | ~30-40 sec | ChatGPT (GPT-4o) | Hand-drawn sketch turned into a polished image |
| 4 | Image → Video | ~30-40 sec | Gemini (Veo) | Generated image turned into a short video |
| 5 | Pinpad Debug (Live) | ~45-60 sec | Gemini Live | Live camera debugging a payment pinpad |
| 6 | Outro (talking head) | ~15 sec | — | Wrap-up with RSPA plug and meta AI editing callout |

**Total assembled runtime:** 3-5 minutes

**Pacing:** Demos 1, 3, 4 are quick "wow" moments. Demos 2 and 5 are the substantive business-value demos. Order builds from simple to complex, ending with the pinpad showstopper.

**Model distribution:** Claude x1, ChatGPT x1, Gemini x3 — reflects where multimodal strengths currently live.

---

## Demo Specifications

### Demo 1: Photo → Explain (Gemini)

- **Input:** Photo of an industry-relevant object (payment terminal, POS hardware, or general object)
- **Platform:** Gemini in the browser (screen-recorded). Take the photo on your phone first, then upload it to Gemini in the browser.
- **Prompt:** "What is this and how does it work?"
- **Wow moment:** Correct identification with useful context — no Googling or manuals
- **Prep:** Pick the object and take the photo ahead of time so it's ready to upload

### Demo 2: Multi-file Upload → Report (Claude)

- **Input:** 2-3 industry documents (vendor spec sheets, sales reports, or contracts)
- **Platform:** Claude (claude.ai)
- **Prompt:** "Compare these documents and give me a summary of the key differences" or "Analyze these reports and tell me what stands out"
- **Wow moment:** Structured report generated in seconds from multiple docs
- **Prep:** Have files on desktop. Do a dry run to verify the output is impressive.
- **Credential callout:** "I'm a certified architect on this platform — this is where it shines."

### Demo 3: Sketch → Image (ChatGPT / GPT-4o)

- **Input:** Hand-drawn sketch on paper — stick figures, labels, arrows (storefront, product concept, trade show booth, etc.)
- **Platform:** ChatGPT with GPT-4o image generation
- **Prompt:** "Turn this into a professional image"
- **Wow moment:** The dramatic jump from crude sketch to polished image
- **Prep:** Draw the sketch ahead of time. Simple but with labels for detail.

### Demo 4: Image → Video (Gemini Veo)

- **Input:** The image generated in Demo 3
- **Platform:** Gemini with Veo video generation
- **Prompt:** "Create a short video from this image"
- **Wow moment:** Still image comes to life — continuity from Demo 3 creates a 1-2 punch
- **Prep:** Save the ChatGPT output image from Demo 3 to your desktop before starting this demo
- **Important: Generation time.** Veo may take 30 seconds to a few minutes to generate. Two options: (1) narrate over the wait ("This takes a moment — Veo is actually generating a video from scratch..."), or (2) do a time-cut and let Cardboard splice to the result. Option 2 is cleaner for pacing.

### Demo 5: Live Pinpad Debug (Gemini Live)

- **Input:** Physical pinpad at desk, showing a status screen or error state
- **Platform:** Gemini Live (phone camera)
- **Prompt:** "I'm getting [X issue] on this device — can you help me figure out what's wrong?"
- **Wow moment:** AI sees the physical device, identifies it, reads the screen, gives real-time troubleshooting steps via conversation
- **Prep:** Most prep required. Pinpad powered on. Know what "problem" to present. Dry run mandatory — verify Gemini Live can see and identify the device.
- **Audience resonance:** Every VAR/ISV has been on the phone with support describing a pinpad screen. This replaces that experience.

---

## Reference Script

This is a bullet-point reference for talking naturally — not a teleprompter read. Ad-lib around these points.

### Intro (talking head, ~20 sec)

> "Hey, I'm Ed Crotty — I'm a Claude Certified Architect at Datacap Systems and I work with retail technology every day. I want to show you 5 things that most people have no idea AI can do right now. Not in the future. Right now. Let's go."

### Demo 1 — Photo → Explain

- "Let's start simple. I'm going to take a picture of [object] and ask AI what it is."
- *Upload photo, ask Gemini*
- "Boom — it nailed it. It knows what this is, what it does, and how it works. No Googling, no manuals."

### Demo 2 — Multi-file → Report

- "Now this one's a game-changer for anyone drowning in documents. I've got [2-3 files] here — I'm going to upload them all at once into Claude."
- *Upload files, type the prompt*
- "In about 10 seconds, it just did what would've taken me an hour. It read everything, compared them, and gave me a structured report."
- "This is Claude — I'm a certified architect on this platform and this is where it absolutely shines."

### Demo 3 — Sketch → Image

- "Alright, here's a fun one. I drew this on a piece of paper — yes, with stick figures."
- *Show the sketch to camera or upload it*
- "I'm going to ask ChatGPT to turn this into an actual image."
- *Upload, prompt, wait for result*
- "Look at that. From napkin sketch to this. Think about what that means for mocking up ideas, store layouts, marketing materials."

### Demo 4 — Image → Video

- "Now watch this — I'm taking that image we just created and asking Gemini to turn it into a video."
- *Upload image to Gemini, request video*
- "A drawing on a piece of paper just became a video. Let that sink in."

### Demo 5 — Pinpad Debug

- "Okay, this last one is the one that blew my mind when I first tried it. I've got a pinpad here at my desk."
- *Open Gemini Live, point phone camera at pinpad*
- "I'm going to have a live conversation with AI while it looks at my device and helps me debug it."
- *Walk through the troubleshooting conversation*
- "Think about what this means for field techs, for help desks, for anyone who's ever been on hold with support trying to describe what they're looking at."

### Outro (talking head, ~15 sec)

> "That's five things AI can do right now that most people have no idea about. And here's one more — this video was edited by AI too. If you want to learn more, check out the RSPA's resources on AI best practices. I'm Ed Crotty — go try this stuff."

---

## Recording Checklist

See [`script/talking-points.md`](../../../script/talking-points.md) for the full recording checklist and recommended recording order. Key points:

- Record each demo as its own separate clip for modularity
- Record demos 1-4 as individual screen recordings
- Record Demo 5 on phone camera
- Record intro + outro **last** — you'll sound more natural after completing all 5 demos
- Save the Demo 3 output image to desktop between Demo 3 and Demo 4

---

## Cardboard Assembly Brief

See [`cardboard/assembly-brief.md`](../../../cardboard/assembly-brief.md) for the full copy-paste prompts for Cardboard. Includes tips directly from the Cardboard team. Covers:
- Main video assembly (7 clips → 3-5 min, 16:9)
- Talking head as picture-in-picture overlay during screen recordings
- 5 individual social media clips (30-60 sec each) with structured reel-style prompts
- Optional 9:16 vertical cuts for Reels/Shorts/TikTok
- Pro tips: stacking edit requests, search-by-content for finding moments in raw footage, 1.5x pacing

---

## Deliverables

| Asset | Use |
|---|---|
| 1x full video (3-5 min) | Main piece — LinkedIn, RSPA, YouTube |
| 5x individual demo clips (30-60 sec) | Social media drip content (LinkedIn, Instagram, X) |
| 1x script/talking points doc | Reference for future videos or presentations |
| GitHub repo with all project files | Reusable template for future content projects |

---

## Meta Angle

The video itself is produced using AI (Cardboard). This is a 6th implicit demonstration of AI capability. Called out in the outro: "And here's one more — this video was edited by AI too."

---

## Open Decisions (Resolve Before Recording Day)

These are intentionally flexible — decide them when you sit down to prep:

| Decision | Options | When to Decide |
|---|---|---|
| Screen recording tool | Loom, OBS, QuickTime, macOS built-in | Day 1 (prep) |
| Demo 1 object | Payment terminal, POS hardware, random object | Day 1 (prep) |
| Demo 2 files | Vendor spec sheets, sales reports, or contracts (2-3 files) | Day 1 (prep) |
| Demo 3 sketch subject | Storefront, product concept, trade show booth, or anything visual | Day 1 (prep) |
| Demo 5 pinpad "problem" | Specific error code, connectivity issue, status screen anomaly | Day 1 (dry run) |
| Demo 4 wait handling | Narrate over the wait vs. time-cut | During recording |

## Retry Protocol

The whole point of Approach B (modular clips) is resilience. Guidelines:

- **If a demo goes smoothly:** Move on. Don't over-polish.
- **If AI gives a weak or wrong response:** Retry that demo as a fresh clip. Don't try to salvage it.
- **If Gemini Live can't see/identify the pinpad (Demo 5):** Try a different angle, better lighting, or a different "problem." If it still doesn't work after 2-3 attempts, pivot to a different live camera scenario (diagnosing a cable setup, identifying a piece of hardware, etc.).
- **If Veo takes too long (Demo 4):** Let it run, record the result later, Cardboard can splice it in.
- **General rule:** If you've tried something 3 times and it's not working, move on and come back to it. Don't burn your energy.

## Timeline

**Target:** Complete recording and assembly within the week of 2026-03-27.

| Day | Activity |
|---|---|
| Day 1 | Prep: gather docs, draw sketch, set up pinpad, dry run Demo 5 |
| Day 2 | Record: all demos + talking head (~30-45 min) |
| Day 2-3 | Upload to Cardboard, review AI edit, request adjustments |
| Day 3-4 | Final review, export full video + 5 individual clips |
| Day 4-5 | Push to LinkedIn/social, share with RSPA |
