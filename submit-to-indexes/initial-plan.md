# Typer — Directory Submission Plan (Traffic & Lead Gen Focus)

The goal isn't backlinks for backlinks' sake. It's **people downloading Typer**. Every entry below is evaluated on one question: will this actually drive downloads or meaningfully improve Typer's Google ranking for searches like "local AI Mac app" or "ChatGPT alternative offline"?

Organised into three tiers based on expected download impact, not domain authority.

**Assets available**: Logo ✓, Mac App Store images ✓ (marketing-style with device frames and text overlays — work for most directories, but NOT for download sites or review platforms that expect raw UI screenshots).

**Assets still needed**: Raw app screenshots (just the UI, no device frames), a PAD file for download sites, and benchmark data for technical communities.

---

## Tier 1 — High traffic, high intent

These platforms have audiences actively looking for what Typer is. Every one of these should be done.

### 1.1 Launch platforms (one-time events, coordinate together)

These generate traffic spikes. Do them in the same week for compounding effect — people who see Typer on PH check HN, people on Reddit check PH, etc.

#### Product Hunt
- **Why it matters**: 5M monthly visitors. The "Featured on PH" badge is permanent social proof. Secondary press coverage multiplies the effect.
- **Expected traffic**: 1,000–10,000 visits on launch day depending on ranking
- **Submission**: producthunt.com/posts/new
- **Cost**: Free
- **Backlinks**: Nofollow (DR 91) — SEO value comes from secondary coverage
- **Ready to submit?** NO — needs serious prep
- **What's missing**: Hunter with followers (optional but helps), first comment draft, 10-20 genuine supporters lined up, launch day blocked for comment responses, tagline under 60 chars, product video or animated GIF
- **App Store images work?** Yes — PH wants polished marketing visuals
- **Best timing**: Tuesday–Thursday, post 12:01–12:30 AM PST. Avoid Apple event weeks.

#### Hacker News (Show HN)
- **Why it matters**: Front page = 20,000–30,000 visitors in a day. The audience writes blog posts about things they discover, creating organic dofollow backlinks.
- **Expected traffic**: 500–30,000 depending on whether it hits front page
- **Submission**: news.ycombinator.com/submit — title must start with `Show HN:`
- **Cost**: Free
- **Backlinks**: Nofollow (DR 91)
- **Ready to submit?** NO — needs prep
- **What's missing**: First comment with technical backstory (models used, inference approach, why local-only). Benchmark data. 4-6 hours blocked for comment responses. NO LLM-generated text anywhere — community is hostile to this. Username must not be "typer" or brand name.
- **Suggested title**: `Show HN: Typer – Free local AI chat for Mac, runs on-device, no API keys`
- **Best timing**: 8 AM–12 PM Pacific, Tuesday–Thursday
- **If it flops**: Can repost in a few weeks. HN mods have a "second chance" mechanism.

#### Reddit — r/macapps (~172–180K subscribers)
- **Why it matters**: The single most targeted subreddit. Every subscriber is a Mac user looking for apps.
- **Expected traffic**: 500–5,000 visits if post gets traction
- **Cost**: Free
- **Ready to submit?** ALMOST — needs some comment history in the sub first (1-2 weeks)
- **What's missing**: Build posting history by commenting on other r/macapps posts. Prepare screenshots (App Store images probably work here). Draft post title: "I built Typer – a free local AI chat for Mac that runs entirely on-device, no API keys"
- **App Store images work?** Yes — this sub is used to polished app marketing

#### Reddit — r/LocalLLaMA (~671K subscribers)
- **Why it matters**: Largest community of people running AI locally. They're your exact audience.
- **Expected traffic**: 1,000–10,000 if well-received
- **Cost**: Free
- **Ready to submit?** NO — needs technical prep
- **What's missing**: This audience is deeply technical. You need: supported models list, tokens/sec benchmarks on different Macs, RAM requirements per model, quantisation details, context window size, Metal acceleration details. A demo GIF showing inference speed is almost mandatory.
- **App Store images work?** No — they want to see actual UI, actual inference, actual benchmarks. Raw screenshots needed.

