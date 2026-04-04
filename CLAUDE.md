# Typer Marketing

This repo contains marketing research, content, and assets for Typer.

**Website:** https://typer.space
**App Store:** https://apps.apple.com/app/typer-ai/id6751274483
**App Store ID:** 6751274483
**Website repo:** ../website
**Support:** studio@satellite.studio (Satellite Studio)

---

## What is Typer

Typer is a free, local AI chat app for macOS (Apple Silicon only). It runs AI models directly on the Mac — no cloud, no account required. It also supports web search, powered locally (no data sent to external servers).

**Tagline:** "Ask your Mac anything."
**Sub-headline:** "Free. Private. No internet needed."

### How it works for users
- Download from the Mac App Store (free)
- On first run, the app detects machine specs and prompts to download an appropriate model
- Default/baseline: ~500MB download (currently Qwen 3.5, will evolve as models improve)
- Better models offered based on machine capability
- No setup, no account, no configuration required

### Key features
- **Free, no ads, forever** — no monetization plans
- **Fully private** — chats never leave the device
- **Works offline** — no internet required for chat
- **Web search** — can search the web locally without sending queries to external servers (unique differentiator vs all other local AI tools)
- **Auto-updates** — downloads better models automatically as they improve
- **Vision/image analysis** — coming soon

### Platform
- macOS only (Apple Silicon required — M-series chips)
- Intel Macs: not supported
- iOS: waitlist (not yet available)
- Windows/Linux: not planned

---

## Target Audience

### Primary segments
1. **Non-technical Mac users** — people who don't know much about AI but want to run it locally. NOT targeting AI enthusiasts or model-watchers. Avoid jargon (don't mention "Qwen", "LLM", "inference", etc.)
2. **Privacy-first users** — don't want to share data with companies or pay subscriptions
3. **Offline/travel users** — don't always have reliable internet (travelers, commuters)
4. **Long-tail general public** — people becoming dependent on AI who want to know how to set it up without subscriptions, data sharing, or cloud dependency. NOT interested in the model race.

