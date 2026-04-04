# Reddit Channel Strategy

Research compiled April 2026.

---

## Subreddits to Target

Ranked by fit + permissiveness for Typer's blind test approach:

| Subreddit | Members (approx.) | Fit | Notes |
|---|---|---|---|
| r/LocalLLaMA | 600k–1M | High | Technical audience, tolerates dev posts with substance. Qwen specifically popular here (2,400-upvote comment about Qwen on M4 Mac). No r/Qwen exists — this is where Qwen discussion lives. |
| r/ollama | 102k | High | Mac local AI users by definition. Small = manual moderation = forgiving. |
| r/LocalLLM | 129k | High | Same audience as r/LocalLLaMA, less scrutinised. Good second post. |
| r/MacApps | 172k | Medium-high | Natural home for Mac app posts. Dev posts appear culturally normal. |
| r/SideProject | 503k | Medium | Explicitly welcomes "I built this" + link. Less targeted audience. |
| r/alphaandbetausers | 24k | Medium | Built for testable tools. Blind test page qualifies. Small but explicitly permissive. |
| r/ChatGPT | 8–11M | Medium-low | Massive reach, aggressive automod. Only viable after building account karma. |

---

## What Gets You Banned

- Naked link drop with no surrounding content
- Cross-posting identical content to multiple subreddits within 24–48h
- Account under ~30 days old / under ~100 karma doing promotional posts
- Sales language: "best", "check out", "DM me"
- Posts where the link IS the entire point

The old 10:1 rule is no longer official Reddit policy, but in practice tech/AI subs expect closer to 95:5 (non-promotional to promotional). Large subs use automod; small subs use manual moderation.

**Shadowban risk:** Posting the same link to 20+ subreddits triggers site-wide shadowban. Don't spray.

---

## What Survives

- Posts where the link is additive, not the whole point
- A finding or result shared in the post body first ("I ran X experiment, here's what I found")
- Free, no-signup tool framing + privacy language ("no login, no logs")
- Genuine question to the community embedded in the post
- Upfront disclosure of builder status (transparency helps more than you'd expect)
- Technical grounding appropriate to the subreddit

**Best confirmed precedent:** A dev posted a patent search AI to r/LocalLLaMA (titled "I classified 3.5M US patents with Nemotron 9B on a single RTX 5090 — then built a free search engine on top"). Result: 65 upvotes, 20+ technical questions, NOT removed. Key factors: technical achievement front-loaded, link was to free no-login tool, "no logs" privacy framing.

---

## The Blind Test Framing

The concept is genuinely interesting to r/LocalLLaMA — this community debates model quality constantly. A post that shares a surprising result from the test and invites the community to add to it is native content for that sub.

**What the post needs to work:**
1. A finding in the post body (not just "go try this") — share a surprising result
2. Technical grounding (which models, how it runs locally on Mac)
3. "Free, no account" framing for the test page
4. A genuine question to the community

**Example framing that fits r/LocalLLaMA:**
> "I've been running local models on my Mac and got curious whether people can tell the difference between local and cloud AI in real use. So I built a blind test — 10 questions, two answers, pick which one you prefer. After 50+ responses the results surprised me: [specific surprising finding]. Test is at typer.space/blindtest if you want to add a data point."

Note: the blind test page needs to actually exist and work before posting. Don't link to a coming-soon page.

---

## Account Prep

Using an existing account is the right call. Before any Typer-related posts:
- Spend 2–3 weeks commenting helpfully in target subreddits (answer questions, engage threads)
- Do not cross-post identical content — write a fresh version for each sub
- Disclose you built Typer when posting (transparency reduces mod removal risk)

---

## Posting Order (recommended)

Start small and forgiving, build account karma in the local AI space, then scale:

1. **r/ollama** — smallest, most forgiving, directly relevant audience
2. **r/LocalLLM** — warm up in the local AI space before the bigger sub
3. **r/LocalLLaMA** — the main event once blind test page is live and has some data
4. **r/MacApps** — different angle, Mac-first framing
5. **r/ChatGPT** — only after account has history + karma from posts 1–4

---

## What We Don't Have Yet (blockers)

- Blind test page on typer.space (must be live before r/LocalLLaMA post)
- Results/data from the blind test (needed to write a compelling post body)
- Account karma in target subs (needs 2–3 weeks of normal participation first)

---

## Iteration Plan

Each post is a test. Read comments for what lands, adjust angle for the next round.

**Round 1:** Blind test — ChatGPT free vs Qwen 3.5 on M3 Pro, everyday questions. Subtext: local is already as good as free ChatGPT for normal use.

**Round 2 (if round 1 underperforms, or as a follow-up):** Benchmark comparison as models improve. Different hook — "the gap keeps closing" or "here's how the new [model] compares now." Answers will have moved on from the April 2026 snapshot, which is itself a story.
