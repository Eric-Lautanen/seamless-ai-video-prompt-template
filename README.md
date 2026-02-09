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
- When you want professional-looking output without "AI slop" tells

**Features:**
- Streamlined input form (just 3 fields to start)
- Simplified camera controls (no math required)
- Built-in slop prevention (no fades to black, no morphing faces, no awkward pauses)
- Same-seed continuity lock
- Fast prompt generation
- One-click copyable prompts per clip
- Automatic dialogue timing (80% rule for conversations)

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
- **NEW:** 180-degree rule enforcement
- **NEW:** 30-degree rule for angle changes
- **NEW:** Eyeline match for character interactions
- **NEW:** Match on action editing
- **NEW:** Eye trace for viewer attention control
- **NEW:** Reference image workflow (2026 best practice)
- **NEW:** Dual-image input method (60-80% less identity drift)

**Use when:** You need maximum creative control and cinematic polish with professional spatial continuity.

---

## 🚀 Quick Start (3 Steps)

### 1. Choose Your Template
- **Lite Edition:** `seamless-ai-video-prompt-lite.txt`
- **Cinematic Edition:** `seamless_video_prompt_template.txt`

### 2. Fill the Input Form
**Lite Edition requires only 3 fields:**
- **CONTENT TYPE:** Describe your scene (the more detail, the better)
  - Example: "A woman dances in a warehouse. One continuous camera movement circling around her as she dances."
- **DURATION:** Total video length
  - Example: "42 seconds"
- **CLIP LENGTH:** Individual clip duration (most tools support 6 or 10 seconds)
  - Example: "6 seconds"

Then paste the template into ChatGPT, Claude, Gemini, or Grok and say:
- **"prefill"** — AI fills the template but doesn't generate clips yet (review/edit first)
- **"run"** or **"generate"** — AI generates all clips immediately

**Why prefill exists:** Most people struggle to describe their vision technically. Prefill translates "woman walking through neon alley" into complete environment descriptions, locked subject details, camera movement plans, sound design, and negative prompts. Review it, tweak it, then generate.

### 3. Generate Your Video (Last Frame Method)
- Generate Clip 1 as text-to-video or text-to-image → video
- Export the last frame from your video editor (NOT a screenshot)
- Generate Clip 2 as image-to-video using that exported frame
- Repeat for all clips
- Stitch clips together

**Result:** A professional sequence with fluid motion, intentional transitions, and continuous sound.

**Pro Tips for Bulletproof Continuity**

- Always describe the *exact same* outfit, hair, scar, freckles—word-for-word. AI forgets if you paraphrase.
- If the face drifts after clip 3? Regenerate just that one using the last good frame. Don't chain garbage.
- Test with 12 seconds first. If it breaks early, the whole thing will.
- Use 24fps, not 30. Feels more cinematic, less TikTok.
- Sound? Add it last. Most generators still choke if you bake audio in.
- Seed 0? Skip it. Some tools treat zero as "random"—always start at 1.

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

## 🎥 Professional Cinematography (Cinematic Edition Only)

The Cinematic Edition enforces Hollywood spatial continuity rules:

### 180-Degree Rule
Camera stays on one side of the "action axis" (imaginary line between subjects):
- Prevents spatial disorientation
- Characters remain in consistent left/right relationship
- **Example:** In a conversation, if Person A is on the left, they stay left in every shot
- **Exception:** You can cross the line if you show the camera movement on screen

### 30-Degree Rule
When cutting to the same subject from a different angle:
- Angle must change by at least 30 degrees
- Less than 30° creates jarring "jump cut" effect
- **Exception:** Intentional jump cuts for stylistic/time-compression effect

### Eyeline Match
When characters look at each other:
- If Subject A looks right, Subject B must look left
- Maintains spatial logic and eye contact illusion
- Critical for natural-feeling conversations

### Match on Action
Cut during movement, not between movements:
- **Example:** Cut while door is opening, not before or after
- Creates seamless, invisible transitions
- Viewer's brain fills in the gap

### Eye Trace
Guide viewer attention from shot to shot:
- Use color, composition, or blocking
- Place important elements where the viewer is already looking
- **Example:** Subject exits frame-right → next shot starts frame-right

These rules are why Hollywood films feel smooth while amateur videos feel "off." The Cinematic template enforces them automatically.

---

## 📋 Lite Edition — What Makes It Work

The Lite Edition enforces these rules automatically so you don't have to think about them:

### Continuity Locks
1. **Same seed for ALL clips** — Auto-generated if you don't provide one (guarantees visual consistency)
2. **Word-for-word repetition** — Environment and subject descriptions copied exactly every clip
3. **No new elements after Clip 1** — What's visible in the first clip is ALL that exists (prevents random props appearing)
4. **Explicit camera instructions** — Every clip states movement or "remains completely static"

### Slop Prevention (Built-in)
5. **No fades to black/white** — Clips end with visible, well-lit frames (biggest AI slop giveaway)
6. **No identity drift** — Facial features, clothing, proportions locked across all clips
7. **No scale changes** — Subject size relative to frame stays consistent
8. **No lighting drift** — Light sources and color temperature locked (unless you use EVOLVING mode)
9. **Dialogue timing** — Multi-character conversations fill 80%+ of clip duration (no awkward pauses)
10. **Full negative prompts** — Every clip gets complete prevention list (no shortcuts like "same as above")

