# no-aispeak

A Claude Cowork skill that catches AI writing tells before your copy goes out.

---

## The problem

AI-generated text has a shape. A 2026 study from the University of Maryland and Google DeepMind ([StoryScope](https://arxiv.org/abs/2604.03136)) found that structure alone — no vocabulary analysis — identifies AI vs. human writing at 93.2% accuracy. The five AI models tested (Claude, GPT, Gemini, DeepSeek, Kimi) clustered in a tight zone. Human writers scattered across the whole map.

Word swaps don't fix this. Replacing "delve" with "explore" and calling it done misses the actual tells: AI states its own moral, names nothing real, resolves every thread, and maintains a flat, even register from first sentence to last.

This skill addresses both layers — the structural patterns that detectors actually catch, and the vocabulary that trained readers notice first.

---

## What it catches

The skill organizes tells into five tiers, from most to least diagnostic:

**Tier 1 — Structural** (93.2% detection accuracy from structure alone)
- States the lesson explicitly instead of letting content make the case
- Names nothing real — no specific person, company, date, study, or price
- Ties every thread into a clean resolution; nothing left open
- Even coverage — every section equally developed regardless of what matters
- No lived experience; nothing only this author could know

**Tier 2 — Vocabulary** (65+ flagged words and phrases)
Includes: delve, leverage, robust, seamless, transformative, pivotal, tapestry, realm, beacon, foster, embark, myriad, ecosystem, paradigm shift, "at its core," "in today's fast-paced world," and others documented in the 2025–2026 research.

**Tier 3 — Rhetorical patterns**
Compulsive Rule of Three, contrastive parallelism ("it's not X, it's Y"), false ranges ("from X to Y"), staged rhetorical questions, present-participle trailing clauses, and compulsive summaries.

**Tier 4 — Tone**
Hedge saturation, vague attribution, uniform register, significance declared not shown, and the "both sides" reflex.

**Tier 5 — Formatting**
Excessive bolding, perfect paragraph rectangles, and bullet-heavy structure where prose would flow.

---

## Installation

Download `no-aispeak.skill` from this repo and open it in Claude Cowork. Click "Save skill." It installs immediately.

Once installed, the skill is always-on for audience-facing writing. Any request to write, draft, edit, or review copy triggers it automatically. No slash command required.

---

## Refresh command

AI writing patterns shift as models retrain. The vocabulary blacklist especially drifts — models train away from the most-flagged words and new patterns emerge.

To update the methodology: say `/refresh`, "refresh no-aispeak," or "are these AI tells still current."

The skill will search for research published after its `methodology_date`, produce a diff (words to add, words to retire, new patterns), and ask for approval before changing anything. Tier 1 structural rules are protected from casual refresh — those only change if new peer-reviewed research updates the underlying findings.

---

## Audit mode

Paste existing copy and say "check this for AI tells." The skill returns a flagged version with inline comments, then a clean revised version.

---

## Methodology

Built from six sources, all from 2025–2026:

- [StoryScope](https://arxiv.org/abs/2604.03136) — University of Maryland + Google DeepMind (2026)
- [Telltale-AI.com](https://www.telltale-ai.com/blog/how-to-spot-ai-writing) — based on Wikipedia's editorial AI detection guide (May 2026)
- [StationX / Nathan House](https://app.stationx.net/articles/ai-writing-patterns) — built and blind-tested a structural detector (July 2026)
- [OliviaCal.com](https://www.oliviacal.com/post/ai-writing-tells) — B2B copywriter vocabulary blacklist (updated May 2026)
- [Cherryleaf.com](https://www.cherryleaf.com/2026/02/indicators-that-suggest-something-was-written-by-ai/) — technical writing perspective (February 2026)
- [AI Localization Think Tank / Marina Pantcheva](https://www.ailocthinktank.com/post/the-telltale-signs-of-ai-generated-content) — linguistic pattern analysis (October 2025)

Methodology version: 1.0 (July 2026)
