# Seamless AI Video Prompt Generator

**Create perfect single-take AI video sequences with frame-perfect continuity**

Generate professional AI videos where every clip flows seamlessly into the next. No jarring jumps, no position shifts, no lighting changes—just smooth, cinematic sequences with synchronized sound.

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![AI Video](https://img.shields.io/badge/AI-Video%20Generation-blue)](https://github.com/Eric-Lautanen/seamless-ai-video-prompt-template)

---

## 🚀 Quick Start (3 Steps)

### 1. Fill Out the Form
Open `seamless_video_prompt_template.txt` and fill out the 9 fields at the top.

### 2. Give It to an AI
Paste the filled template into ChatGPT, Claude, Gemini, or Grok and say:
> "Please use this template to generate seamless video prompts for my concept."

### 3. Generate Your Video
Use the detailed prompts with the **Last Frame Method**:
- Generate Clip 1 as text-to-video
- Export last frame from your video editor (NOT screenshot!)
- Generate Clip 2 as image-to-video using that frame
- Repeat for all clips
- Stitch together

**Result:** Professional seamless sequence that looks like one continuous shot with continuous audio.

---

## 📝 The 9 Input Fields

### 1. **CONTENT TYPE(S)**
Select one or more types that describe your video:

| Type | Use For | Examples |
|------|---------|----------|
| **Narrative** | Character-driven stories, emotional arcs | Hero's journey, character reveal, emotional moment |
| **Dialogue** | Conversations, interviews, talking scenes | Two people talking, interview setup, debate |
| **Dance** | Choreographed movement, performances | Solo dance, group routine, synchronized movement |
| **Landscape** | Nature, cityscapes, environments | Mountain flyover, city tour, forest walkthrough |
| **Wildlife** | Animals, nature behavior | Eagle hunting, lion stalking, underwater creatures |
| **Product** | Product reveals, commercial shots | Watch rotation, car reveal, tech unboxing |
| **Action** | High-energy movement, sports, fighting | Parkour chase, martial arts, car chase |
| **VFX** | Heavy effects, magic, sci-fi | Spell casting, portal opening, energy effects |
| **Aerial** | Drone shots, bird's eye views | Flyover, orbital reveal, ascending shot |

**Combine types:** "Narrative + VFX" for superhero scene, "Wildlife + Aerial" for nature doc, "Product + Action" for dynamic commercial

---

### 2. **VIDEO DURATION**
Total length in seconds. Will be divided into 6-second clips.
- **12-18 sec** (2-3 clips): Quick reveals, simple shots
- **24-36 sec** (4-6 clips): Single scene, action sequence
- **60+ sec** (10+ clips): Complete narrative, complex sequence

**Tip:** Start small (24-30 sec) to test the workflow before attempting longer sequences.

---

### 3. **CLIP LENGTH**
**6 seconds** (optimal for most AI video generators). This is the standard but adjustable if needed.

---

### 4. **SUBJECT/CONCEPT**
Describe your ENTIRE video from start to finish. Include:
- **Who/what** is in the scene
- **Where** it takes place
- **What happens** (beginning → middle → end)
- **How it looks** (visual style, mood, lighting)

**Bad example:** "A dragon"

**Good example:** "Ancient red dragon sleeping in treasure-filled cave. Camera starts on glowing eye opening, pulls back revealing massive scaled body coiled around gold, dragon raises head and roars sending flames toward camera, ends with dragon spreading wings filling frame."

---

### 5. **STYLE GUIDELINES**
Visual aesthetic and technical specs:

**Common Styles:**
- **Photorealistic:** "Shot on ARRI Alexa, cinematic, film grain, natural lighting"
- **Anime:** "Studio Ghibli style, hand-painted, soft colors, whimsical"
- **Cyberpunk:** "Neon-lit, rain-soaked streets, purple and cyan tones, Blade Runner aesthetic"
- **Documentary:** "BBC Planet Earth, natural lighting, 4K clarity, observational"
- **Commercial:** "Apple product video style, minimalist, clean lighting, slow motion"
- **Thriller:** "David Fincher style, desaturated, sharp contrast, cold tones"

**Mix and match:** "Photorealistic + cinematic golden hour + IMAX quality + epic scale"

---

### 6. **ASPECT RATIO**

| Ratio | Use For |
|-------|---------|
| **16:9** | YouTube, TV, standard horizontal |
| **9:16** | TikTok, Instagram Stories, Reels, vertical |
| **2.35:1** | Cinematic widescreen, movie-style |
| **1:1** | Instagram feed, square format |
| **21:9** | Ultra-wide cinematic |

---

### 7. **SPECIAL INSTRUCTIONS**
Key moments, transitions, or specific requirements:
- "Start with close-up on eyes, then pull back to reveal full character"
- "Launch sequence should feel powerful with camera shake"
- "Transition from day to night in the middle"
- "End with dramatic reveal of the spaceship"
- "Include slow-motion during the jump"
- "Smooth camera acceleration using ease-in/out curves"

---

### 8. **SOUND** 🎵 NEW!
Design your audio to match the visual sequence. The template tracks three audio layers plus transitions:

**Format:**
```
Music: [None / Track description / Volume %]
Ambient: [None / Environment description / Volume %]
Foley: [Yes/No / Specific effects]
Sound Transitions: [Crossfade, fade-in/out, continuity]
Notes: [Sync instructions, timing specifics]
```

**Three Audio Layers:**

1. **Music:** Background score or soundtrack
   - None / Track name / Description
   - Volume level (0-100%)
   - Example: `Music: Epic orchestral build, 60% volume`

2. **Ambient:** Environmental soundscape
   - None / Specify environment
   - Volume level (0-100%)
   - Example: `Ambient: City traffic distant, wind through alley, 40% volume`

3. **Foley:** Synchronized sound effects for actions
   - Yes / No / Specify effects
   - Synced to subject movement and camera actions
   - Example: `Foley: Footsteps on wet pavement, dress fabric swish, door creak`

**Sound Transitions:**
- **Crossfade:** Overlap between clips for smooth blend
- **Fade-in/out:** Gradual volume changes
- **Hard cut:** Immediate change for dramatic effect
- **Continuity:** Maintain same sound across clips

**Notes Section:**
- Sync instructions (match foley to choreography)
- Timing specifics (sound should peak at 3-second mark)
- Spatial audio cues (sound moves left to right with subject)

**Complete Example:**
```
Music: Atmospheric synth pad building tension, 50% volume
Ambient: Underground tunnel reverb, water dripping, 35% volume
Foley: Character footsteps echoing, breathing heavy, metal door scraping
Sound Transitions: Crossfade ambient from previous clip, music continues
Notes: Sync footstep foley to character stride, increase breathing as camera closes in
```

**Why Include Sound?**
- Modern AI video generators (Runway, Pika, Kling) support audio generation
- Sound design ensures continuity matches visual continuity
- Helps you plan complete audio post-production
- Reference for manual sound editing or AI audio tools

---

### 9. **NEGATIVE PROMPTS** (Optional)
Tell the AI what to avoid. Use 5-8 terms max.

**Universal Starter (use for everything):**
```
flicker, blur, morphing, text, watermark, low quality
```

**Add based on content:**
- **People/Characters:** `extra fingers, deformed hands, warped face, bad anatomy`
- **Products:** `fingerprints, dust, scratches, reflections`
- **Action:** `jitter, stutter, unnatural physics, shaky camera`
- **VFX:** `unconvincing compositing, temporal inconsistency, flat lighting`

**How to apply:**
- **Runway, Pika, Kling:** Paste in "Negative Prompt" field
- **Sora, Luma, Veo:** Add to end: "Avoid: flicker, blur, morphing, text, watermark"
- **Use SAME negatives for ALL clips** in your sequence

---

## 🎬 Advanced Camera Features

### Smooth Camera Movement System
The template now includes professional camera physics to eliminate jerky movements:

**Camera Inertia (0-1 scale):**
- 0 = Instant response (robotic)
- 0.5 = Natural motion (recommended)
- 1 = Heavy, slow response (cinematic)

**Damping:**
- Controls how quickly camera settles after movement
- Rotation damping (0-1): How pan/tilt decelerates
- Dolly damping (0-1): How forward/back movement stops

**Acceleration Limits:**
- Linear movement: ≤ 2 ft/sec² (prevents sudden speed changes)
- Rotational movement: ≤ 5°/sec² (prevents whip pans)

**Easing Curves:**
- **Linear:** Constant speed (mechanical feel)
- **Ease-in:** Slow start, faster end (building momentum)
- **Ease-out:** Fast start, slow end (gentle stop)
- **Ease-in-out:** Smooth start and stop (most natural)
- **Sinusoidal:** Wave-like, ultra-smooth

**Motion Sub-Segments:**
- Break complex moves into 1-2 second intervals
- Example: "Dolly forward 1 ft/sec for 2 sec (ease-in), arc left 5°/sec for 2 sec (ease-out), crane up 0.5 ft/sec for 2 sec"

---

## 📋 Complete Examples

### Example 1: Product Commercial
```
CONTENT TYPE(S): Product
VIDEO DURATION: 12
CLIP LENGTH: 6
SUBJECT/CONCEPT: Luxury gold watch on black velvet surface. Camera starts extreme close-up on watch face showing second hand ticking, slowly orbits around watch revealing side profile and bracelet, continues rotating 180° to show clasp and back of case, ends with full top-down view of complete watch centered.
STYLE GUIDELINES: Commercial luxury aesthetic, studio lighting, high-key, pristine clarity, shot on high-end cinema camera, metallic reflections, f/2.8 shallow depth of field
ASPECT RATIO: 16:9
SPECIAL INSTRUCTIONS: Emphasize craftsmanship details, watch should remain perfectly centered throughout rotation, lighting should create elegant reflections on gold surface, use ease-in-out for smooth orbital movement
SOUND: Music: Subtle luxury brand ambience, 40% volume Ambient: Studio silence, faint room tone Foley: Gentle velvet surface texture Sound Transitions: Fade-in music at start Notes: Minimal sound for premium feel
NEGATIVE PROMPTS: blur, fingerprints, dust, scratches, text, watermark, low quality
```

### Example 2: Nature Documentary
```
CONTENT TYPE(S): Wildlife, Aerial
VIDEO DURATION: 24
CLIP LENGTH: 6
SUBJECT/CONCEPT: Golden eagle hunting over mountain valley. Starts with eagle soaring high in clear blue sky, eagle spots prey and banks into steep dive accelerating rapidly, camera follows descent staying behind eagle, eagle extends talons as ground approaches, pulls up at last second with captured rabbit in talons, camera arcs upward following eagle's ascent.
STYLE GUIDELINES: BBC Planet Earth style, photorealistic, natural lighting, pristine 4K clarity, documentary aesthetic, no color grading, authentic wildlife behavior
ASPECT RATIO: 16:9
SPECIAL INSTRUCTIONS: Speed ramp during dive to emphasize acceleration, capture moment of talon extension clearly, show power of pull-up with prey, camera inertia 0.6 for natural tracking
SOUND: Music: None Ambient: Mountain wind constant, 50% volume Foley: Eagle wing flaps, wind rush during dive, rabbit cry Sound Transitions: Ambient continuous throughout, wind intensity increases during dive Notes: Sync wing flaps to visible movement, crescendo wind rush at dive peak
NEGATIVE PROMPTS: flicker, blur, artificial movement, mechanical motion, low quality, morphing
```

### Example 3: Sci-Fi Narrative
```
CONTENT TYPE(S): Narrative, VFX, Aerial
VIDEO DURATION: 36
CLIP LENGTH: 6
SUBJECT/CONCEPT: Elon Musk in SpaceX spacesuit at Cape Canaveral launch pad at dawn looking up at massive Starship. Camera starts close on face showing determination, pulls back revealing full rocket scale, Starship engines ignite and lift off with Elon watching, camera follows rocket ascending through clouds into space, final shot shows Starship approaching Mars with red planet filling frame.
STYLE GUIDELINES: Photorealistic, IMAX documentary quality, SpaceX/NASA aesthetics, golden hour lighting transitioning to space darkness, high detail on spacesuit and rocket, volumetric exhaust effects, epic scale, shot on ARRI Alexa 65
ASPECT RATIO: 2.35:1
SPECIAL INSTRUCTIONS: Start intimate then reveal scale, launch should feel powerful with camera shake, smooth transition from blue sky to black space, Mars approach as climactic reveal, use camera damping 0.3 for responsive tracking during launch
SOUND: Music: Epic orchestral building throughout, 70% volume Ambient: Launch pad atmosphere to engine roar to space silence, 80% volume Foley: Spacesuit breathing, rocket ignition, engine rumble Sound Transitions: Crossfade ambient layers as environment changes, music continuous Notes: Sync breathing to close-up, massive engine sound peak at liftoff, fade to silence in space
NEGATIVE PROMPTS: flicker, blur, morphing, text, watermark, warped face, cartoon, unconvincing compositing, temporal inconsistency
```

### Example 4: Action Sequence
```
CONTENT TYPE(S): Action, Narrative
VIDEO DURATION: 30
CLIP LENGTH: 6
SUBJECT/CONCEPT: Parkour athlete in red jacket running across urban rooftops at sunset. Starts with athlete sprinting toward camera, athlete vaults over AC unit, continues running and leaps across gap between buildings, lands and rolls on adjacent rooftop, springs up and continues running as camera follows, ends with athlete jumping and grabbing fire escape ladder.
STYLE GUIDELINES: Gritty urban realism, desaturated except for red jacket, handheld energy, practical lighting, sunset backlight, high contrast, shot on Sony FX6
ASPECT RATIO: 16:9
SPECIAL INSTRUCTIONS: Handheld camera shake throughout for energy, speed ramp during building leap, maintain sense of height and danger, jacket should be vibrant against muted environment, camera inertia 0.7 for heavy handheld feel
SOUND: Music: Intense electronic beat, 60% volume Ambient: City traffic below, distant sirens, 40% volume Foley: Running footsteps on concrete, breathing heavy, fabric rustling, landing impact Sound Transitions: Music continuous, ambient maintains urban environment Notes: Heavy foley on footsteps and landings, breathing synced to exertion, fabric swish on jumps
NEGATIVE PROMPTS: flicker, blur loss, jitter, stutter, unnatural physics, morphing, low quality
```

### Example 5: Music Video
```
CONTENT TYPE(S): Dance, VFX, Narrative
VIDEO DURATION: 30
CLIP LENGTH: 6
SUBJECT/CONCEPT: Solo dancer in white flowing dress in empty warehouse with dramatic side lighting. Camera starts on dancer's feet, slowly cranes up revealing full body as dancer begins slow contemporary movement, camera orbits counter-clockwise around dancer as movement intensifies, magical blue particles begin emanating from dancer's hands, camera completes 180° orbit as particles fill the space, ends with wide shot showing dancer surrounded by swirling particle effects.
STYLE GUIDELINES: Cinematic music video aesthetic, high contrast side lighting, volumetric light rays through windows, slow motion at 120fps, magical realism, moody atmosphere
ASPECT RATIO: 2.35:1
SPECIAL INSTRUCTIONS: Particles should progressively increase from 0 to hundreds, movement should feel fluid and weightless, lighting should create dramatic shadows, end wide to show full effect, use sinusoidal easing for dreamy camera orbit
SOUND: Music: Ethereal electronic with building intensity, 80% volume Ambient: Warehouse reverb, distant city muffled, 30% volume Foley: Dress fabric flowing, bare feet on concrete, particle shimmer effects Sound Transitions: Music continuous build, crossfade ambient layers Notes: Sync particle sounds to visual density, fabric sounds match dance moves, spatial audio as camera orbits
NEGATIVE PROMPTS: flicker, morphing, temporal inconsistency, unconvincing compositing, blur, mistimed movement
```

---

## 📋 Ready-to-Use Examples

Check out the `/examples` folder for pre-filled templates you can copy and modify:

- **[product-commercial-watch.txt](examples/product-commercial-watch.txt)** - Luxury watch reveal with orbital camera
- **[nature-documentary-eagle.txt](examples/nature-documentary-eagle.txt)** - Golden eagle hunting sequence
- **[sci-fi-narrative-elon-mars.txt](examples/sci-fi-narrative-elon-mars.txt)** - SpaceX Starship launch to Mars
- **[action-sequence-parkour.txt](examples/action-sequence-parkour.txt)** - Urban rooftop parkour chase
- **[music-video-dancer.txt](examples/music-video-dancer.txt)** - Contemporary dance with VFX particles

Simply copy an example, modify it for your needs, and paste into your AI!

---

## 🎯 The Last Frame Method

**Why it's critical:** AI video generators have randomness. The Last Frame Method eliminates this by showing each clip exactly where to start.

### Workflow:
1. **Generate Clip 1** → Text-to-video with your prompt
2. **Export last frame** → Use video editor's export function (NOT screenshot)
   - DaVinci Resolve: Right-click timeline → Grab Still → Export PNG
   - Premiere: File → Export → Frame
   - CapCut: Right-click frame → Export Frame
   - **Must be same resolution as video!**
3. **Generate Clip 2** → Image-to-video with exported frame + Clip 2 prompt
4. **Repeat** → Export last frame of Clip 2 → Generate Clip 3, etc.
5. **Stitch** → Combine all clips in editor
6. **Add Audio** → Use sound design from prompts to add music, ambient, and foley

### Why NOT screenshots?
❌ Wrong resolution  
❌ Compression artifacts  
❌ May capture UI elements  
❌ Wrong color space  

✅ Editor exports maintain exact resolution, aspect ratio, and quality

---

## 🎨 Camera Movement Glossary

| Movement | Description | Speed Scale |
|----------|-------------|-------------|
| **Dolly** | Forward/backward toward subject | 0.5-3 ft/sec typical |
| **Truck** | Left/right lateral movement | 0.5-3 ft/sec typical |
| **Crane/Pedestal** | Up/down vertical movement | 0.5-3 ft/sec typical |
| **Pan** | Horizontal rotation (swivel) | 5-30°/sec typical |
| **Tilt** | Vertical rotation (look up/down) | 5-30°/sec typical |
| **Arc/Orbital** | Circular path around subject | 5-20°/sec typical |
| **Zoom** | Lens focal length change | Specify start/end focal length |
| **Roll/Dutch** | Horizon tilt (axis rotation) | 5-15°/sec typical |

**Speeds:**
- **Glacial:** 0.1-0.3 ft/sec (barely perceptible)
- **Slow:** 0.5-1 ft/sec (contemplative)
- **Moderate:** 1.5-3 ft/sec (natural)
- **Fast:** 4-6 ft/sec (energetic)
- **Rapid:** 7+ ft/sec (action)

**Acceleration Limits (for smooth motion):**
- Linear: ≤ 2 ft/sec²
- Rotational: ≤ 5°/sec²

---

## 📊 Motion Blur Scale

The template tracks motion blur intensity as a percentage:

- **0-5%** = Minimal (slow movement, barely visible)
- **5-15%** = Subtle (walking, gentle camera moves)
- **15-25%** = Moderate (running, quick pans)
- **25-40%** = Strong (action sequences, fast motion)
- **40%+** = Extreme (high-speed chases, impacts)

The AI calculates this automatically based on movement speeds.

---

## 🎵 Sound Design Features

The template now includes comprehensive audio tracking:

### Audio Layers
1. **Music:** Score, soundtrack, background music
2. **Ambient:** Environmental sounds, atmosphere
3. **Foley:** Action-synced sound effects

### Transition Types
- **Crossfade:** Smooth overlap between clips
- **Fade-in/out:** Gradual volume changes
- **Hard cut:** Immediate change
- **Continuity:** Sustained across clips

### Sync Capabilities
- Match foley to choreography
- Time-specific audio cues
- Spatial audio positioning
- Volume automation

---

## 🛠️ Compatible Platforms

### AI Prompt Generators (where you use the template):
- ✅ ChatGPT (GPT-4, GPT-4o, o1)
- ✅ Claude (Sonnet, Opus)
- ✅ Google Gemini (Pro, Ultra)
- ✅ Grok
- ✅ Any instruction-following AI

### AI Video Generators (where you generate clips):

**With Image-to-Video (Last Frame Method works best):**
- ✅ Runway Gen-3/Gen-4
- ✅ Pika Labs
- ✅ Luma Dream Machine
- ✅ Kling AI
- ✅ Haiper AI
- ✅ Stability AI Video
- ✅ Grok Imagine

**Text-Only (Template still helps):**
- ✅ Sora/Sora 2
- ✅ Veo 2/3
- ✅ Any emerging models

**Audio Generation Compatible:**
- ✅ Runway (built-in audio)
- ✅ Pika Labs (sound effects)
- ✅ Kling AI (audio support)
- ✅ ElevenLabs (custom audio post-production)
- ✅ Suno AI (music generation)

---

## ⏱️ Time Estimates

**Prompt Generation (AI creating the clip prompts):**
- 12-24 sec video: 1-2 minutes
- 30-60 sec video: 2-4 minutes
- 120+ sec video: 5-8 minutes

**Video Generation (creating actual clips):**
- Per clip: 30 seconds - 5 minutes (depends on platform and queue)
- 30-sec video (5 clips): 15-30 minutes total
- 60-sec video (10 clips): 30-60 minutes total

**Audio Post-Production:**
- Manual editing: 10-20 minutes per minute of video
- AI-assisted: 5-10 minutes per minute of video

**Tip:** Generate during off-peak hours for faster results. Sequential generation (Last Frame Method) takes longer but ensures perfect continuity.

---

## 🙋 FAQ

**Q: Do I need to understand camera terminology?**  
A: No! Just fill out the form. The AI handles all technical details including camera physics and sound design.

**Q: Can I use this for vertical videos (TikTok)?**  
A: Yes! Set ASPECT RATIO to 9:16.

**Q: What if clips don't match perfectly?**  
A: The Last Frame Method fixes 95% of issues. For remaining mismatches:
- Regenerate with same last frame
- Adjust "image strength" parameter higher
- Minor post-production adjustment if needed

**Q: Should I always use negative prompts?**  
A: Not required, but recommended. Start with universal preset: "flicker, blur, morphing, text, watermark, low quality"

**Q: Can I modify the template?**  
A: Absolutely! It's MIT licensed. Customize for your workflow.

**Q: How long can sequences be?**  
A: Technically unlimited, but practical limits:
- Sweet spot: 24-60 seconds (4-10 clips)
- Longer sequences require more patience
- Very long (5+ min) may have style drift

**Q: Do I need to design sound even if I'll add it later?**  
A: No, but it helps! The sound section:
- Ensures audio continuity matches visual continuity
- Provides clear reference for post-production
- Works with AI video generators that support audio
- Can be skipped if you prefer manual audio editing

**Q: What's camera inertia and do I need to set it?**  
A: Camera inertia controls how "heavy" the camera feels (0=instant response, 1=slow/cinematic). The AI will choose appropriate defaults if you don't specify, but mentioning it in SPECIAL INSTRUCTIONS helps for specific styles (handheld vs. crane vs. stabilized).

**Q: How do easing curves improve camera movement?**  
A: Easing curves (ease-in, ease-out, ease-in-out, sinusoidal) make camera movement feel natural by gradually accelerating/decelerating instead of starting/stopping instantly. This eliminates the "robotic" feel common in AI videos.

---

## 📄 License

MIT License - Free for personal and commercial use.

---

## 🤝 Contributing

Contributions welcome! Submit issues or pull requests on GitHub.

**Ideas:**
- More example sequences
- Platform-specific tips
- Translations
- Video tutorials
- Audio workflow guides

---

## 🏆 Credits

Built with insights from professional cinematographers, sound designers, and AI video community feedback.

*Star this repo if it helps you create amazing videos!* ⭐

---

**Keywords:** AI video generation, text to video, seamless transitions, video prompts, Runway ML, Sora, Pika Labs, Kling AI, continuous shot, single take video, AI cinematography, prompt engineering, last frame method, image to video, video continuity, camera movement, sound design, foley, audio continuity, smooth camera motion, easing curves, camera physics
