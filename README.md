# Seamless AI Video Prompt Generator

**Solve the #1 problem in AI video generation: Continuity.**

Generate professional, multi-clip AI video sequences with perfect consistency. This prompt framework turns LLMs (ChatGPT, Claude, Gemini) into professional cinematographers, handling camera physics, subject locking, and editorial flow so you don't have to.

**Three versions available. Choose the one that matches your workflow.**

[![AI Video](https://img.shields.io/badge/GenAI-Video%20Workflow-blue)](https://github.com/Eric-Lautanen/seamless-ai-video-prompt-template)

## 🤖 Compatible LLMs (The "Brain")
This template is optimized for the following 2026 flagship models. Upload the `.txt` template of your choice and say **"Prefill"** to begin.

[![ChatGPT](https://img.shields.io/badge/ChatGPT-74aa9c?style=for-the-badge&logo=openai&logoColor=white)](https://chatgpt.com)
[![Claude](https://img.shields.io/badge/Claude-D97757?style=for-the-badge&logo=claude&logoColor=white)](https://claude.ai)
[![Gemini](https://img.shields.io/badge/Gemini-8E75B2?style=for-the-badge&logo=googlegemini&logoColor=white)](https://gemini.google.com)
[![DeepSeek](https://img.shields.io/badge/DeepSeek-4D6BFE?style=for-the-badge&logo=deepseek&logoColor=white)](https://chat.deepseek.com)
[![Grok](https://img.shields.io/badge/Grok-000000?style=for-the-badge&logo=x&logoColor=white)](https://x.com/i/grok)
[![Qwen](https://img.shields.io/badge/Qwen-615ced?style=for-the-badge&logo=alibabacloud&logoColor=white)](https://chat.qwenlm.ai)

---

## ⚡ Which Version Should You Use?

| Version | Best For... | Key Features | File Name |
| :--- | :--- | :--- | :--- |
| **🎥 Cinematic (V5)** | **Filmmakers & Pros** | Full Hollywood camera physics, motivated cuts, 180° rule, VFX logic, & complex sound design. | `seamless_video_prompt_template.txt` |
| **🚀 Standard Lite** | **Content Creators** | The perfect balance. Fast setup, reliable consistency, strict "no-slop" rules, & automatic extension logic. | `seamless-ai-video-prompt-lite.txt` |
| **⚡ Token Efficient** | **Power Users / API** | Ultra-compressed. Best for long videos (10+ clips) or LLMs with smaller context windows. | `seamless-ai-prompt-template-token-effecient.txt` |

---

## 🚀 Quick Start Guide

### 1. Pick Your Template
Copy the full text of your chosen version (`Cinematic`, `Lite`, or `Token Efficient`).

### 2. "Prefill" (The Magic Step)
Paste the template into ChatGPT, Claude, Gemini, or Grok and type:
> "Prefill this for a [Cyberpunk detective walking through a rainy neon city]"

The AI will auto-complete the technical definitions (Lighting, Camera, Physics) based on your simple idea. It creates a "Master File" you can review.

### 3. "Run"
Once you are happy with the plan, type:
> "Run"

The AI will generate **individual artifacts** (code blocks) for every single clip.

### 4. Generate the Video (The Chain)
1. Copy the prompt for **Clip 1**. Paste into Runway/Pika/Sora/Kling.
2. **CRITICAL:** Take the *last frame* of Clip 1 (export it from your editor, don't just screenshot).
3. Use that image as the **Start Frame** (Image-to-Video) for Clip 2.
4. Paste the prompt for **Clip 2**.
5. Repeat for the whole sequence.

---

## 🔍 Deep Dive: The Editions

### 1. Cinematic Edition (V5)
**"The Director's Cut"**
This is the heavy lifter. It treats the LLM like a film school graduate.
* **Physics Engine:** Defines camera inertia, damping, and acceleration (e.g., "Truck left at 2ft/s").
* **Spatial Rules:** Enforces the **180-Degree Rule**, **30-Degree Rule**, and **Eyeline Matching** to prevent viewer disorientation.
* **Environment Modes:**
    * *Static:* Room never changes.
    * *Evolving:* Room changes over time (great for burning buildings or time-lapses).
    * *Per-Clip:* Character moves through different rooms.
* **Failure Analysis:** The AI performs a "pre-flight check" before writing every prompt to predict and prevent glitches specific to that exact moment.

### 2. Standard Lite Edition
**"The Creator's Choice"**
Streamlined for speed without sacrificing quality.
* **Efficiency:** Skips the complex physics math in favor of natural language descriptions.
* **Anti-Slop Logic:** Built-in rules to prevent common AI failures (fading to black, morphing faces, awkward pauses).
* **Smart Extension:** If your action won't fit in 6 seconds, the AI automatically calculates the necessary time extension.
* **Output:** Clean, single-click copyable prompts perfect for Runway Gen-3 or Luma Dream Machine.

### 3. Token Efficient Edition
**"The Minimalist"**
Designed to save context window space and generate faster.
* **Compressed Logic:** Uses a "baseline" reference system. Clip 1 defines the world; subsequent clips only describe *changes*.
* **Low Token Cost:** Perfect if you are paying per token or using smaller models.
* **Boundary Locking:** Enforces strict visibility rules only at the start/end of clips to maximize AI creativity in the middle.

---

## 🎬 Key Technologies & Concepts

### The "Last Frame" Workflow
AI video models have short memories. To get a 60-second consistent video, you cannot generate it all at once.
* **The Solution:** This template generates **linked prompts**.
* Clip 2's prompt explicitly describes Clip 1's ending state.
* By combining this text prompt with the **Image-to-Video** feature of your generator (using Clip 1's last frame), you achieve near-perfect continuity.

### The Reference Image Strategy (2026 Ready)
For the absolute best results with modern models (Veo, Sora, Gen-3 Alpha):
1.  Generate a "Character Sheet" or select a perfect photo of your subject.
2.  Use this **same image** as a reference for *every single clip*.
3.  Use the **Last Frame** of the previous clip as the *start frame*.
4.  This "Dual Image" input (Start Frame + Reference Frame) locks identity by 80% more than text alone.

### Spatial Continuity Rules (Cinematic Only)
* **180-Degree Rule:** Keeps characters on the correct side of the screen during conversation.
* **Match on Action:** Cuts occur *during* movement (e.g., a door opening) rather than before/after, masking the transition.
* **Eye Trace:** Directs the viewer's eye to the correct spot for the next cut.

---

## 🛠 Compatible Tools

**Text Generation (The Brain):**
* ChatGPT (GPT-4o / o1) - *Highly Recommended*
* Claude 3.5 Sonnet / Opus - *Best for creative writing*
* Google Gemini 1.5 Pro
* Grok 2/3

**Video Generation (The Engine):**
* Runway Gen-3 Alpha / Gen-2
* Luma Dream Machine
* Kling AI
* Pika Labs
* OpenAI Sora (when available)
* Google Veo (when available)
* Grok Imagine
* Wan AI

---

## ❓ FAQ

**Q: Why does the prompt repeat the character description every time?**
A: AI models have "attention drift." If you don't remind them exactly what the character acts/looks like in *every* prompt, they will hallucinate changes (e.g., changing a t-shirt color).

**Q: Can I use this for non-realistic styles?**
A: Yes. Just define "Anime," "Claymation," or "Watercolor" in the `Style` section. The camera and continuity rules apply universally.

**Q: The AI is refusing to generate "unsafe" content?**
A: These templates are designed for general creativity. If you trigger safety refusals, check your `Subject` or `Narrative` descriptions. The template itself is neutral.

---

## 📄 License

MIT License

Copyright (c) 2026 Eric Lautanen

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
**If this saves you hours of frustration, give the repo a star! ⭐**
