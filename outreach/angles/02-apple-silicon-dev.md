# Angle 2: Apple Silicon Native Development

**Hook**: "Local AI app built with Tauri + Rust, running inference via Metal on Apple Silicon."

**Why they'd care**: Real native Mac development (not Electron). Tauri is still relatively new. Rust on Mac is growing. Metal GPU for ML is underexplored territory.

## Search depth
- Status: deep (second pass 2026-05-14)
- Contacts found: 30 (10 original + 20 added 2026-05-14)
- Last searched: 2026-05-14
- Queries used: ["tauri vs electron", "rust macos app", "building with tauri", "rust native mac app", "apple silicon ml inference", "local llm tauri app"]
- Sources checked: corrode.dev, jonhoo.eu, fasterthanlime.com, gethopp.app, wezm.net, rymc.io, levminer.com, dolthub.com, aptabase.com, codenote.net
- Remaining leads: Swift/Rust interop bloggers, Metal GPU ML posts, Apple Silicon optimization writers

## People found

| Name | Platform | Tier | Notes |
|------|----------|------|-------|
| Matthias Endler | corrode.dev + "Rust in Production" podcast | mid | Rust consultant, blogger, @matthiasendler |
| Jon Gjengset | YouTube (97K) + jonhoo.eu | high | Rust educator, author of "Rust for Rustaceans" |
| Amos Wenger | fasterthanlime.com + YouTube | mid | Deep-dive Rust/systems writer, Mac user |
| Costa Alexoglou | gethopp.app blog | low | Wrote "Tauri vs Electron" deep-dive (Apr 2025), costa@gethopp.app |
| Wesley Moore | wezm.net | low | Rust blogger, curated Read Rust, wes@wezm.net |
| Ryan McGrath | rymc.io | low | Built Cacao (Rust AppKit bindings), writes Rust+Mac |
| Lev Miner | levminer.com | low | Built Authme with Tauri, wrote real-world Tauri vs Electron comparison |
| Eric Richardson | DoltHub blog | mid | Wrote DoltHub's Nov 2025 "Electron vs Tauri" migration post |
| Aptabase | aptabase.com | mid | Privacy-first analytics for Tauri apps, wrote "Why I chose Tauri" |
| Tadashi Shigeoka | codenote.net | low | Wrote "Why I Chose Tauri for Building a Local LLM App on macOS/Windows" |

---

### Draft emails

**Matthias Endler** (corrode.dev)
```
hey matthias,

your rust in production podcast has been my background noise for months - the episode on startup latency made me rethink a few things in my own build.

built a local ai chat for mac with tauri + rust, running inference via metal on apple silicon. no cloud, no account. thought you might find the stack interesting: https://typer.space

Duarte, made Typer
```

**Jon Gjengset** (jonhoo.eu)
```
hey jon,

"rust for rustaceans" got me through some rough lifetimes - grateful for how clearly you explain the harder parts.

built a local ai chat for mac in tauri + rust using metal for inference on apple silicon. no account, no cloud. would love to hear what you think: https://typer.space

Duarte, made Typer
```

**Amos Wenger** (fasterthanlime.com)
```
hey amos,

your "a half-hour to learn rust" post is the best entry point to the language I've found - I still send it to people.

built a local ai app for mac with tauri + rust - running inference through metal on apple silicon. no cloud, no account. thought you might find the stack interesting: https://typer.space

Duarte, made Typer
```

**Costa Alexoglou** (gethopp.app)
```
hey costa,

your tauri vs electron deep-dive was the most honest comparison I've read - you didn't hedge on the rough edges.

I went with tauri for a local ai chat app for mac - running inference on-device via metal. no account, no cloud. thought you might find it interesting given your own experience: https://typer.space

Duarte, made Typer
```

**Wesley Moore** (wezm.net)
```
hey wes,

been following wezm.net for a while - your rust on freebsd coverage is a great reminder how far the ecosystem has come.

built a local ai chat for mac with rust + tauri, running models via metal on apple silicon. no account, no cloud. would love to hear what you think: https://typer.space

Duarte, made Typer
```

**Ryan McGrath** (rymc.io)
```
hey ryan,

cacao is genuinely useful - the idea of writing mac apps in pure rust without a swift bridge is the right direction.

built a local ai chat for mac using tauri + rust with metal for inference on apple silicon. no account, no cloud. thought you might find the stack interesting: https://typer.space

Duarte, made Typer
```

