# Complete Guide to Hooks

An interactive reference and toolkit for short-form video hooks — the first 1–3 seconds that decide whether anyone watches. Built for creators who already know how to shoot and edit, but want to master the opening.

---

## Files

| File | What it is |
|---|---|
| `index.html` | The standalone, self-contained build — works offline, share/open anywhere. Regenerated from the source. |


---

## How to use it

1. **Open** `index.html` in any browser (no internet needed).
2. **Pick your level** (top right): Beginner → Intermediate → Advanced. Higher levels unlock more sections and depth.
3. **Toggle dark / light** with the sun/moon button. Dark is the default.
4. **Navigate** with the left sidebar. Sidebar numbering is sequential and re-counts automatically as sections unlock per level.

---

## The three levels

The guide reveals itself progressively, so it's not overwhelming for newcomers but still deep for experienced creators.

- **Beginner** — Foundations, the 6 core hook types, Formulas, Workflow, My Videos, and the 7-Day Plan.
- **Intermediate** — also unlocks the Hook Generator, the Quiz, the Platforms section, niche filtering, all 13 hook types, and the psychology layer.
- **Advanced** — also unlocks the full Advanced Techniques section and an extra strategy callout in Foundations.

The header shows a section kicker (Learn / Tools / Apply), a pill level switcher, and a round dark/light toggle.

---

## Sections

- **Foundations** — what a hook is, why it's the highest-leverage edit, the three layers (see / read / hear), the psychology, and the four qualities of a good hook.
- **Hook Types** — the core toolkit of 13 types (Question, Curiosity, Bold claim, Story, Listicle, Proof, Negative, Transformation, Visual, Callout, FOMO, POV, ASMR). Each card expands to show sub-types, copy-paste examples, why it works, and which niches it suits. Filter by niche at Intermediate+.
- **Formulas** — fill-in-the-blank templates grouped by goal. Click any line to copy it.
- **Hook Generator** — pick a niche, generate ready-to-tweak hook lines, re-roll for more.
- **Quiz** — "spot the hook type" with instant feedback and a score.
- **Platforms** — hooks tuned per platform (Instagram Reels, TikTok, YouTube Shorts, YouTube long-form, LinkedIn, Facebook): timing, sound/text behavior, best hook types, tailored examples, and concrete **opening techniques categorized by type** (zoom-in → Visual, text-first → Text, sound-led → Audio, cold-open → Edit, etc.).
- **Workflow** — an editable product-video sequence (Product → Customer review → Testing → Exhibition → Final launch). Add your own stages, remove any, reset. Each stage carries its job and best hook.
- **My Videos** — your personal swipe file. Add a video with a title, an optional link, and a hook category; it files automatically under the matching hook type, with a count per category. Each card links out; remove with ×. Builds your own tested library.
- **Advanced Techniques** — hook stacking, the open-loop/payoff principle, A/B testing, platform & audience matching, the 2026 algorithm reality, and the full Hook → Body → CTA structure.
- **7-Day Starter Plan** — a checklist with a progress bar.

---

## What's saved

Your progress persists in the browser (localStorage), per device:

- **7-Day Plan** — which days you've checked off.
- **Workflow** — your custom stages.
- **My Videos** — your saved swipe-file videos and their hook categories.

Resetting is available within the relevant sections.

---

## Editing the source

`index.html` is a single self-contained component:

- **Content** (hook types, formulas, platforms, workflow defaults, quiz) lives in the logic class as plain data arrays — easy to edit, add to, or reword.
- **Theme** is driven by CSS custom properties at the top of the file. Two palettes: dark (default) and light. The accent is purple (`#9F86FF` dark / `#6D45C9` light).
- **Tweaks** exposed: default theme, default level, and whether example lines show.

---

*Content based on 2026 short-form retention data and creator guides. Always adapt examples to your own niche and test against your own audience.*