#### Reddit — r/SideProject (~503K subscribers)
- **Why it matters**: Explicitly designed for self-promotion. "I built..." posts are the norm.
- **Expected traffic**: 200–2,000
- **Cost**: Free
- **Ready to submit?** YES — App Store images + a short story about why you built it
- **App Store images work?** Yes

### 1.2 High-intent discovery platforms (permanent listings)

These have people actively searching for "AI tools" or "alternatives to ChatGPT." The listings stay up permanently and compound over time.

#### AlternativeTo
- **URL**: alternativeto.net → Sign up → "Suggest new application"
- **Why it matters**: People come here specifically searching for alternatives to ChatGPT, Copilot, Ollama, LM Studio. The intent is "I want something like X but different." That's Typer.
- **Expected traffic**: Slow build, but high-intent. Hundreds of clicks/month once established with reviews.
- **Cost**: Free
- **Backlinks**: Dofollow, DR 80–82
- **Ready to submit?** YES — but write the description carefully
- **App Store images work?** Yes
- **Critical note**: They reject "basic AI wrappers for LLMs." Frame Typer around on-device privacy, zero-config UX, and native Mac experience — not "chat with AI." List as alternative to: ChatGPT, Copilot, Ollama, LM Studio, GPT4All, Jan.ai, Claude
- **Action**: After listing, ask a friend to leave a "like" and tag Typer as an alternative on the ChatGPT and Copilot pages

#### There's An AI For That
- **URL**: theresanaiforthat.com/get-featured/
- **Why it matters**: 4M+ monthly visitors searching for AI tools. Biggest AI directory by traffic.
- **Expected traffic**: Moderate ongoing — depends on category ranking and reviews
- **Cost**: Free basic listing. Paid featured options exist but start free.
- **Backlinks**: Dofollow, DR 76
- **Ready to submit?** YES
- **App Store images work?** Yes
- **Tags**: local AI, on-device, privacy, offline, Mac, free, no API keys, chat assistant

#### Futurepedia
- **URL**: futurepedia.io → "Submit AI Tool" button
- **Why it matters**: 2M+ monthly visitors. Second-largest AI directory.
- **Expected traffic**: Moderate ongoing
- **Cost**: Free basic
- **Backlinks**: Dofollow, DA 72
- **Ready to submit?** YES
- **App Store images work?** Yes

#### Toolify.ai
- **URL**: toolify.ai/submit
- **Why it matters**: Growing fast, strong Google rankings for "best AI tools for [X]" queries
- **Cost**: Free basic
- **Backlinks**: Dofollow (6+ links on paid tier)
- **Ready to submit?** YES
- **App Store images work?** Yes

#### SaaSHub
- **URL**: saashub.com → Create account, submit listing
- **Why it matters**: Strong organic traffic for "[product] alternatives" searches. 856K+ monthly pageviews.
- **Cost**: Free
- **Backlinks**: Dofollow, DR 74–76
- **Ready to submit?** YES
- **App Store images work?** Yes
- **Action**: Tag as alternative to ChatGPT, Copilot, Ollama, LM Studio, GPT4All

---

## Tier 2 — SEO backbone + moderate direct traffic

These won't drive huge download spikes, but they build the backlink foundation that makes Typer rank for "local AI Mac app," "private AI chat," etc. Some also drive steady trickle traffic from people browsing software directories.

### 2.1 High-authority dofollow backlinks (SEO priority)

These are valuable primarily because a dofollow link from DR 80+ meaningfully moves your Google ranking. Direct traffic is a bonus.

#### G2
- **URL**: g2.com/products/new
- **Cost**: Free basic listing
- **Backlinks**: Dofollow, DR 91
- **Ready to submit?** NO — needs raw UI screenshots (not App Store images) and ideally 1-2 user reviews
- **What's missing**: G2 users expect actual product screenshots showing the real UI. Also need a detailed feature list and pricing info. Ask a friend to leave the first review after listing goes live — G2 pages with zero reviews don't rank.
- **Traffic**: Moderate. G2 pages rank extremely well for "[product] reviews" and "[product] alternatives" Google searches.

