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

### 2. Get Your Prompts (Two Workflows)

**Option A: AI Prefill (Recommended for Beginners)**
1. Upload the template to ChatGPT, Claude, Gemini, or Grok
2. Describe your vision in plain language:
   - "I want a woman dancing in a warehouse with the camera slowly circling her"
   - "Create a cyberpunk alley scene with neon lights and rain"
   - "Make a coffee shop conversation between two people"
3. Say **"prefill"**
4. AI fills out the entire template for you (environment, subjects, camera, sound, etc.)
5. Review the prefilled template, make any tweaks
6. Say **"run"** or **"generate"** to create all clip prompts

**Option B: Manual Fill (For Experienced Users)**
1. Open the template
2. Fill out the form sections yourself:
   - **CONTENT TYPE:** Your scene description
   - **DURATION:** Total video length (e.g., "42 seconds")
   - **CLIP LENGTH:** Individual clip duration (e.g., "6 seconds")
3. Upload the filled template to your AI
4. Say **"run"** or **"generate"** to create all clip prompts

**Why prefill exists:** Most people struggle to describe their vision technically. Prefill translates "woman walking through neon alley" into complete environment descriptions, locked subject details, camera movement plans, sound design, and negative prompts. It's like having a cinematographer translate your idea into technical specs.

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

**Think of these as different ways your clips connect:**

### 1. Continuous
The camera never stops moving. Like following someone through a building in one smooth shot. Great for making viewers feel like they're right there.

### 2. Invisible Cut
You hide the cuts so cleverly viewers don't notice. Tricks include:
- Whip the camera super fast (whip pan)
- Someone walks in front blocking the view
- Everything gets really blurry for a moment
- A bright flash

Feels like one shot, but you actually cut. Hollywood does this all the time.

### 3. Editorial Cut
You DO want people to notice the cut, but for a good reason:
- Cutting to a close-up to show emotion
- Showing what someone's looking at
- Jumping forward in time

Always has a reason and the audio keeps flowing smoothly between cuts.

**Key rule:** Keep the sound flowing between clips even if the picture cuts. Continuous audio makes cuts feel smooth.

---

## 🎥 Professional Cinematography (Cinematic Edition Only)

**Ever notice how Hollywood movies feel "right" but some YouTube videos feel "off"?** It's not the camera quality—it's these invisible rules. The Cinematic Edition enforces them automatically so your videos feel professional:

### 180-Degree Rule
**The "don't confuse your viewer" rule.**

Imagine a line between two people talking. The camera must stay on one side of that line:
- **Why?** If Person A is on the left, they should STAY on the left in every shot
- **What happens if you break it?** Viewer gets confused about where everyone is
- **Example:** In a conversation, if you jump to the other side of the line, it looks like the characters switched places
- **Exception:** You CAN cross the line if you show the camera moving across it on screen

### 30-Degree Rule
**The "make your cuts smooth" rule.**

When you cut from one angle to another of the same subject:
- The angle must change by at least 30 degrees
- **Why?** Less than 30° looks like a glitch, not an intentional cut
- **Example:** If you're filming someone's face, don't cut to almost the same angle—move the camera noticeably left/right/up/down
- **Exception:** Jump cuts (intentional glitchy cuts for time compression or style)

### Eyeline Match
**The "make conversations feel real" rule.**

When two characters look at each other:
- If Person A looks right → Person B must look left
- **Why?** Makes it look like they're actually looking at each other, not past each other
- **This is critical** for dialogue scenes feeling natural

### Match on Action
**The "hide cuts in movement" rule.**

Cut DURING an action, not before or after:
- **Good:** Cut while the door is opening (mid-swing)
- **Bad:** Cut before door opens or after it's already open
- **Why?** Your brain fills in the gap and doesn't notice the cut
- **Example:** Someone reaches for a cup → cut while hand is moving → next shot shows hand grabbing it

### Eye Trace
**The "guide where people look" rule.**

Lead the viewer's eyes from shot to shot:
- If someone exits the right side of the frame → start the next shot on the right side
- Use color: red jacket in one shot → red sign in the next shot draws the eye
- **Why?** Viewer's eyes don't have to search for what to look at

**The magic:** These rules are why Hollywood films feel effortless to watch. The Cinematic template follows them automatically—you just describe your scene.

---

## 📋 Lite Edition — What Makes It Work

**The Lite Edition prevents common AI video problems automatically.** You don't have to think about any of this—just describe your idea:

### What It Locks Down
1. **Same "DNA" for every clip** — Uses the same seed number so your character doesn't morph into a different person
2. **Exact copy-paste descriptions** — Repeats environment and character details word-for-word so AI doesn't "forget"
3. **No new stuff appearing randomly** — First clip establishes everything that exists. No magic props appearing later
4. **Camera always knows what to do** — Every clip states how the camera moves (or "stays still")

### Problems It Prevents
5. **No fading to black between clips** — Biggest "this is AI slop" giveaway. Clips end with visible, lit scenes
6. **Faces don't change** — Your character's face, hair, clothes stay identical across all clips
7. **People don't randomly shrink or grow** — Character size stays consistent
8. **Lighting doesn't flicker around** — Lights stay in the same place with the same color
9. **No awkward silence in conversations** — When people talk, they actually talk (80% of the clip time)
10. **Every prompt is complete** — No "same as above" shortcuts that confuse the AI

