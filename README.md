# Title & Positioning

A folder-based ICM specialist that generates and evaluates title/subtitle candidates for a book before it exists, and runs a retitle pass on an already-published book whose title isn't converting — plus the closely coupled back-cover/jacket copy for either.

This formalizes two real, already-evidenced patterns: a first-time-development trail run twice on one book (*Are You Actually Hungry?*), and a retitle-for-positioning workflow run identically three separate times across three other books on the same shelf (*Joint Dialogue Method*, *Hold The Room*, *Yin*). It is not a theory of how naming should work — it's a repeat of what already worked, four times.

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

## License

MIT — see `LICENSE`.
