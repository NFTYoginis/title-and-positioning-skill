# Title & Positioning

A folder-based ICM specialist that generates and evaluates title/subtitle candidates for a book before it exists, and runs a retitle pass on an already-published book whose title isn't converting — plus the closely coupled back-cover/jacket copy for either.

This formalizes two real, already-evidenced patterns: a first-time-development trail run twice on one book (*Are You Actually Hungry?*), and a retitle-for-positioning workflow run identically three separate times across three other books on the same shelf (*Joint Dialogue Method*, *Hold The Room*, *Yin*). It is not a theory of how naming should work — it's a repeat of what already worked, four times.

## What it produces

An example from a real book: the title-development file for *Are You Actually Hungry?* (`TITLE-CANDIDATES.md`). Each candidate carries its own why-it-works and risk. One of the five from round 1, quoted as written:

> ### **It Was Never About the Toxins**
> *What fasting actually does, and the older reason we keep coming back to it*
>
> **Why it works:** This is the book's whole argument compressed to five words, and it's a genuine pattern-interrupt in the category — a detox book that opens by disowning the word. […]
>
> **Risk:** The boldest and the most exposed. A negative/contrarian title risks reading as cynical or click-baity if the cover and body don't immediately deliver the warmth […] It also flirts with *over*claiming-by-denial: a too-confident "never" could undercut the book's careful, tiered humility. […]

The same file ends round 1 with a safe pick (*Hearing Yourself Again*), a bold commercial swing (the title above) and a dark horse (*Are You Actually Hungry?*). The title the book locked on is that dark horse, per the file's own header.

## What this is

Two distinct workflows, chosen by what already exists for the book:

1. **First-time development** — no published title yet. 5 candidates a round, each with a why-it-works/risk pair, against a stated north star and the book's real constraints. Never a single winner: a safe pick, a bold commercial swing, and a dark horse. A new round runs when the manuscript's actual thesis evolves, not just on request.
2. **Retitle-for-positioning** — already published, not finding readers. The exact `_archive-old-title/` convention: old PDFs/PNGs archived, codenames and folder names unchanged, only the displayed title text changes. Proven three times running, no deviation.

Both feed a formalized comparable-title scan before any real decision locks, and both produce dated, versioned jacket/back-cover copy with a mandatory "does this copy actually belong to this book" check — a real incident on this shelf already caught one that didn't.

Full detail per pattern: `reference/`.

## Setup

1. Load this folder into a Claude Project, or point a Claude Code session at it — `SKILL.md` lets Claude Code auto-discover and trigger it from a natural request (e.g. "name this book" or "help me retitle"); it routes to `identity.md` → `rules.md`, then to the one `reference/` file the active situation needs.
2. Working from the raw files directly (no `SKILL.md` support): read `identity.md` → `rules.md` → `examples.md` in that order, then open only the `reference/` file for the situation actually in play.
3. Have the manuscript (or its real thesis, not a pitch) ready for first-time development; have a stated reason the current title isn't converting ready for a retitle pass.

## First-run prompts

- *"The manuscript's done — give me a round of title candidates."*
- *"This book's title isn't converting. Run a retitle pass."*
- *"Write the back-cover copy."*
- *"The manuscript's thesis changed since the last round — run a new one."*

## What this specialist does and doesn't do

See `identity.md` and `rules.md` for the full contract. In short: it never touches manuscript content, never designs a cover, never builds launch/funnel strategy, and never hands over a single title without its stated risk — it owns the title, subtitle, and jacket-copy artifact, using patterns that already worked four times across this shelf.

## Where this fits

The book-production shelf, numbered as in the catalog. The skill in this repo is in bold.

1. [Book Ghostwriting](https://github.com/NFTYoginis/book-ghostwriting-skill)
2. [Publishing Preparation](https://github.com/NFTYoginis/publishing-preparation-skill)
3. **Title & Positioning** (this repo)
4. [Book-to-Content Repurposing](https://github.com/NFTYoginis/book-to-content-repurposing-skill)
5. [Fact, Claim & Evidence Verification](https://github.com/NFTYoginis/fact-claim-verification-skill)
6. [Book Launch & Funnel Strategy](https://github.com/NFTYoginis/book-launch-funnel-strategy-skill)
7. [Book Format & Interior-Image Integrity](https://github.com/NFTYoginis/book-format-integrity-skill)

Previous: [Publishing Preparation](https://github.com/NFTYoginis/publishing-preparation-skill) · Next: [Book-to-Content Repurposing](https://github.com/NFTYoginis/book-to-content-repurposing-skill). All seven: [Book Production Skills](https://github.com/NFTYoginis/book-production-skills).

## License

MIT — see `LICENSE`.

---

Built by Gabe at The Quiet Ai. The Quiet Scribe Suite (early access) carries your context from one AI tool to the next: [thequietscribe.com](https://thequietscribe.com)
