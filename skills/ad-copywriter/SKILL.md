---
name: ad-copywriter
description: Turns a creative brief into a stack of platform-ready ad headlines, bodies, and descriptions in a senior copywriter's voice — you pick the winners, polish, and launch.
---

# Ad Copywriter

## When to use

- You need Meta or Google ad copy and don't want to start from a blank brief
- Launching a new product or offer and want several angles tested, not one guess
- Your campaign data shows ads with low CTR or high CPA that need fresh variants
- You have a good-performing ad and want variations that keep what works while fixing what doesn't
- An agency quotes weeks of work for something you can generate and QA in an afternoon

## Workflow

1. **Write the brief (input: product info → output: creative brief)**
   Describe the product, the target audience, the core benefit, and the tone of voice — one paragraph each is enough. Don't skip the audience's pain point, because every headline will trace back to it. If there are compliance constraints (no before/after claims, no medical promises), put them in the brief now, not later.

2. **Set the angles and limits (input: brief → output: generation spec)**
   Decide how many angles to explore (3–5 is plenty) and how many variants per angle. Look up the platform character limits — headline, body, description — and write them into the spec. The AI should never have to guess the limits; every variant that comes back must already fit.

3. **Generate the stack (input: brief + spec → output: copy variants)**
   Have the AI work in the voice of a senior direct-response copywriter: one idea per variant, each tagged with its angle. Ask for headlines, body copy, and descriptions as separate sets so you can mix and match later. If two variants read alike, one of them gets cut.

4. **Mine your campaign data (input: ad performance CSV → output: rewrite targets) — optional**
   When you have past data, filter for ads with low CTR or high CPA above your threshold and generate variants specifically for those losers. This turns guesswork into a hit list. Keep the original ad ID attached to each variant so you can compare performance later.

5. **Pick, polish, QA (input: copy stack → output: launch-ready copy)**
   You read every word before it goes live. Cut duplicates, check every claim against the brief, and verify character counts. Flag anything that could fail ad review. Only after QA do the variants move into your ad tooling.

## Output spec

- Headlines, body copy, and descriptions grouped by angle, each tagged with its angle
- Every variant within platform character limits; the count stated next to each line
- Each variant traces back to a brief fact (pain, benefit, or offer) — nothing invented
- Data-driven variants carry a source line: which ad they replace and why it underperformed
- Companion template.md brief skeleton — fill in the blanks and use it

## Good vs. bad examples

- ❌ Bad headline: "Revolutionize your workflow with cutting-edge AI technology" (could describe any product; names no one, promises nothing concrete)
- ✅ Good headline: "Inbox zero by Friday: a 10-minute daily triage system for founders" (66 chars; names the outcome, the effort, and the audience)
- ❌ Bad body: "Our amazing platform delivers unparalleled value and will transform how you work, guaranteed!"
- ✅ Good body: "You forward receipts as they arrive; every Monday you get a clean expense report. No bookkeeping, no spreadsheet fiddling — just forward the receipts." (concrete mechanics, zero superlatives)
- ❌ Bad brief-to-copy: the brief says "targets freelancers" and the copy talks about "enterprise teams"
- ✅ Good check: every variant's audience line matches the brief's audience line word for word; a mismatch sends the variant back for rewrite
- Standard: every line must name one concrete thing — a feature, a number, a scene. Adjectives without evidence get cut.

## Notes

- Never invent claims: no "guaranteed results", no percentages without a source. An unverified number gets cut, not softened.
- Distilled from real cases: one writer fed a brief to an AI acting as a senior copywriter and got 5 bodies, 5 headlines, and 3 descriptions back, then picked and edited the winners; another ran ad-performance CSVs through a sub-agent to rewrite only the underperformers — both kept humans on QA and final launch.
- Character limits are the spec, not a suggestion: a 31-character headline in a 30-character slot is a wasted variant.
- One idea per variant: if a headline tries to say two things, it says neither.
- Compliance is yours, not the AI's: you sign off on every claim before anything goes to an ad platform.
