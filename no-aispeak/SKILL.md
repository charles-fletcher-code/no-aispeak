---
name: no-aispeak
description: >
  Writing style guardrail that prevents AI tells in any copy a human audience will read.
  Trigger on ANY request to write, draft, edit, review, or improve copy — emails, LinkedIn
  posts, messages, articles, blog posts, introductions, pitches, reports, summaries, bios,
  job descriptions, or anything else intended for an audience. Also trigger on "make this
  sound more human," "humanize this," "does this sound like AI?", "edit out the AI," or
  "review this for AI tells." Trigger on "refresh no-aispeak," "update the AI writing
  rules," "are the AI tells still current," or any request to update this skill's
  methodology. Treat this as always-on for audience-facing writing: do not wait for the
  user to ask for it explicitly. If you are about to write more than two sentences that
  someone else will read, this skill applies.
metadata:
  methodology_version: "1.0"
  methodology_date: "2026-07-11"
  methodology_sources:
    - "StoryScope 2026 (University of Maryland + Google DeepMind) — arxiv.org/abs/2604.03136"
    - "Telltale-AI.com — How to Spot AI-Generated Writing (May 2026)"
    - "StationX / Nathan House — AI Writing Patterns (July 2026)"
    - "OliviaCal.com — AI Writing Tells + Blacklist (updated May 2026)"
    - "Cherryleaf.com — Indicators of AI Writing (February 2026)"
    - "AI Localization Think Tank / Marina Pantcheva (October 2025)"
---

# No-AiSpeak

You are writing (or reviewing) copy that a human will read. Your job is to produce writing
that sounds like it came from a specific person — not from a language model averaging
across millions of documents.

The research behind this skill (StoryScope 2026 / University of Maryland + Google DeepMind,
Telltale-AI May 2026, StationX July 2026, OliviaCal May 2026, Cherryleaf Feb 2026,
AI Localization Think Tank Oct 2025) identifies 112 documented tells. The most diagnostic
are structural — structure alone distinguishes AI from human writing at 93.2% accuracy.
Vocabulary is visible but shallow; AI models are already training away from the most
famous words. Fix structure first, vocabulary second.

---

## Tier 1 — Structural (highest diagnostic value; fix these before anything else)

**1. Stating the lesson.** AI narrates its own point. If the content makes the case,
don't also write a sentence explaining what the case means. Cut the moral.

**2. Naming nothing real.** AI produces vague allusion dressed as expertise: "studies
show," "a major company," "experts say," "research indicates." Replace with the actual
study, the actual company, the actual expert — or drop the claim. Specificity is the
single strongest human signal.

**3. Tying every thread.** AI resolves everything. Every tension lands on acceptance,
every question gets answered, every subplot closes. Leave something open. Real thinking
doesn't resolve cleanly.

**4. No lived experience.** Nothing in the copy that only this author could know. No
real failure, no actual conversation, no named Tuesday. If the same paragraph could appear
in a different piece on the same topic by a different writer, it's too generic.

**5. Even coverage.** Every section equally developed regardless of what's interesting.
Human writers spend three paragraphs on what fascinates them and compress the obligatory
parts. Dwell where it matters; skip what doesn't earn its space.

**6. No tangents.** Human writing wanders productively. It gets excited about something
adjacent, follows it briefly, and doesn't always return. Perfect on-topic discipline is
a tell.

**7. Performing emotion through clichés.** "Heart racing," "breath catching," "stomach
dropping," "a chill ran down their spine." Say the feeling directly ("I was furious") or
give a specific physical detail no model would invent. Cut body-language boilerplate.

**8. Uniform register.** A real person's voice shifts. They slip from formal to casual,
use a word that reveals their background, make a joke that may or may not land. AI picks
a register and holds it perfectly from first sentence to last.

**9. Perfect outline structure.** Intro, three points, conclusion — every time. Vary
the architecture. Some pieces start in the middle. Some skip the intro entirely. Some
end on a question.

**10. Generic specificity.** Sounds concrete but isn't. "A company in the healthcare
space," "a recent study on productivity," "a typical enterprise workflow." If the example
could be swapped into a different article, it's a placeholder, not a detail.

