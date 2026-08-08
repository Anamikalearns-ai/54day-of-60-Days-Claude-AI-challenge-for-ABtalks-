# 54day-of-60-Days-Claude-AI-challenge-for-ABtalks-

NexaGrowth Digital website — Day 5: Clinic and Retail Shop case studies added, plus index.html/style.css/script.js finally split into real files (previously only embedded in README).

## Live preview
https://htmlpreview.github.io/?https://github.com/Anamikalearns-ai/54day-of-60-Days-Claude-AI-challenge-for-ABtalks-/blob/main/index.html

## What's in this repo
- `index.html` — full site markup (Hero, Services, About/Process, 3 Case Studies, AI Demo shell, Footer)
- `style.css` — complete design system (dark theme, amber/sage accents, Fraunces/Inter/IBM Plex Mono)
- `script.js` — mobile nav toggle; AI Demo logic reserved for Day 6

## Day 5 — what was built
- Fixed a structural issue: Day 3/4 code was only pasted inside README.md, not saved as real files. Today it was split into actual `index.html`, `style.css`, `script.js` — required before GitHub Pages can ever deploy this.
- Case Study #2 — Dental Clinic (Lucknow): 3 → 28 leads/mo, 3.6x ROAS, 8-week test window. Google Ads + GA4.
- Case Study #3 — Retail Clothing Shop (Kanpur): 12 → 65 leads/mo, 5.2x ROAS, 5-week test window. Meta Ads + GA4.
- Both reuse the exact case-card component built Day 4 — same bar chart, stat row, ROAS badge, disclaimer pattern. No new CSS classes needed, only new content.
- Verified all 3 case studies render and animate correctly via live preview.

## Key learnings
- Splitting content into real files vs. keeping it in README isn't cosmetic — GitHub Pages, `<link>`, and `<script src>` all depend on actual files existing at those paths. Catching this before Day 9 avoided a bigger fix later.
- A well-built reusable component (Day 4's case-card) makes Day 5 almost entirely a content task, not a design task — copy the block, swap numbers and narrative, done.
- `htmlpreview.github.io` is a free way to sanity-check a static GitHub file in-browser without waiting for Pages — useful for an Android-only, no-PC workflow.

## Coming Day 6
AI Marketing Audit tool — form + Claude API call. Per the locked System Design, the API key will be visible client-side (no server proxy in this version) — this will need a decision on a restricted/low-limit key before going live.

---
Built in public · Day 5 of the NexaGrowth capstone · #60DaysClaudeChallenge