**Lev Miner** (levminer.com)
```
hey lev,

your real-world tauri vs electron comparison was the most useful thing I found when I was deciding - the memory numbers especially.

went tauri for a local ai chat app for mac - on-device inference via metal, no cloud, no account. thought you might appreciate seeing another tauri app in the wild: https://typer.space

Duarte, made Typer
```

**Tadashi Shigeoka** (codenote.net)
```
hey tadashi,

saw your post on why you chose tauri for a local llm app - that's almost exactly what I built.

made a local ai chat for mac - tauri + rust, inference via metal on apple silicon, no cloud, no account. would love to hear what you think: https://typer.space

Duarte, made Typer
```


---

### New contacts (added 2026-05-14, second pass)

| Name | Platform | Tier | Contact | Why |
|------|----------|------|---------|-----|
| Ken (Code to the Moon) | YouTube ~100K + Rust + LLM focus | high | ken@cttm.io | Covers Rust AND LLMs — Typer is almost tailor-made for his content |
| Mattt (NSHipster) | Blog, legendary Apple dev community | high | X @mattt | Already wrote about Ollama + MCP in 2025. Direct topical hit. |
| Paul Hudson | hackingwithswift.com, 100K+ newsletter | high | paul@hackingwithswift.com | Huge Mac/iOS dev audience. "Typer built without Swift" angle. |
| Daniel Thompson-Yvetot | Tauri co-creator, Verso browser | high | GitHub / X DM | Literally co-built Tauri. Typer is a Metal + Rust production Tauri app. |
| Allen Wyma (Rustacean Station) | Podcast, active Feb 2026 | mid | hello@rustacean-station.org | Podcast about Rust builders — guest pitch opportunity. |
| Bogdan Pshonyak (Let's Get Rusty) | YouTube 1.2M | high | bogdan@letsgetrusty.com | Largest Rust YouTube channel. Mention as real-world Rust Mac app. |
| Tris Oaten (No Boilerplate) | YouTube 279K | high | Mastodon @tris@namtao.com | Rust safety/correctness evangelist. Local-first = his narrative. |
| Jeremy Chone | YouTube 60-70K, production Rust | mid | jeremy@britesnow.com | Production-Rust focus, Tauri + Metal is his kind of real-world app. |
| Niko Matsakis | babysteps blog, Rust core team | mid | niko@alum.mit.edu | Borrow checker designer. Credibility anchor. |
| Chris Krycho | sympolymathesy.net, Rust book co-author | mid | hi@chriskrycho.com | Co-authored official Rust book. Async Rust + Tauri angle. |
| Alice Ryhl | ryhl.io, Tokio core + Google Android Rust | mid | alice@ryhl.io | Core async Rust. Typer's async architecture relevant. |
| Finbarr Timbers | artfintel.com, 5K researcher subscribers | mid | Substack DM | Writes about transformer inference. Metal on Apple Silicon is his beat. |
| Tim Dettmers | timdettmers.com, QLoRA inventor | mid | dettmers@cmu.edu | Quantization godfather. Typer uses quantized models on Metal. |
| John Sundell | swiftbysundell.com | mid | john@sundell.co | Mac dev audience. "Built without Swift" angle. Back from hiatus 2025. |
| Bob Peters (Rust Trends) | newsletter, biweekly, thousands of devs | low | rust-trends.com contact form | Newsletter covers Rust in production. Easy project mention. |
| Rust Bytes editors | weeklyrust.substack.com, 2400+ | low | rustaceanseditors@gmail.com | Weekly Rust newsletter. Project spotlight format. |
| Mara Bos | blog.m-ou.se, "Rust Atomics and Locks" | mid | X @m_ou_se (lower blogging activity) | Rust atomics/concurrency author. Metal + concurrency angle. |
| withoutboats | without.boats, async/await designer | mid | Bluesky @without.boats (less active) | Designed Rust async/await. Typer is downstream production user. |
| Ken Logan (Logan Smith) | YouTube _noisecode, systems Rust | low | YouTube About DM | Rust from C++ angle, smaller but targeted. |
| Youngju Kim | youngju.dev, Apple Silicon LLM deep-dive | low | fjvbn2003@gmail.com | Just wrote March 2026 deep-dive on Apple Silicon inference. High topical hit. |