#### Capterra
- **URL**: capterra.com/vendors/sign-up
- **Cost**: Free basic listing
- **Backlinks**: Dofollow, DR 91
- **Ready to submit?** NO — same as G2, needs raw screenshots and feature list
- **Bonus**: One submission cross-publishes to GetApp (DR 86) + Software Advice (DR 85) automatically. Three listings for one.

#### SourceForge
- **URL**: sourceforge.net/software/vendors/
- **Cost**: Free
- **Backlinks**: Dofollow, DR 92
- **Ready to submit?** MAYBE — check their current submission flow. May need a downloadable file or link to Mac App Store.
- **Traffic**: 21M+ monthly visitors, though most are looking for open-source/dev tools

#### F6S
- **URL**: f6s.com → Create startup profile
- **Cost**: Free
- **Backlinks**: Dofollow, DR 83
- **Ready to submit?** YES — just a profile form. Instant approval.
- **Traffic**: Low direct traffic. Pure SEO play.
- **App Store images work?** Yes

#### StackShare
- **URL**: stackshare.io → Create free profile
- **Cost**: Free
- **Backlinks**: Dofollow, DR 80
- **Ready to submit?** YES — list Typer's tech stack (Swift, Core ML, Metal, whatever you use)
- **Traffic**: Low-moderate. Developers browse tech stacks.

#### FinancesOnline
- **URL**: financesonline.com/add-product/
- **Cost**: Free
- **Backlinks**: Dofollow, DR 74
- **Ready to submit?** YES
- **Traffic**: Low direct. They might write an expert review unprompted, which adds a second backlink.
- **App Store images work?** Yes

#### GitHub awesome lists (DA 96 dofollow — best SEO ROI per minute spent)
All of these are: fork repo → add Typer in alphabetical order → submit PR. Free. 15 min per PR. Dofollow from github.com (DA 96). Expect 1–4 weeks to merge. Direct traffic is minimal but the backlink value per effort is unmatched.

| Repo | URL | Fit |
|------|-----|-----|
| awesome-privacy | github.com/pluja/awesome-privacy | AI assistants section. Perfect fit. High stars. |
| awesome-local-ai (msb) | github.com/msb-msb/awesome-local-ai | Lists LM Studio, GPT4All. Direct peers. |
| awesome-local-ai (janhq) | github.com/janhq/awesome-local-ai | Run by Jan (competitor). Relevant audience. |
| awesome-local-llm | github.com/rafska/awesome-local-llm | On-device LLM tools. |
| awesome-llm-apps | github.com/Shubhamsaboo/awesome-llm-apps | LLM applications. |

**Ready to submit?** YES — just follow the existing format exactly.

### 2.2 Software download sites (trickle traffic, credibility)

These sites get traffic from people googling "download [app name] Mac." Not useful today, but once Typer has some name recognition, having a Softpedia or MacUpdate listing means you own that search result instead of a piracy site.

#### Softpedia Mac
- **URL**: mac.softpedia.com/user/submit.shtml
- **Cost**: Free
- **Backlinks**: Dofollow, DA 82–90
- **Ready to submit?** NO — prefers a PAD file (XML format). Also wants actual screenshots, not marketing images.
- **What's missing**: Generate a PAD file (use padbuilder.com or similar), prepare raw screenshots

#### MacUpdate
- **URL**: macupdate.com/content/submit
- **Cost**: Free
- **Backlinks**: Nofollow, DA 55–60
- **Ready to submit?** NO — needs raw screenshots and detailed app info. Content specialist reviews.
- **App Store images work?** Probably not — Mac-specific directory, expects proper screenshots

#### Softonic
- **URL**: publishing-center.softonic.com
- **Cost**: Free
- **Backlinks**: Nofollow, DA 92
- **Ready to submit?** NO — needs screenshots, goes through security review
- **Traffic**: 130M+ monthly users, auto-translated to 17+ languages. Massive reach if approved.

