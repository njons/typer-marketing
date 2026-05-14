# Personal Outreach

Find people who'd be interested in covering [Typer](https://typer.space) - a free, local AI chat app for Mac (Apple Silicon). No cloud, no account, no ads. Built with Tauri and Rust by a solo designer/developer.

## Strategy

For each angle:
1. **Find people** - search for writers, creators, podcasters relevant to the angle
2. **Cross-reference** - check for duplicates across angles
3. **Tier** - classify as low / mid / high influence
4. **Craft outreach** - personalize per person, angle, and medium
5. **Reach out** - start with low tier, learn what resonates, then scale up

## Tiers

- **Low**: Small following (<5K), personal blogs, niche newsletters. Good for learning what messaging works.
- **Mid**: Moderate following (5K-50K), established newsletters, active YouTube channels, known community voices.
- **High**: Large following (50K+), major publications, top podcasts. Approach last with social proof from earlier outreach.

## Drip sequence

Every email must be worth reading on its own. Never send "just following up."

### Email 1 - Day 0: Intro
- 4-6 sentences max
- Lead with something specific about THEIR work
- One sentence on what Typer is
- Soft ask: "I'd genuinely love your take on it"
- Link to app. No attachment, no press kit

### Email 2 - Day 5-7: Value-add (only if no reply)
- Share something genuinely interesting for their angle
- A data point, behind-the-scenes detail, or relevant news
- Light re-mention of the app

### Email 3 - Day 21-28: News peg (only if no reply)
- Tie to something real: milestone, new feature, press, PH launch
- "Thought you'd want to know" framing
- Last cold email. Then stop.

If they reply at any point, exit the sequence. Be human.

### Dormant re-activation
Only re-contact dormant contacts for genuinely newsworthy events: Product Hunt launch day, Apple feature, major press hit. One-off, not a drip.

## Angle-specific email hooks

| # | Angle | Email 1 opening hook |
|---|-------|---------------------|
| 1 | ChatGPT alternatives | "Saw your piece on [ChatGPT ads/alternatives]. I built something in that space..." |
| 2 | Apple Silicon dev | "Read your post on [Tauri/Rust/Metal]. Built a local AI app with this stack..." |
| 3 | Indie Mac dev | "Fellow indie dev. Loved your piece on [topic]. Been building a solo Mac app..." |
| 4 | Local AI / privacy | "Saw your coverage of [Jan/LM Studio/etc]. Built something similar but for non-technical users..." |
| 5 | Mac app roundups | "Love your [year] roundup. Shipped a free Mac AI app that might fit..." |
| 6 | Privacy & digital rights | "Read your piece on [privacy topic]. Built an AI app where nothing ever leaves the device..." |
| 7 | YouTube reviewers | "Love your Mac app videos. Built something that'd make a good demo..." |
| 8 | AI/tech newsletters | "Reader of [newsletter]. Shipped something your audience might find interesting..." |
| 9 | Anti-subscription | "Saw your post on [SaaS fatigue/self-hosting]. Built a free AI app, no subscription ever..." |
| 10 | Apple ecosystem press | Formal press pitch with press kit |
| 11 | Podcast hosts | "Would love to chat about [topic] on your show. Built a local AI app as a solo dev..." |
| 12 | "My setup" bloggers | "Loved your setup post. Built a Mac app you might want to try..." |
| 13 | AI for normies | "Read your guide on [AI for beginners]. Built an AI app that needs zero setup..." |

## Medium-specific notes

- **Blog/article**: Pitch a review, mention, or dedicated post
- **Newsletter**: Pitch a one-liner mention with link
- **YouTube**: Pitch a visual demo - offer to provide assets/screenshots
- **Podcast**: Pitch a guest spot or discussion topic
- **X/social**: Engage with their content first, build relationship before pitching
- **Reddit**: Don't DM cold. Engage in their communities, mention naturally.

## Research queue

Angles researched so far: 1, 3, 5, 8 (April 6, 2026 — 52 contacts found)

Next angles to research, in priority order:

| Priority | Angle | Why next |
|----------|-------|----------|
| 1 | 4 — Local AI / privacy | Warmest audience, was deferred from first session |
| 2 | 13 — AI for normies | Matches Typer's actual target user exactly |
| 3 | 6 — Privacy & digital rights | Strong differentiator, distinct from angle 4 |
| 4 | 7 — YouTube Mac reviewers | High leverage per contact, visual demo opportunity |
| 5 | 2 — Apple Silicon dev | Technical story, Tauri/Rust angle |
| 6 | 9 — Anti-subscription | Self-hosted/degoogle community |
| 7 | 10 — Apple ecosystem press | Needs social proof first, approach later |
| 8 | 11 — Podcast hosts | Needs social proof first, approach later |
| 9 | 12 — "My setup" bloggers | Evergreen SEO, lower urgency |

## Batches

- `batches/batch-01.md` — 20 contacts, queued for first send. Needs reference research on 13 people before sending.

## Files

- `contacts/index.md` - master list of all contacts (status: not contacted / queued-b1 / emailed / replied / engaged / featured)
- `contacts/{firstname-lastname}.md` - per-person detail and message history (created when someone replies)
- `angles/01-chatgpt-alternatives.md` through `angles/13-ai-for-normies.md` - research and people found per angle
- `emails/01-intro.md`, `02-value-add.md`, `03-last-touch.md` - drip sequence templates
- `batches/batch-01.md` - working doc for first send
