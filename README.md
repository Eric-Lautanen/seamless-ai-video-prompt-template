# Seamless AI Video Prompt Generator

**Two versions. One goal: Cinematic continuity.**

Generate professional AI videos with seamless transitions and frame-accurate continuity. Choose the version that matches your workflow:

- **Lite / Fast Edition** — Quick prompts, reliable results, perfect for social content and rapid iteration
- **Cinematic Edition** — Full Hollywood-grade camera physics, motivated cuts, and professional sound design

No jarring jumps, no random resets, no broken audio. Just smooth motion, intentional transitions, and continuous flow.

Note: Regenerate clips when needed for pixel-accurate continuity.

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![AI Video](https://img.shields.io/badge/AI-Video%20Generation-blue)](https://github.com/Eric-Lautanen/seamless-ai-video-prompt-template)

---

## 🎯 Which Version Should You Use?

### Lite / Fast Edition
**Best for:**
- Social media videos (TikTok, Reels, Shorts)
- Product demos and ads
- Concept tests and client previews
- Rapid iteration and quick turnarounds
- When you need reliable results without deep technical setup
- When tokens are low and you still need 12–30 seconds of usable footage

**Features:**
- Streamlined input form
- Simplified camera controls (no math required)
- Same-seed continuity lock
- Fast prompt generation
- Clean cinematic output

**Use when:** Speed and reliability matter more than fine-tuned camera physics.

---

### Cinematic Edition
**Best for:**
- Full narrative productions
- High-end commercial work
- Complex camera choreography
- Motivated editorial cuts
- Professional sound design integration
- Films, documentaries, music videos

**Features:**
- Precise camera physics (acceleration, inertia, damping)
- Hollywood-grade cut motivations
- Three-layer sound design system
- Frame-perfect continuity controls
- VFX integration support

**Use when:** You need maximum creative control and cinematic polish.

---

## 🚀 Quick Start (3 Steps)

### 1. Choose Your Template
- **Lite Edition:** `seamless-ai-video-prompt-lite.txt`
- **Cinematic Edition:** `seamless_video_prompt_template.txt`

Fill out the template fields at the top, or ask an AI to fill it based on your vision.

### 2. Give It to an AI
Paste the filled template into ChatGPT, Claude, Gemini, or Grok and say:

"Please use this template to generate video prompts with seamless continuity."

### 3. Generate Your Video (Last Frame Method)
- Generate Clip 1 as text-to-video or text-to-image → video
- Export the last frame from your editor (NOT a screenshot)
- Generate Clip 2 as image-to-video using that frame
- Repeat for all clips
- Stitch clips together

**Result:** A professional sequence with fluid motion, intentional transitions, and continuous sound.

**Pro Tips for Bulletproof Continuity**

- Always describe the *exact same* outfit, hair, scar, freckles—word-for-word. AI forgets if you paraphrase.
- If the face drifts after clip 3? Regenerate just that one using the last good frame. Don’t chain garbage.
- Test with 12 seconds first. If it breaks early, the whole thing will.
- Use 24fps, not 30. Feels more cinematic, less TikTok.
- Sound? Add it last. Most generators still choke if you bake audio in.
- Seed 0? Skip it. Some tools treat zero as “random”—always start at 1.

---

## 🎬 Continuity Modes (Both Versions)

### 1. Continuous
One uninterrupted camera move. Best for immersive tracking shots.

### 2. Invisible Cut
Hidden Hollywood-style cuts using whip pans, occlusion, motion blur, or light flashes. Feels like one shot.

### 3. Editorial Cut
Intentional cutaways, inserts, or montage beats. Used for emphasis and pacing. Always motivated and sound-bridged.

**Key principle:** Sound continuity always takes priority over visual continuity.

---

## 📋 Lite Edition — Core Rules

The Lite Edition follows five simple rules for reliable continuity:

1. Break video into 6-second clips
2. Use the SAME SEED for every clip (if available)
3. End EVERY clip with the MAIN SUBJECT:
   - Fully visible
   - Centered
   - Unchanged
4. Repeat the MAIN SUBJECT DESCRIPTION word-for-word in every clip
5. Audio continuity overrides visual continuity

**No camera math required.** Just follow the template and describe shots simply: "push-in," "orbit," "follow," "static."

---

## 🎥 Cinematic Edition — Camera System

The Cinematic Edition includes precise physics controls:

**Camera Physics:**
- Linear acceleration ≤ 2 ft/sec²
- Rotational acceleration ≤ 5°/sec²
- Motion changes blended over 1–2 sec

**Camera Inertia (0–1):**
- 0 = robotic
- 0.5 = natural
- 1 = heavy cinematic

**Damping:**
- Rotation damping
- Dolly damping

**Easing:**
- Linear, Ease-in, Ease-out, Ease-in-out, Sinusoidal

---

## ✂️ Cinematic Cuts (Both Versions)

Cuts are allowed — but never accidental.

**Allowed methods:**
- Whip pan
- Full-frame occlusion
- Motion blur peak
- Light flash
- Match cut (shape, motion, framing)
- Editorial inserts (1–3 sec max)

Every cut must specify:
- Motivation
- Camera continuity (preserved or reset)
- Audio bridge

---

## 🎯 The Last Frame Method

This technique eliminates AI randomness and preserves camera, lighting, and framing:

1. Generate Clip 1
2. Export final frame from editor (not screenshot)
3. Generate Clip 2 using that frame
4. Repeat for all clips
5. Stitch sequence
6. Apply sound design

**Works with both versions.**

---

## 🎵 Sound Design

### Lite Edition
Simple three-field system:
- Music (description / volume %)
- Ambient (environment / volume %)
- Foley (key sounds)
- Sound Transitions (continuous / crossfade / J-cut / L-cut)

### Cinematic Edition
Professional three-layer system with detailed control:
- Music (track / volume % / sync)
- Ambient (environment / volume % / transition type)
- Foley (specific action-synced effects)
- Sound Transitions (crossfade, J-cut, L-cut, beat sync)
- Notes (sync rules, emotional emphasis)

---

## 🛠️ Compatible Platforms

**Prompt Generation:**
- ChatGPT
- Claude
- Gemini
- Grok

**Video Generation:**
- Runway
- Pika
- Luma Dream Machine
- Kling
- Haiper
- Stability AI
- Sora / Veo (text-only)
- Grok Imagine

**Audio:**
- Runway
- Kling
- ElevenLabs
- Suno

---

## 📊 Version Comparison

| Feature | Lite Edition | Cinematic Edition |
|---------|-------------|-------------------|
| **Setup Time** | 5 minutes | 15–30 minutes |
| **Camera Controls** | Simple descriptions | Precise physics |
| **Sound Design** | Basic 3-field | Professional 3-layer |
| **Cut Motivations** | Simplified | Detailed justification |
| **Best For** | Social, ads, tests | Films, commercials, docs |
| **Learning Curve** | Minimal | Moderate |
| **Output Quality** | Clean & cinematic | Maximum polish |

---

## 📄 License

MIT License — free for personal and commercial use.

---

## 🤝 Contributing

Contributions welcome:
- New examples for both versions
- Platform-specific presets
- Action / trailer cut recipes
- Documentation improvements

---

## 🏆 Credits

Built using techniques inspired by professional cinematography, film editing, and sound design — adapted for modern AI video generation.

**Star the repo if this helps you ship cinematic AI videos** ⭐
