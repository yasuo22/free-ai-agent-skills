---
name: meeting-notes
description: Turn chat logs or meeting transcripts into structured minutes: conclusions first, every action item assigned to an owner with a deadline — ready to forward the moment the meeting ends.
---

# Meeting Notes

## When to use

- The meeting is over and all you have is a transcript or a chat log that needs to become readable minutes
- The discussion sprawled and "what we talked about" needs compressing into "what we decided and who's doing what"
- A cross-team meeting needs its conclusions synced so absentees get it in 3 minutes
- The boss or client wants a "one-pager" on the meeting outcome
- A long-running project needs a paper trail: when it was decided, who called it, and why

## Workflow

1. Read everything, grab the conclusions first
   - Input: the full chat log / transcript, attendee list if available
   - Action: find every decision, approval, rejection, and open item; ignore small talk and tangents
   - Output: conclusion list, one sentence each, noting who called it (e.g. "Called by Ana: …")

2. Extract action items
   - Input: conclusion list + source text
   - Action: break each action into "what to do" and find its owner and deadline; where the source is silent, mark "to confirm" instead of guessing
   - Output: action list, each with task, owner, and deadline

3. Compress the discussion
   - Input: the discussion passages behind each conclusion
   - Action: keep only the key disagreements, rationale, and data that shaped the conclusion; cut repeated and emotional remarks
   - Output: 3–8 discussion bullets, each stating who argued what and on what basis

4. Collect next-time topics
   - Input: "let's revisit" / "decide later" type remarks in the source
   - Action: list them separately as next-time topics, noting where each got stuck
   - Output: next-time topic list, one line each + what's blocking it

5. Assemble the final draft from the template
   - Input: conclusions + actions + discussion summary + next-time topics
   - Action: assemble per template.md: header info → conclusions → action table → discussion summary → next topics, with 1–3 key source quotes
   - Output: markdown minutes ready to forward

## Output spec

- The first 3 lines must state: what meeting, when, who attended, and the core conclusions — no scrolling to find the point
- Action items in a table with columns: task / owner / deadline / status; each item executable and verifiable
- Deadlines as concrete dates (e.g. Oct 15), never fuzzy words like "next week" or "ASAP"
- Names consistent throughout: full name or one fixed short form, never switching mid-document
- Discussion summary covers only conclusion-relevant disagreements and rationale, not the whole play-by-play
- Key conclusions carry a source quote (speaker + the gist of their words) for traceability
- Title format "date + topic" (e.g. 1011-Q4 Campaign Review) for easy archiving and search
- For minutes being broadcast, add a "sent to" line after the action table stating who received it

## Good vs. bad examples

- ❌ Bad minutes: a 2-page play-by-play of who said what, ending with "we'll follow up." (No decisions, no owners, no deadlines.)
- ✅ Good minutes: conclusions first, then an action table — task / owner / deadline — then 3 discussion bullets.
- ❌ Bad action item: "Ana to look into the API issue." (No deadline, no definition of done.)
- ✅ Good action item: "Ana to share the API error log with the vendor by Oct 15; status: in progress."
- ❌ Bad: "The team decided to move forward" — with no record of who decided or what "forward" means.
- ✅ Good: "Called by Ana: ship v2.1 on Oct 20 with the new checkout only; the dashboard redesign moves to next sprint."

## Notes

- Anything undecided stays "open / to confirm" — never decide on attendees' behalf. That's the red line of minutes.
- For sensitive topics (personnel, compensation, reorgs): record conclusions only, not verbatim details
- When speaker attribution is uncertain, mark "(sounds like XX)" — never misattribute
- Fix typos and slips in transcripts from context, but never change the meaning; when unsure, keep the original with a note
- Before sending, add a "please flag corrections by [date]" line to leave a window for fixes
