---
name: new-website-seo-growth
description: Helps AI turn Google Search Console data into a content plan for a new website — indexation → impressions → CTR → average position → pages → keywords → content gaps → the next batch of articles. For new sites (0–12 months) that need to grow organic traffic from zero with data, not guesswork.
---

# New Website SEO Growth

## When to use

- Your website is new (0–12 months) and organic traffic is near zero — you need a data-driven content plan, not guesswork
- You exported GSC data (Performance: queries + pages, last 28 days or 3 months) and want to know what it's actually telling you
- You need to decide: which pages to fix, which keywords to target, what to write next — in what order
- You're about to write a batch of articles and want each one aimed at a gap the data reveals
- Traffic plateaued after the first few months and you need to find the next lever

## Workflow

1. **Indexation (input: GSC coverage / indexing report → output: indexation health)**
   Check submitted vs indexed pages. If indexed is under ~80% of submitted, diagnose why before writing anything new: crawl budget, thin content, no internal links, technical blocks (noindex, canonical, robots). Writing new articles when Google won't index the old ones is pouring water into a leaking bucket — fix the leak first.

2. **Impressions (input: GSC Performance → output: impression map)**
   Total impressions and the trend (up / flat / down), plus which pages and queries drive them. Impressions without clicks are the opportunity pool — Google is testing you in the SERPs. Map exactly where those tests are happening.

3. **CTR (input: impressions + clicks → output: CTR diagnosis)**
   Compare actual CTR against the expected CTR for your average position. Low CTR at good positions (1–10) = title/meta problem → rewrite them. Low CTR at bad positions (30+) = ranking problem, not a CTR problem — don't fix the wrong thing. State which one it is for each case.

4. **Average position (input: GSC Performance → output: position tiers)**
   Bucket every query: page 1 (1–10), striking distance (11–30), invisible (30+). Striking-distance queries are the highest-ROI targets — small pushes move them onto page 1. Invisible queries need new or heavily strengthened pages, not tweaks.

5. **Pages (input: page-level GSC → output: page verdicts)**
   For each indexed page: impressions, clicks, average position — then a verdict. Keep (it's working, leave it alone). Improve (impressions but no clicks → title/meta or intent mismatch). Consolidate (2+ pages ranking for the same query → merge into one strong page). Prune (zero impressions after 90+ days, no backlinks, no internal links → 301 to the closest surviving page).

6. **Keywords (input: query-level GSC → output: keyword tiers)**
   Group queries by intent — informational, commercial, navigational — and by branded vs non-branded. A healthy new site shows non-branded informational queries growing. If it's all branded, you're not acquiring new demand; the content plan must target non-branded informational queries.

7. **Content gaps (input: keyword tiers + page verdicts → output: gap list)**
   Find four kinds of gaps: ① queries with impressions but no dedicated page (write one) ② queries at positions 11–30 (strengthen the existing page) ③ topics the query themes point to that you haven't covered (from competitors' angles) ④ question-queries (who / what / how) you haven't answered. Each gap cites its GSC evidence.

8. **Next batch (input: gap list → output: article plan)**
   Produce the next batch: 5–10 article titles, each with target keyword, intent, the gap it fills, internal-link targets, and an H2 outline. Prioritize by impression volume × striking-distance proximity. Sequence it: quick wins first (strengthen existing pages), then new pages for the biggest gaps. Include what NOT to write — the topics the data says to skip.

## Output spec

- Deliverable 1 — GSC health snapshot: indexation %, impressions trend, CTR vs expected, position distribution. One page, numbers plus a one-line diagnosis each.
- Deliverable 2 — Page verdicts table: URL | impressions | clicks | avg position | verdict (keep / improve / consolidate / prune) | action.
- Deliverable 3 — Keyword tiers: intent × branded/non-branded, top 20 queries with position + impressions + CTR.
- Deliverable 4 — Content gap list: gap | GSC evidence | type (new page / strengthen / consolidate).
- Deliverable 5 — Next batch article plan: 5–10 titles, each with target keyword, intent, gap filled, internal-link targets, H2 outline, and priority order.
- All thresholds stated up front (e.g. "striking distance = positions 11–30", "prune = zero impressions after 90 days"). No vanity metric without a decision attached to it.

## Good vs. bad examples

- ❌ Bad: "Write more content about SEO." (no data, no target, no reason — a wish, not a plan)
- ✅ Good: "Query 'how to install a skill' — 1,240 impressions, position 14, 0.8% CTR. Gap: no dedicated page; impressions land on the homepage. Action: new article 'How to Install a Skill in 2 Minutes', target the query, link it from the Install page. Priority 1."
- ❌ Bad: "Your CTR is low, rewrite all titles." (wrong diagnosis — treats a symptom)
- ✅ Good: "CTR 0.6% at avg position 42 — that's a ranking problem, not a CTR problem. Titles are fine; the page needs internal links and authority first. Rewrite titles only for the 3 queries already at positions 5–10 with below-expected CTR."
- ❌ Bad: "Delete every page with no traffic." (too aggressive, no timeframe, destroys option value)
- ✅ Good: "3 pages, zero impressions after 120 days, no backlinks, no internal links → prune (301 to the closest surviving page). 2 pages, zero impressions after 30 days → too early; give them 90 days and one internal link first, then re-judge."

## Notes

- GSC data is the boss. If the data says a page is invisible, no amount of "but the content is good" overrides it. Diagnose, don't defend.
- New sites live at positions 11–50 for months. That's normal, not failure. The plan is to farm striking distance — not to chase position 1 on day one.
- Never write new articles to fix an indexing problem. If Google won't index what you have, more pages won't help. Fix crawl, internal links, and thin content first.
- Cannibalization is the classic new-site disease: three posts targeting the same keyword, all ranking at #25. Consolidate — one strong page beats three weak ones.
- CTR benchmarks are position-dependent. 1% CTR at position 8 is bad; at position 28 it's expected. Always compare against the expected CTR for that position, never against a flat number.
- Re-run this monthly. GSC is a movie, not a snapshot — the trend tells you whether the plan is working. Keep each month's snapshot so you can compare.
- The "what NOT to write" list is as valuable as the article plan. A new site's scarcest resource is writing time — spend it where the data points.