### 2.3 Startup and indie directories (long-tail SEO)

These add breadth to your backlink profile and occasionally send a trickle of visitors.

| Directory | URL | Cost | Backlink | Ready? | Notes |
|-----------|-----|------|----------|--------|-------|
| BetaList | betalist.com/submit | Free (2-4 wk queue) | Dofollow, DR 65-74 | YES | Submit and forget. App Store images fine. |
| Fazier | fazier.com | Free w/ badge on site | Dofollow, DR 80 | ALMOST | Need to add verification badge to Typer website. Worth it for DR 80 dofollow. |
| Crunchbase | crunchbase.com/add-new | Free | Nofollow, DR 89 | YES | Legitimacy signal. Quick form. |
| BetaPage | betapage.co | Free | Dofollow, DA 48 | YES | App Store images fine. |
| Launching Next | launchingnext.com | Free | Dofollow, DA 35 | YES | 2-minute form. |
| DevHunt | devhunt.org | Free | Dofollow, DR 59 | YES (needs GitHub auth) | Developer audience. Products visible 1 week. |
| Uneed | uneed.best | Free / $30 skip queue | Dofollow, DR 57-61 | YES | 9K newsletter subscribers. |
| OpenHunts | openhunts.com/projects/submit | Free–$23 | Dofollow | YES | Themed launch weeks (look for AI Week). |
| Startup Inspire | startupinspire.com | Free | Mixed, DA 72 | YES | High DA for the effort. |
| KillerStartups | killerstartups.com/submit-startup | Free (3-6 mo wait) | Dofollow, DA 56 | YES | Submit free, forget. |

### 2.4 Content-based lead gen (needs writing)

These aren't directories — they're platforms where a well-written article generates ongoing traffic and downloads.

#### Indie Hackers — journey post
- **URL**: indiehackers.com
- **Why**: Reportedly 23% conversion rate per engaged post
- **Ready?** NO — needs a genuine 800-1500 word story with real numbers (downloads, retention, technical decisions, $0 marketing). Budget 2-3 hours.

#### DEV.to — technical article
- **URL**: dev.to → publish with #showdev #mac #ai tags
- **Why**: Articles rank well in Google. DA 80+. Massive developer reach.
- **Ready?** NO — needs a "How I built Typer" article. 3-4 hours. Instant publish.

#### Hashnode — blog post
- **URL**: hashnode.com
- **Why**: Custom domain support means long-term SEO value on your own domain
- **Ready?** NO — same article effort as DEV.to. Can cross-post.

---

## Tier 3 — Low effort, low-but-nonzero value

Batch these in one sitting. Each takes 2-5 minutes. They won't drive meaningful traffic individually, but collectively they broaden your backlink profile and ensure Typer shows up when people search AI tool aggregators.

### AI directories (submit-and-forget)

Write one master description, one short description, and a tag set before starting. Then open tabs and paste through all of them. App Store images work for all of these.

**Tags to paste everywhere**: `local AI, on-device, privacy, offline, Mac, macOS, free, no API keys, chat assistant, no cloud, Apple Silicon`

