# Ambient Concept Generator

A browser-based inspiration tool for ambient musicians. Combines modifiers and nouns to generate concept starting points for new pieces — displayed as a flowchart showing a light and dark take on the same anchor word.

**[→ Open the Tool](https://craigdamlo.github.io/Ambient-Concept-Generator/)**

![Ambient Concept Generator screenshot](screenshot.png)

---

## What It Does

Opens with a concept already loaded. Hit Generate to get another.

The layout shows three words connected by lines:

- **Light modifier** (top) — an evocative word drawn from the light pool
- **Noun** (center, right-justified) — the shared anchor word
- **Dark modifier** (bottom) — a contrasting word drawn from the dark pool

The light and dark modifiers are drawn from completely separate word pools so they're always genuinely distinct. The noun is the shared anchor — both concepts tell a different story about the same thing.

**Lock any word** by tapping 🔓 next to it. Locked words survive a Generate, letting you zero in on a concept piece by piece rather than rerolling everything at once. Changing the setting unlocks all words.

**Setting** (optional): Space · Nature · City · Industrial · Archive · Fantasy

Selecting a setting biases both the modifier and noun pools toward that world. Leave it unselected for pure surprise.

---

## Combinations

Each mood modifier pool contains 25 words. Light and dark modifiers are drawn from completely separate pools — overlap is impossible by design. Setting noun pools each contain 25 words, with some nouns intentionally shared across settings (a city has archives, a fantasy world has nature).

There is a 35% chance of a two-noun anchor being generated, multiplying the possible combinations significantly.

- 136 unique nouns across all 6 settings × 25 light × 25 dark = **85,000 single-noun combinations**
- 3 neutral-only nouns (Ferry, Static, Echo) × 25 light × 25 dark = **1,875 additional combinations**
- Two-noun pairs from 139 unique nouns: 139 × 138 / 2 × 25 × 25 = **5,990,625 two-noun combinations**
- **Grand total: ~6,077,500 unique combinations**

---

## Running Locally

No build step, no dependencies, no install required.

```
git clone https://github.com/CraigDamlo/Ambient-Concept-Generator.git
cd Ambient-Concept-Generator
open index.html
```

Works offline after fonts load.

---

## Background

Made by [Soap Box Rocket](https://soapboxrocket.bandcamp.com) — a Seattle-based ambient project working primarily on the Dirtywave M8 and Deluge. The tool came out of wanting a creative starting point that gets out of the way fast — one strong concept is enough to anchor a whole piece.

Inspired by tracks like [Number Station](https://soapboxrocket.bandcamp.com/track/number-station) — built around a captured shortwave broadcast — and [Maui Tuesday](https://soapboxrocket.bandcamp.com/track/maui-tuesday), recorded while sitting on a beach trying to match a synth to the real sound in front of me. The best pieces start with a real-world anchor. This tool helps find one.
