# Free AI Agent Skills — full samples from AI Services Market

Five complete AI agent skills, free. Not teasers, not stripped-down demos — these are the full, working skills (instruction playbook + starter template), published so you can install them, read every line, and judge the quality before you ever spend a cent anywhere.

A skill is a small folder built around a `SKILL.md` file. Install it once, and your AI assistant (Claude, or any agent that supports the Agent Skills format) loads it on its own whenever a matching task comes up — carrying the process, the format, and the hard-won gotchas, so you stop re-explaining them in every chat.

## The five skills

| Skill | What it does |
|---|---|
| [Pitch Deck](skills/pitch-deck/) | A 10-slide investor deck structure — every slide answers exactly one investor question, with per-slide scripts. For fundraising, project reviews, Demo Day. |
| [Meeting Notes](skills/meeting-notes/) | Turns chat logs and transcripts into structured minutes: conclusions first, every action item with an owner and a deadline. |
| [Content Repurposer](skills/content-repurposer/) | Turns one finished long-form piece into a week of social content — carousel outlines, short-video scripts, posts — without inventing facts. |
| [Ad Copywriter](skills/ad-copywriter/) | Turns a creative brief into a stack of platform-ready ad headlines, bodies, and descriptions in a senior copywriter's voice. |
| [New Website SEO Growth](skills/new-website-seo-growth/) | Turns Google Search Console data into a content plan for a new site — indexation, impressions, CTR, gaps, the next batch of articles. |

## Install

**With the skills CLI:**

```bash
npx skills add __OWNER__/free-ai-agent-skills
```

**In Claude (claude.ai):** download this repo as a ZIP (green "Code" button → Download ZIP). Then in Claude: turn on code execution under Settings → Capabilities, go to Customize → Skills → **+** → Create skill → Upload a skill, and upload a ZIP containing one skill folder at a time (the `SKILL.md` must sit at the top level of the ZIP). Switch the skill on and test it in a new chat.

**In Claude Code:** copy a skill folder into `~/.claude/skills/` (personal) or your project's `.claude/skills/`, then restart.

## Is it safe to install third-party skills?

Read the files first — that's the whole point of publishing these in the open. Every skill here is plain text: a `SKILL.md` playbook and a `template.md`. No scripts, no binaries, nothing that phones home. Only ever install skills whose files you can inspect, from any source, including us. (Longer version: our [7-point safety checklist](https://aiservicesmarket.lol/learn/are-third-party-ai-skills-safe/).)

## Where these come from

These five are free samples from [AI Services Market](https://aiservicesmarket.lol) — a plain-English store of original AI agent skills (490+ more: documents, research, decks, marketing, small-business workflows, and more), $4.99 each or all-in with Pro. If these five earn their keep, the rest are there when you need them.

## License

MIT — use them, adapt them, ship them in your own projects. See [LICENSE](LICENSE). A link back to [aiservicesmarket.lol](https://aiservicesmarket.lol) is appreciated but not required.