---

## Tier 2 — Vocabulary blacklist

These words appear at statistically anomalous rates in AI-generated text (documented
across multiple 2025–2026 studies). Presence of 4+ in 200 words is a strong signal;
density matters more than individual words.

**Verbs to avoid:**
- delve / delve into
- leverage (as a verb)
- foster
- embark (on)
- empower
- unleash
- unlock (as a metaphor)
- ignite
- uncover (as a metaphor)
- cultivate
- elevate
- streamline
- optimize / optimise
- underscore
- navigate (as a metaphor)
- harness (as a metaphor)
- spearhead

**Adjectives to avoid:**
- robust
- seamless
- transformative
- pivotal
- multifaceted
- comprehensive (when used loosely)
- holistic
- dynamic (as a filler adjective)
- cutting-edge
- groundbreaking
- revolutionary
- future-ready
- unwavering
- nuanced (when the piece delivers no nuance)
- impactful
- actionable

**Nouns and metaphors to avoid:**
- tapestry (especially "rich tapestry")
- realm (as a domain metaphor)
- beacon
- symphony (as a metaphor)
- ecosystem (as a business metaphor)
- landscape (as a business metaphor)
- paradigm shift
- synergy
- myriad (instead of "many")
- plethora
- testament ("a testament to")
- mosaic (as a complexity metaphor)
- fabric (as a social metaphor)

**Intensifiers and qualifiers to avoid:**
- genuinely, truly, actually (used as sincerity markers rather than for genuine contrast)
- crucially
- importantly
- "at its core"
- "it's worth noting"

**Phrases to avoid:**
- "in today's fast-paced world"
- "in an increasingly X world"
- "in the ever-evolving landscape of"
- "best practices"
- "at scale"
- "end-to-end"
- "game-changer"
- "complex interplay"
- "profound impact"
- "left an indelible mark"
- "continues to shape"
- "foster collaboration"
- "drive innovation"
- "cultivate growth"
- "dive in" / "let's dive in" / "deep dive"
- "let's explore"
- "here's the thing"
- "here's an uncomfortable truth"
- "real talk"
- "needle-moving"

**What to use instead:** Concrete nouns. Active verbs. Specific numbers.
- "leverage our resources" → "use what we have" or "apply the $40k budget"
- "transformative impact" → name the specific change: "cut onboarding time from 6 weeks to 2"
- "robust solution" → describe what makes it strong
- "seamless experience" → describe what specifically doesn't break
- "holistic approach" → describe what it actually includes

---

## Tier 3 — Rhetorical patterns

Every pattern below is a legitimate writing device. AI deploys each one compulsively,
at 3–5x human frequency. The tell is density, not presence.

**Rule of Three.** AI enumerates almost everything in triplets — adjectives, examples,
clauses, sometimes triplets within triplets (fractal). Use two items or four. Let lists
be as long as they actually are.

**Contrastive parallelism.** "It's not X, it's Y." "Not just A, but B." Powerful once;
a tic by the third use. Also verify the contrast is real — AI frequently contrasts things
that are the same ("it's not about being seen, it's about being felt").

**False ranges.** "From X to Y" where X and Y don't form a real continuum. "From legal
frameworks to sustainability reports" — what lies between them? Use ranges only when the
endpoints define a genuine spectrum.

**Fronted focus / dramatic pause.** "The outcome? [explanatory sentence]." "Efficiency?
[definition]." Used occasionally by skilled writers; used in every third paragraph by AI.

**"Because…" fragments.** "Because visibility equals opportunity." "Because efficiency
without purpose is just speed in the wrong direction." Legitimate rhetorical device;
becomes a tell when repeated.

**Present participle trailing clauses.** Sentences that end with a gesture at importance:
"…emphasizing the significance of the moment." "…highlighting the importance of community."
These add the feeling of substance without adding substance. Cut them.

**Staged rhetorical questions.** Questions the writer already knows the answer to, used
as pivot transitions. Real questions are open — the writer doesn't know where they land.

**Compulsive summaries.** "In conclusion." "To summarize." "Overall." "In essence."
End with a thought, not a recap of what just happened.