| Directory | URL | Backlink | Notes |
|-----------|-----|----------|-------|
| FutureTools | futuretools.io/submit-a-tool | Dofollow, DA 60+ | |
| TopAI.tools | topai.tools/submit | Dofollow, DA 55+ | |
| AI Tools Directory | aitoolsdirectory.com | Dofollow, DA 50+ | |
| AiToolHunt | aitoolhunt.com | Dofollow, DA 40+ | |
| AIxploria | aixploria.com/en/ → "Submit an AI" | Dofollow | 8,800+ tools listed |
| ListMyAI | listmyai.net/submit-ai-tools | Dofollow | |
| AIModels.fyi | aimodels.fyi | Dofollow | 65K+ users |
| OpenTools.ai | opentools.ai | Dofollow | |
| All Things AI | allthingsai.com | Dofollow | |
| Insidr.ai | insidr.ai/ai-tools/ | Dofollow | |
| EasyWithAI | easywithai.com | Dofollow | |
| AI Top Tools | aitoptools.com | Dofollow | |
| PoweredByAI | poweredbyai.app | Dofollow | 50K newsletter |
| Dang.ai | dang.ai | Mixed | |
| The Next AI Tool | thenextaitool.com | Mixed | 43K+ tools |
| Altern.ai | altern.ai | Mixed | |
| AI Valley | aivalley.ai | Mixed | |
| DropYourAI | dropyourai.com/submit-tool | Dofollow | Free tier only |
| AI Scout | aiscout.net | Dofollow | |
| Dofollow.Tools | dofollow.tools | Dofollow | |
| OpenFuture AI | openfuture.ai | Dofollow | |
| Productivity Directory | productivity.directory | Mixed | |
| Stackviv | stackviv.ai | Mixed | |
| TheAISurf | theaisurf.com | Dofollow | |
| Best of Web | bestofweb.site | Dofollow | |
| Ben's Bites | news.bensbites.com | Dofollow | Large newsletter |

### Startup/software directories (batch submission)

| Directory | URL | Notes |
|-----------|-----|-------|
| SideProjectors | sideprojectors.com | DA 33 |
| 10Words | 10words.io | "Private local AI chat assistant for Mac. No cloud." |
| Startup Buffer | startupbuffer.com | |
| Startup Ranking | startupranking.com | |
| StartupJohn | startupjohn.com | |
| Pitchwall | pitchwall.co | |
| StartupStash | startupstash.com | |
| Startup Base | startupbase.io | Must be <1 year old |
| Alternative.me | alternative.me | DA 50-55 |
| Serchen | serchen.com | |
| SaaSWorthy | saasworthy.com | DA 50-55 |
| GoodFirms | goodfirms.co | DA 65 |
| Crozdesk | crozdesk.com | DR 65 |
| Software Suggest | softwaresuggest.com | |
| Firsto | firsto.co | Every product gets homepage visibility |
| ItsLaunched | itslaunched.com | Only 10 products/day |
| Launching.Today | launching.today | |
| TinyLaunch | tinylaun.ch | |
| MicroLaunch | microlaunch.net | Products rank for a full month |
| Awesome Indie | awesomeindie.com | One product featured/day |
| IndieShowcase | indieshowcase.io | 77+ products |

---

## Reddit — additional subreddits (long game)

These require genuine community participation before any mention of Typer. Start commenting now, post about Typer in 2-4 weeks.

| Subreddit | Subscribers | Strategy |
|-----------|------------|----------|
| r/AppHookup | ~182-200K | Strict title format: `[macOS] [Typer][Free] A local AI chat assistant that runs entirely on-device` |
| r/privacy | ~2M | Weeks of participation first. Only mention Typer in relevant "private AI" threads. |
| r/selfhosted | ~400K | Share with full technical details. Community will stress-test privacy claims. |
| r/ChatGPT | ~7M | Don't post. Comment on "looking for alternatives" threads with disclosure. |
| r/artificial | ~1M | Discussion-framed only: "Why local AI assistants are the future of privacy" |
| r/ArtificialIntelligence | ~1.3M | Same approach as r/artificial |
| r/macOS / r/mac | ~600K / ~1.1M | Comment on "what apps do you recommend" threads. No standalone promo posts. |
| r/degoogle / r/PrivacyGuides | ~200K / ~800K | Recommend Typer in relevant discussions only. |
| r/singularity | ~1M | Post about running AI locally on consumer hardware. |
| r/AlternativeTo | ~15K | Post as alternative to cloud AI. |
| r/shamelessplug | ~52K | Zero friction. Low engagement but free. |
| r/IndieHackers | ~15-20K | Use `[SHOW IH]` flair. |
| r/Entrepreneur | ~4.9M | Monthly "Share Your Startup" thread ONLY. Permanent bans for promo. |
| r/startups | ~1.3M | Monthly thread only. No URLs in main posts. |
| r/alphaandbetausers | ~22K | Beta testing feedback. |
| r/somethingimade | ~3M | "I made this" framing. |
| r/software | ~200K | Software recommendations. |