### What You Get
- **One prompt per clip** — Click, copy, paste into your video AI. That's it.
- **No blanks or confusing references** — Each prompt is complete and standalone
- **Flexible locations** — Same room the whole time, gradual changes, or completely different locations per clip

**Bottom line:** Describe your scene in plain English. The template handles all the technical stuff that makes videos look professional instead of "AI-generated."

---

## 🎥 Cinematic Edition — Camera System

**The Cinematic Edition lets you control HOW the camera moves with precision:**

**Camera Movement Speed:**
- Camera speeds up/slows down gradually (like a real camera operator)
- Max speed limits prevent jarring movement
- Changes happen smoothly over 1-2 seconds

**Camera Weight/Feel (Inertia 0–1):**
- **0** = Robotic, instant response (like a drone)
- **0.5** = Natural, slight delay (like a skilled camera operator)
- **1** = Heavy, smooth, cinematic (like a professional steadicam)

**Damping:**
Controls how quickly movement stops:
- High damping = smooth, controlled stops
- Low damping = abrupt stops

**Easing (how movement speeds up/slows down):**
- Linear = constant speed
- Ease-in = starts slow, speeds up
- Ease-out = starts fast, slows down
- Ease-in-out = smooth on both ends
- Sinusoidal = very smooth, wave-like

**You don't have to understand all this to use it**—the prefill feature sets good defaults. But if you want fine control over camera feel, these options are there.

---

## ✂️ Cinematic Cuts (Both Versions)

**You CAN cut between clips—but every cut needs a reason.**

**Ways to hide cuts (make them invisible):**
- **Whip pan** — Camera swings super fast, cut happens during the blur
- **Someone blocks the camera** — Person/object moves in front, cut while view is blocked
- **Motion blur peak** — Everything's really blurry from fast movement, cut in the blur
- **Light flash** — Bright light, cut during the flash
- **Match cut** — Cut when two shots look similar (same shape, same motion, same framing)

**Editorial cuts (you WANT people to notice):**
- **Inserts** — Quick 1-3 second shots showing details (phone screen, clock, etc.)
- Must have a reason (show emotion, show what someone's looking at, jump forward in time)

**Every cut must have:**
1. **A reason** — Why are we cutting here?
2. **Camera plan** — Does camera position continue or reset?
3. **Sound bridge** — How does audio connect across the cut?

**Remember:** Even when you cut the picture, keep the audio flowing smoothly. That's the secret to making cuts feel natural.

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

## 🎨 The Reference Image Method (2026 - Cinematic Only)

**Problem:** AI sometimes "forgets" what your character looks like between clips. Face changes slightly, clothes shift colors, proportions drift.

**Solution:** Give the AI a reference photo to look at for EVERY clip.

**How it works:**

**Setup:**
1. Get one really good photo of your subject (character, product, whatever)
   - Front-facing, well-lit, high quality
   - Shows the look you want: lighting, clothing, style
2. Keep this same photo for the entire video

**Making clips:**
1. **Clip 1:** Feed AI the reference photo + your text description → get video
2. Save the last frame from Clip 1
3. **Clip 2:** Feed AI BOTH the reference photo + last frame + text → get video
4. Keep doing this for all clips

**Why this works:**
- Reference photo keeps your subject looking identical (60-80% better than without it)
- Last frame keeps the motion smooth
- AI has two images to guide it instead of just text

**What you need:**
- Good reference photo (front-facing, well-lit, 1080p or better)
- Same photo used for EVERY single clip
- No action shots—neutral pose works best

**Tools that support this (as of Feb 2026):**
- ✅ Sora 2
- ✅ Veo 3.1
- ✅ Runway Gen-4.5
- ✅ Kling 2.6
- ✅ Pika 2.5

(Check if your tool supports reference images—this feature is rolling out across platforms)

---

## 🎵 Sound Design

### Lite Edition
**Simple 5-part system for each clip:**

- **Music:** What's playing or None (with volume %)
- **Ambient:** Background sounds like traffic, wind, room tone (with volume %)
- **Foley:** Specific sounds synced to actions—footsteps at 2 seconds, door slam at 4.5 seconds (with volume %)
- **Dialogue:** Who says what and when
  - Format: Person A: "Hello there" (0.2s-2.1s)
  - Conversations automatically fill 80%+ of clip time (no awkward pauses)
- **Transitions:** How sound connects to the next clip (smooth, crossfade, etc.)

### Cinematic Edition
**Professional multi-layer system:**

Same as Lite but with more control:
- **Music sync** — Sync cuts to beat, control emotional emphasis
- **Ambient transitions** — Exactly how one environment sound fades into another
- **Foley precision** — Action-synced effects with frame accuracy
- **Advanced transitions** — J-cuts (audio starts before video), L-cuts (audio continues after video), beat sync
- **Notes section** — Special sync rules, emotional cues

**Both versions keep audio flowing smoothly between clips—that's what makes everything feel connected.**

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