### Output Quality
- **One artifact per clip** — Single-click copy, paste directly into your video AI tool
- **Complete prompts** — No references, no blanks, no abbreviations
- **Environment flexibility** — Choose STATIC (same setting), EVOLVING (gradual changes), or PER-CLIP (different locations)

**Camera movement is flexible:** You control timing. Specify static holds, continuous movement, or any combination in your CONTENT TYPE description. The template adapts to your vision.

**No camera math required.** Just follow the template and describe shots simply: "push-in," "orbit left," "continuous right movement," "static."

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
2. Export final frame from your video editor (not a screenshot)
3. Generate Clip 2 using that exact frame as the starting image
4. Repeat for all subsequent clips
5. Stitch sequence in your editor
6. Apply sound design

**Critical:** Use the actual exported frame from your editor, not a screenshot. This preserves exact color grading, resolution, and compression artifacts that help the AI maintain consistency.

**Works with both versions.**

---

## 🎨 The Reference Image Method (2026 Best Practice - Cinematic Only)

Advanced workflow for superior identity consistency using dual-image input:

**Setup:**
1. Create or source a high-quality reference image showing your subject with desired lighting, clothing, and style
2. Use this SAME reference image for ALL clips

**Generation:**
1. **Clip 1:** Reference Image + Text Prompt → Video
2. Export final frame
3. **Clip 2:** Reference Image + Final Frame + Text Prompt → Video
4. Repeat for all clips

**Results:**
- 60-80% reduction in identity drift
- Locked color grading and lighting
- Consistent facial features and proportions
- Works best with frontal, well-lit reference images

**Platform Support (Feb 2026):**
- ✅ Sora 2 (dual reference + final frame)
- ✅ Veo 3.1 (reference + prompt)
- ✅ Runway Gen-4.5 (multi-image input)
- ✅ Kling 2.6 (reference + continuity)
- ✅ Pika 2.5 (image conditioning)

Check your platform's documentation for latest features.

---

## 🎵 Sound Design

### Lite Edition
Simple structured system:
- **Music:** (description or None / volume %)
- **Ambient:** (environment or None / volume %)
- **Foley:** (specific sounds with timing / volume %)
- **Dialogue:** (Subject name: "exact line" (0.2s-5.8s) OR None)
  - Multi-subject conversations automatically fill 80%+ of clip duration
- **Transitions:** (how sound connects between clips)

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
- Grok Imagine (6/10 second clips)

**Audio:**
- Runway
- Kling
- ElevenLabs
- Suno

---

## 📊 Version Comparison

| Feature | Lite Edition | Cinematic Edition |
|---------|-------------|-------------------|
| **Setup Time** | 2 minutes (3 fields) | 15–30 minutes |
| **Camera Controls** | Simple descriptions | Precise physics + spatial rules |
| **Camera Timing** | User-controlled | Structured defaults |
| **Sound Design** | 5-field structured | Professional 3-layer |
| **Slop Prevention** | Built-in (10+ rules) | Built-in + advanced |
| **Dialogue Timing** | Auto 80% rule | Manual control |
| **Output Format** | 1 artifact per clip | 1 artifact per clip |
| **Cut Motivations** | Simplified | Detailed justification |
| **Spatial Continuity** | Basic | 180°/30° rules + eyeline match |
| **Advanced Editing** | ❌ | Match on action + eye trace |
| **Reference Images** | ❌ | ✅ Dual-image workflow |
| **Identity Drift Prevention** | Seed + word-for-word | Seed + reference image (60-80% better) |
| **Best For** | Social, ads, tests | Films, commercials, docs |
| **Learning Curve** | Minimal | Moderate |
| **Output Quality** | Clean & cinematic | Maximum polish |
| **Token Efficiency** | High | Moderate |

---

## 🎯 Common Use Cases

### Lite Edition Examples
- **30-second product demo** (5 clips × 6 seconds)
- **TikTok/Reel with dialogue** (3 clips × 10 seconds, 80% dialogue rule auto-applied)
- **Concept test for client** (prefill → review → generate)
- **Social ad with call-to-action** (static environment, continuous camera movement)

### Cinematic Edition Examples
- **60-second narrative short** (10 clips × 6 seconds, 180° rule enforced)
- **Two-character conversation** (eyeline match + match on action + reference images for identity lock)
- **Action sequence with VFX** (particle state tracking + invisible cuts on motion blur peaks)
- **Product commercial with camera choreography** (precise dolly moves + eye trace for viewer attention)
- **Music video with location changes** (PER-CLIP environment mode + reference image for artist consistency)

### When to Use Prefill
- "I want a cyberpunk alley scene but don't know how to describe the neon lights"
- "Make a coffee shop conversation but I'm not sure about camera angles"
- "Create a space shuttle approach sequence" (see template for exact example)
- "I have a great idea but don't know cinematography terminology"

### When to Use Reference Image Method (Cinematic)
- Character-driven narratives requiring facial consistency
- Product videos where brand colors must stay exact
- Any sequence where identity drift would break immersion
- Multi-location scenes requiring consistent subject appearance
- Professional client work requiring pixel-perfect brand consistency

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