### Key assumption
Many casual ChatGPT users don't have highly powerful machines (they don't care about specs), but a lot of them bought a Mac in the past 6 years — those Macs can run Typer. These people know ChatGPT (it's synonymous with AI for them), run out of tokens, and hear about AI constantly. The bet: some subset of them will want to put AI on their own computer when they understand they can.

---

## Positioning & Messaging

### Current core hook (hypothesis being tested)
The ChatGPT ads narrative: In February 2026, ChatGPT started showing ads to free users and made $100M in six weeks. Typer is the antidote — private, free, no ads, on your Mac.

This messaging is expected to evolve. Features will be highlighted more prominently beneath this narrative as the site develops.

### Voice and tone
- Match the website voice: conversational, confident, slightly cheeky, anti-corporate
- Example: "We don't even have your data."
- Friendly and accessible to someone who has never heard of Qwen or local AI
- Do NOT use: "LLM", "inference", "quantization", "GGUF", model names, benchmark scores
- DO use: plain English, "on your Mac", "private", "free", "no account needed"

### Website copy patterns (study these)
The site uses very short, punchy sentences — often just a feature name followed by one line. Not bullet points, not paragraphs. Rhythm and confidence over completeness.

Feature name style: "Always ad-free." / "Just you and your Mac." / "Use from anywhere." / "Always cutting edge."
Follow-on lines: single sentence, plain English. "No account and no tracking. Chats stay on your device."

Notable lines to draw from:
- Hero: "Ask your Mac anything."
- "This here is the only ad you'll ever see." — self-aware, cheeky
- "All you need to use Typer is your Mac. No internet or signup."
- "Try Typer. It's free."

Tagline pattern that works: short anchor + three "no X" beats + punch word at end.
Example: "Ask your Mac anything. Free AI, no cloud, no account." (54 chars)
Example: "AI on your Mac. Free, private, no account — ever." (50 chars)

"ever" at the end of a sentence carries unusual weight in this voice. Use it sparingly.

### Key differentiator
Typer is the only local AI product that combines privacy/offline with web search. Every competitor is either fully offline OR fully cloud. Typer bridges both — but still keeps queries private.

### Blind test — details
A live interactive blind test is being built for the website (typer.space). Details:

- **What's compared:** ChatGPT free tier vs Typer (running Qwen 3.5 on an M3 Pro — not the newest but a solid mid-range Apple Silicon machine)
- **Mechanic:** User sees Answer A and Answer B side by side, picks preferred answer, repeated 7 times. At the end they see their score: how many of their picks were Typer vs ChatGPT.
- **Genuinely blind:** Even the makers don't know which answer is which during the test. This is important for credibility.
- **Topics:** Mundane everyday questions — recipes, trip advice, moving to a new city, buying shoes, writing a story for a child. Aimed at the normal person, not developers. Nothing is stopping technical users but that's not the target.
- **Snapshot:** Answers captured at a fixed point in time (April 2026). Post copy should acknowledge this.

**What to disclose where:**
- **Reddit posts (technical subs like r/LocalLLaMA):** Include full details — Qwen 3.5, M3 Pro, vs ChatGPT free, methodology, snapshot date. The community expects this and will call out vagueness.
- **Marketing website:** Do NOT mention model names or hardware specs. That detail is what the tech community cares about, not the general audience Typer is targeting.

Do not use results in copy until the page is live and has real response data to cite.

---

## Marketing Goals

### Phase 1: Pre-launch (now)
- Get the website link out there in relevant communities
- Build awareness among people who have already downloaded other local AI apps
- Build a pre-launch audience ahead of Product Hunt

### Phase 2: Product Hunt launch
- Target: 500-1,000 upvotes (would make Typer #1 indie local AI launch in PH history; current ceiling is Llamao at 523)
- Launch day: Tuesday or Wednesday in January, March, or September at 12:01 AM PT
- Key cross-post channels: r/MacApps, r/LocalLLaMA, r/Apple, Hacker News, X/Twitter
- Tagline must anchor to ChatGPT, plain English, mention Mac — no jargon

### Phase 3: Post-launch audience building
- Grow organic community
- Long-tail SEO / content strategy

---

## First Marketing Channel: Reddit

**Target:** People who have already downloaded other local AI apps. They don't need convincing that local AI works — they just need to know Typer exists and is simpler/better.

**Key subreddits:**
- r/LocalLLaMA (300K+ members — core local AI community)
- r/MacApps
- r/MacOS
- r/apple
- r/ChatGPT (for the "I'm tired of running out of tokens" angle)

**Content formats:** Text posts and images. Video on existing platforms (no new YouTube channel). May repurpose video content that already exists.

**Goal:** Collate insights and understand what resonates. Track results and build understanding of what messaging works before scaling.

---

## What This Repo Is For

- Marketing research and competitive analysis
- Content drafts (Reddit posts, social copy, ad copy, blog posts)
- Campaign tracking and results
- Audience and channel insights
- Pre-PH launch materials

---

## PH Launch Research Summary

Key findings from RESEARCH.md in the website repo (../website/RESEARCH.md):

**What works:**
- Anchor tagline to ChatGPT in plain English (no jargon)
- Mac-only is an advantage on PH (audience skews Mac, Apple-only products average 2x score)
- Show maker identity (named person, not faceless product)
- Hard social proof numbers (downloads, ratings, test sample sizes)
- Reply to every PH comment within 30 min on launch day
- Build PH "coming soon" page 3-4 weeks before to collect followers

**What kills launches:**
- Jargon in tagline ("LLM", "WebGPU", "inference")
- Weekend or summer launches (July/August/December)
- No category tags on PH
- Ghosting the comments
- No pre-built PH audience

**Website gaps to address before PH:**
1. Add maker name/attribution
2. Add screenshots or 30-sec video
3. Back up blind test claim with sample size
4. Dedicated web search section (unique differentiator, currently invisible)
5. FAQ section (6-8 questions)
6. Model/system requirements info
7. Sticky nav with Download CTA
8. One external proof point (blog, newsletter)

---

## Competitor Landscape (Local AI)

| Product | PH Score | Platform | Notes |
|---------|----------|----------|-------|
| Llamao | 523 | Android + iOS | Top indie local AI on PH |
| Jan | 341 | Mac/Win/Linux | Strong social proof, 5.3M downloads |
| fullmoon | 337 | iOS only | Jordan Singer's following |
| Apollo AI | 302 | iOS only | Bad site, good launch execution |
| RecurseChat | 121 | macOS | Feature dump, no proof |
| LM Studio | 0 | Mac/Win/Linux | Millions of users, zero PH execution |

**The gap:** No local-first AI app has broken 1,000 upvotes on PH. The category is wide open.
