# Retitle-for-positioning

For a book that's already published, already covered, and not finding readers. This is the better-proven of the two patterns this specialist owns — run identically **three separate times** across three different books on this shelf (*Joint Dialogue Method*, *Hold The Room*, *Yin*), documented in `GabeYoga-HQ/My-Cover-Designs/CLAUDE.md` § "Title Changes (Retitle Workflow)."

## The diagnosis, before the workflow

A retitle is a positioning correction, not a cosmetic one. The title made a claim about what shelf the book belongs on and who it's for; if it isn't converting, the most likely cause is that the claim is wrong for the actual book, not that the wording is merely unattractive. Confirm this before starting — see `rules.md`'s empty-input handling: don't run a retitle pass on an unstated or unverified "it's not converting" claim.

## The exact archive convention

Quoted directly from the source, character for character — this is the one thing in this whole specialist that must never be paraphrased:

> Archive convention used (old PDFs/PNGs → `_archive-old-title/`, codenames/folder names unchanged, only displayed title text changed).

Three separate parts, all three required:

1. **Old PDFs/PNGs → `_archive-old-title/`.** Every rendered asset under the old title — cover files, print PDFs, promotional PNGs — moves into an `_archive-old-title/` subfolder. Nothing under the old title gets deleted; it gets archived.
2. **Codenames/folder names unchanged.** The working project's internal folder name, script references, file-path conventions — none of it changes. If the book was internally called `jdm/` during production, it stays `jdm/` after the retitle to *Why Most Teachers Lose the Room* or whatever the new problem-aware title is. This is what keeps every existing reference, script, and cross-link from silently breaking.
3. **Only the displayed title text changed.** The actual visible title — on the cover, in the metadata, in marketing copy — is the only thing that moves. Everything structural underneath stays exactly where it was.

Getting any one of these three wrong breaks the convention: deleting old assets instead of archiving them loses the retail record; renaming the internal folder breaks every script and reference that points at it by name; changing anything beyond the displayed title (internal chapter file names, for instance) is scope creep the convention doesn't call for.

## What "problem-aware" means here

All three real retitles moved from a more abstract or credential-forward original title to a title that names the reader's actual problem. The pattern isn't "make it snappier" — it's "make it legible to someone who has the problem but doesn't yet know this book is the answer to it." Apply the same first-time-development discipline (why-it-works/risk pairs, a stated north star, a safe/bold/dark-horse recommendation — see `reference/first-time-development.md`) to generate retitle candidates; the workflow difference here is what happens *after* a new title is chosen, not how it's chosen.

## Sequence

1. **Diagnose** — confirm there's a real, stated reason the current title isn't converting (see `rules.md` empty-input handling).
2. **Generate candidates** — same why-works/risk discipline as first-time development, applied to the retitle framing (what problem does the new title name that the old one didn't).
3. **Run the comparable-title scan** — see `reference/comparable-title-scan.md` — before locking the new title.
4. **Lock the new title.**
5. **Archive** — move all old-title PDFs/PNGs to `_archive-old-title/`.
6. **Update the displayed title only** — cover, metadata, marketing copy. Leave every internal codename and folder name untouched.
7. **Hand off** — the new title to `publishing-preparation-skill` (re-typesetting the cover/metadata) and to `book-ghostwriting-skill` if any cover regeneration is needed.

## Precedent, named

Three books, one workflow, no deviation: *Joint Dialogue Method*, *Hold The Room*, *Yin* — all retitled to problem-aware titles, covers completed, archive convention applied identically each time. This is the strongest cross-book repetition evidence this specialist has for any single workflow. If a future retitle needs to deviate from this sequence, that's a real escalation — say so explicitly rather than quietly varying a workflow that's worked three times running.
