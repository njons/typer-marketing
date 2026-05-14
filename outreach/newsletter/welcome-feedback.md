# Newsletter welcome / feedback ask

First (and so far only) email sent to typer.space newsletter subscribers. Goal: make them feel personally noticed and ask for honest feedback on the app.

## Locked copy

**Subject:** `hey from Typer`

**From:** `"Duarte Carrilho da Graça" <duarte@typer.space>`

**Format:** plaintext

**Body (named version):**

```
hey [FIRST_NAME],

hope you're doing well!

thanks for signing up to the typer newsletter. the app is brand new and you're one of the first people on the list. honestly there isn't much of a newsletter yet, but i'd really appreciate hearing your thoughts and what to make of the app.

did you give it a try? anything that worked, anything that didn't, anything you'd want it to do? all of it is useful, i want to keep improving the app :)

Duarte
https://apps.apple.com/app/typer-ai/id6751274483
```

**Body (no-name version)** — same body, but the opener is just `hey,` (no name, no comma-name).

## Name-swap rules

For each subscriber email, decide between named and no-name:

- **Use first name** when the email handle contains an obvious first name (e.g. `mikeacoyle@gmail.com` → Mike, `peeter@solstrimma.se` → Peeter, `brousseaujeanluc@mac.com` → Jean-Luc), or when light research on the domain confirms the person.
- **`duck.com` prefix is user-chosen** — usually their real first name (e.g. `travis@duck.com` → Travis). Treat as named.
- **Use no-name (`hey,`)** for:
  - Anonymous relays: iCloud Hide My Email (`*@icloud.com` with random handles like `bays_addenda1d`, `lotions.visible.88`), Feedbin aliases (`*@feedb.in`)
  - Initials only with no confirmed first name (e.g. `wkuypers@`, `tmoynier@`, `gkolstad@`, `aga@`)
  - Handles with no name signal (e.g. `yellowmatcha@gmail.com`)
- When in doubt, prefer no-name over guessing.

## Send mechanism

Zoho Mail MCP, account ID `8557766000000002002`. One `mcp__zoho__ZohoMail_sendEmail` call per recipient (no Bcc — each email goes individually so it reads personal). Send all in parallel.

## Voice rules (must not change)

- Lowercase `ai`, `chat gpt`, `typer` (the brand uses capital T in subject only)
- No em dashes (`—`). Use commas, periods, or parentheses.
- No filler: genuinely, truly, honestly (except the one in this body which does real work), incredibly. `really` only in `really appreciate` / `really happy`.
- Sign `Duarte` (no last name, no title).
- Self-deprecating builder voice. No pitch language. No "free".
