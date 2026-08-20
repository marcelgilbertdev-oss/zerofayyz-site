# ZEROFAYYZ

Source for **[zerofayyz.com](https://zerofayyz.com)** — a digital production studio.

**Game-ready 3D** — characters, environments and props for Unity, Unreal and Blender.
Rigged, animated, LOD'd, and verified in the target engine.
**AI video and animated shorts** — produced end to end, right model per shot, narration included.
**Custom tools and interfaces** — internal tools, dashboards, working prototypes.

Project enquiries: **marcel.gilbert.dev@gmail.com**

---

## The free guides

Three of them, no signup, no email gate. Written because they didn't exist and we needed them.

## [The AI Video Prompting Guide (2026)](https://zerofayyz.com/ai-video-prompting-guide.html)

Every major AI image and video model wants to be prompted differently, and every model
maker documents their own model and nothing else. This puts ~15 of them side by side.

A few of the differences that cost people the most time:

- **Seedance** takes audio as delimiters inside the prompt — music in `( )`, SFX in `< >`,
  dialogue in `{ }`, subtitles in `【 】`. Silence is not the default: if you don't mention
  audio, it usually scores the clip anyway.
- **MiniMax Hailuo** takes literal camera commands in square brackets — `[Push in]`,
  `[Truck left]`, `[Static shot]` — up to three combined before it degrades.
- **Kling** wants a master prompt for style and characters plus separate per-shot blocks,
  and does up to 6 cuts in one generation. Dialogue is `[Name: role, tone]: "Line."`, at
  roughly 8–12 words per 5 seconds before lip sync falls apart.
- **Veo** burns subtitles into the video whenever you quote dialogue. You have to add
  "no subtitles, no captions, no on-screen text."
- **FLUX.2** has no negative prompts at all — it's guidance-distilled, so you write
  "sharp focus throughout," never "no blur." It also supports literal JSON prompting and
  hex-colour binding.
- **Wan** rejects real people's names, and orbit arcs degrade past ~45°.

The rule that held on every model: **on image-to-video, never re-describe the input image.**
Prompt only what moves, what causes it, the camera, and where it settles.

Claims are tagged **[A]** (officially documented) or **[D]** (community-reported), and the
gaps are marked as gaps rather than filled with guesses.

## [The YouTube AI Disclosure Checklist (2026)](https://zerofayyz.com/ai-disclosure-checklist.html)

When YouTube requires the "Altered content" disclosure, what records to keep per video, and
the upload-day check. Organizational guidance, not legal advice.

## [The Content ID Defense Kit](https://zerofayyz.com/content-id-defense-kit.html)

The evidence to capture *before* a claim lands, and the sequence to follow when one does.

---

Corrections welcome — open an issue. These platforms ship changes weekly and some of this
will go stale. Not affiliated with, endorsed by, or sponsored by any platform or model maker
named in the guides; all trademarks belong to their respective owners.