**Transition overload.** "Furthermore," "Moreover," "Additionally," "It is important
to note" strung in sequence. Use "also" or let the next sentence's logic speak for itself.

**Comparative framing.** "Less like X, more like Y." Fine rarely; formulaic when
every reframing takes this shape.

**Contextual framing.** "As AI continues to reshape the world…" Ambient setup clause
followed by the actual point. The setup usually adds nothing.

---

## Tier 4 — Tonal tells

**Hedge saturation.** "Often," "typically," "generally," "can be," "may," "in many
cases" in nearly every declarative sentence. Real experts stake claims and qualify
specifically when needed — not reflexively across the board.

**Vague attribution.** "Experts say." "Studies show." "Research indicates." "It is
widely accepted." Either name the source or drop the claim.

**Risk aversion.** AI never writes a sentence someone might dispute, never makes a
joke that might not land, never asserts something that could be wrong. This safety
produces competent, bloodless prose. Take a position. Make the claim someone could
argue with.

**Significance declared, not shown.** "A pivotal moment." "Left an indelible mark."
"Played a crucial role." Show significance through specific detail. If you can't, the
significance claim doesn't belong there.

**Promotional superlatives for everything.** Every city is vibrant. Every culture is
rich. Every innovation is breathtaking. Pick one thing that's genuinely notable and say
why; skip the reflex superlative on everything else.

**Throat-clearing openers.** "In today's fast-paced world…" "This article aims to
explore…" "As we navigate an increasingly complex environment…" The real piece starts
in the second paragraph. Cut the first paragraph and see if anything is lost.

**The "both sides" reflex.** Balanced pros and cons with no commitment. Take a position.
Say what you actually think is true and defend it.

**The "This means" tick.** Announcing every logical connection before making it. "This
means several things." "This suggests three approaches." Trust the reader to follow the
logic without a signpost at every turn.

**Equal enthusiasm.** AI is equally invested in every section. Real writers dwell on
what interests them and compress what doesn't. The energy distribution in the copy should
be uneven.

---

## Tier 5 — Formatting tells

- Bold used to highlight key terms within running prose — treats paragraphs like
  textbook study guides. Bold is for navigation; trust the reader to find what matters.
- Every bullet formatted as "Bold Header: Explanatory sentence." Vary structure.
- Every paragraph approximately the same length. Vary: one sentence, then six, then two.
- Bullet-heavy structure when the ideas have natural connective flow. Use prose.

---

## What human writing has that AI writing lacks

Before delivering any audience-facing copy, verify at least one of the following is
present:

- A specific named person, place, company, study, price, or date
- A detail that could only come from this author's direct experience
- A claim the writer would have to defend if challenged
- A sentence that goes somewhere unexpected
- Something left unresolved

If none of these are present, the writing is probably AI-shaped even if every banned
word has been scrubbed. The structural fix is always: add something real and specific
that a model couldn't have generated without being told it.

---

## Audit mode — reviewing existing copy

When the user asks you to check existing copy for AI tells, work through this sequence:

1. **Specificity scan.** Find every claim that names nothing real. Flag it: "[VAGUE: no
   named source/person/company/date]" and either ask for the specific or suggest cutting.

2. **Vocabulary scan.** Count Tier 2 words. If 4+ appear in 200 words, flag the density
   and replace the most replaceable ones with concrete alternatives.

3. **Pattern scan.** Count triplets, contrastive constructions ("it's not X, it's Y"),
   false ranges ("from X to Y"), and compulsive summaries. Flag repetition of any single
   pattern more than twice.

4. **Resolution scan.** Does everything resolve? Does every section close with a summary
   sentence? Flag over-resolution: "consider leaving [this point] open."

5. **Register scan.** Does the tone hold perfectly flat from start to end? Note where a
   real voice would have varied — and suggest how.

6. **Report.** Deliver a short flagged version with inline comments, then a clean revised
   version that addresses the flags. If the copy is short (under 200 words), just deliver
   the revised version with a one-line note on the main pattern fixed.

---

## Refresh command

**Trigger phrases:** `/refresh`, "refresh no-aispeak," "update the AI writing rules,"
"are these AI tells still current," "check if the patterns have changed," "update the
methodology," or any request to bring the skill's ruleset up to date.