---

## Not worth pursuing (for now)

These either require outreach (not self-service), have barriers too high for current stage, or won't move the needle:

- **Setapp** — Developer partnership program, not self-service. Worth revisiting once Typer has traction.
- **MacStories** — Editorial pitch. Need reviews and download numbers to point to first.
- **CNET Download** — May need editorial approval, malware testing. Try after other download sites.
- **FileHippo** — Editorially curated, newer indie apps face high bar.
- **Lobsters / Tildes** — Invite-only. Start the invite process now, post later.
- **Privacy Guides / PRISM Break / FSF Directory** — Strongly prefer or require open-source. Only pursue if Typer goes open-source.
- **FossHub** — Open-source focus only.
- **HackerNoon** — 3-4 day editorial review, higher quality bar. Do DEV.to first.
- **Trustpilot** — DA 93 but the listing is a company profile, not a product directory. Do it eventually for branded search results.
- **EuroAlternative** — Too small to matter right now.
- **switching.software** — Tiny traffic. Perfectly targeted but low volume.
- **ethical.net** — Small, requires active community participation.

---

## Execution plan

### This week — submit everything that's ready

**Session 1 (1 hour)**: High-authority dofollow forms
1. F6S (DR 83, dofollow, instant)
2. StackShare (DR 80, dofollow)
3. AlternativeTo (DR 80, dofollow) — spend 10 min on the description
4. SaaSHub (DR 74, dofollow)
5. FinancesOnline (DR 74, dofollow)
6. BetaList (DR 65-74, dofollow, submit and forget)
7. Crunchbase (DR 89, nofollow, legitimacy)

**Session 2 (1 hour)**: AI directories — top tier
1. There's An AI For That (DR 76, 4M visitors)
2. Futurepedia (DA 72, 2M visitors)
3. Toolify.ai (DA 65+)
4. FutureTools, TopAI.tools, ListMyAI, AIModels.fyi

**Session 3 (1.5 hours)**: AI directories — full batch
- Open 20 tabs, paste master description and tags through all remaining AI directories

**Session 4 (1 hour)**: Startup directories + GitHub PRs
- All the quick startup directory forms
- Submit PRs to awesome-privacy, awesome-local-ai (both repos), awesome-local-llm, awesome-llm-apps

**Session 5 (30 min)**: Reddit groundwork
- Start commenting genuinely in r/macapps and r/LocalLLaMA (no Typer mentions yet)
- Post to r/SideProject (ready now)
- Post to r/shamelessplug and r/AppHookup

### Next 1-2 weeks — asset prep

- Take raw UI screenshots (no device frames, just the app)
- Generate PAD file
- Prepare benchmark data (tokens/sec on M1/M2/M3, RAM usage per model)
- Write Indie Hackers journey post
- Write DEV.to technical article
- Draft Product Hunt assets (tagline, first comment, video/GIF)
- Draft Show HN first comment

### Launch week — coordinate the big ones

Do these within the same 5-day window:
1. **Tuesday AM**: Product Hunt launch (12:01 AM PST)
2. **Tuesday**: r/macapps post, r/SideProject post
3. **Wednesday AM**: Show HN (8 AM Pacific)
4. **Wednesday**: r/LocalLLaMA post (with benchmarks)
5. **Thursday**: Indie Hackers journey post
6. **Friday**: DEV.to article

Block every day that week for comment responses.

### After launch week

- Submit to G2, Capterra (with raw screenshots + ask friends for reviews)
- Submit to Softpedia, MacUpdate, Softonic (with PAD file + screenshots)
- Add Fazier badge to site, submit to Fazier
- Continue Reddit long game (r/privacy, r/selfhosted, r/ChatGPT comments)
- Cross-post article to Hashnode