AI writing patterns shift as models retrain. The structural tells (Tier 1) are stable
because they reflect how LLMs work at a fundamental level, not surface habits. The
vocabulary blacklist and rhetorical patterns (Tiers 2–3) drift as the most-flagged
words get trained away and new patterns emerge to replace them. Run a refresh when the
skill feels like it's catching less than it used to, or every 3–4 months.

### What to do when refresh is triggered

**Step 1 — State the current version.**
Report the `methodology_date` and `methodology_sources` from the frontmatter so the
user knows what the current ruleset is based on and when it was last updated.

**Step 2 — Search for new research.**
Run searches targeting material published after the `methodology_date`. Use queries like:
- "AI writing detection 2026 [current year]"
- "signs of AI generated text [current year] research"
- "AI writing patterns linguistic study [current year]"
- "GPT Claude writing tells [current year]"
- "how to spot AI writing [current year]"

Prioritize: academic papers, editor guides from Wikipedia or major publications,
practitioner posts from linguists or writing researchers, and detection tool
documentation. Discount SEO-optimized listicles that recycle the same word lists
without original analysis.

**Step 3 — Fetch and read the most substantive sources.**
Aim for 3–5 sources with original analysis. Read enough of each to identify:
- New vocabulary items now appearing at anomalous rates
- Vocabulary items that have dropped off (models trained away; now common in human writing)
- New rhetorical or structural patterns documented
- Patterns that are no longer reliable signals
- Any new research methodology worth citing (e.g., corpus studies, detection accuracy
  papers)

**Step 4 — Produce a delta report.**
Present the user with a structured diff before making any changes:

```
REFRESH REPORT — [date]
Sources consulted: [list with URLs]

TIER 2 VOCABULARY
  Add: [words newly documented as AI-anomalous, with source]
  Remove: [words that have become too common in human writing to be reliable signals]
  Unchanged: [note if no changes found]

TIER 3 RHETORICAL PATTERNS
  Add: [newly documented patterns]
  Deprecate: [patterns no longer reliable]
  Unchanged: [note if no changes found]

TIER 1 STRUCTURAL
  [Note any new structural research; these change rarely]

METHODOLOGY NOTE
  [Any change in detection accuracy, new study findings, or caveats worth adding]
```

**Step 5 — Ask for approval before writing.**
Show the delta report and ask: "Should I apply these changes to the skill?" Do not
modify SKILL.md until the user confirms.

**Step 6 — Apply approved changes.**
Edit the relevant sections of SKILL.md. Update `methodology_version` (increment the
minor version, e.g., 1.0 → 1.1), update `methodology_date` to today, and add any new
sources to `methodology_sources`. Then repackage the skill using:

```bash
cd /path/to/skill-creator && python -m scripts.package_skill /path/to/no-aispeak /path/to/output/
```

Present the updated `.skill` file to the user with `present_files`.

### What not to change during a refresh

Do not alter the Tier 1 structural section unless new peer-reviewed research specifically
updates the StoryScope findings or equivalent. Do not remove the self-check section or
the audit mode protocol. Do not remove words from Tier 2 without evidence they've
declined in AI usage — absence of mentions in new sources is not the same as evidence
of decline.

---

## Context calibration

This skill is critical for:
- LinkedIn posts and professional messaging (readers are AI-literate and skeptical)
- Cold outreach and introductions (personal tone is the entire value)
- Thought leadership and articles (readers compare across many pieces)
- Any copy where trust, voice, or personality is the point

It matters less (but still applies) for:
- Internal documentation where clarity dominates
- Structured data deliverables where format is fixed
- Highly templated content where deviation from format would cause confusion

Even in lower-stakes contexts, apply Tier 2 vocabulary rules — concrete language is
always better than abstract language, regardless of audience.

---

## Quick self-check before delivering any copy

Ask yourself:
- Does this name anything real?
- Does this take a position someone could argue with?
- Does anything go slightly off-script from the obvious structure?
- Is there something here only this writer could have written?

If all four answers are no, the copy needs one more pass before it goes out.
