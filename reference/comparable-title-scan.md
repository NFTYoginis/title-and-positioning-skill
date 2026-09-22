# Comparable-title scan

Newly formalized this build — the real production trail referenced retail categories only informally, inside risk notes on individual candidates ("leans literary — strong for his audience, weaker for cold search"; "risks miscategorizing it as a diet/appetite book in an algorithm... needs the subtitle doing real work to lift it out of the weight-loss shelf"). Those notes were right, but they were never backed by an actual look at the shelf. This step formalizes that check as a required part of finalizing any real title decision, in either `first-time-development.md` or `retitle-for-positioning.md`.

## The step

Before locking any title, browse the book's actual retail category — Amazon Best Sellers / Amazon Charts for the category, or a category-equivalent list (Goodreads shelf, KDP category browse) when Amazon itself isn't reachable — and note:

1. **5–10 real titles/subtitles currently active in the category**, exactly as written.
2. **The dominant pattern** — question-title, outcome-promise, mechanism-in-subtitle, reframe-as-title, memoir-register, etc. Most categories cluster hard around one or two shapes.
3. **Where the candidate would sit** among them — does it read as a category match (helps a browsing reader recognize it belongs there) or a category mismatch (risks being scrolled past, or worse, picked up by the wrong reader)?
4. **Whether a mismatch is a real risk or an intentional pattern-interrupt.** A title that doesn't match the shelf's dominant pattern isn't automatically wrong — pattern-interrupt is a legitimate strategy (see the boldest-swing option in `first-time-development.md`) — but it has to be a chosen risk, stated as one, not an accidental one.

## If the scan can't be run

Say so plainly and mark the title decision as un-scanned in the output — see `rules.md`'s empty-input handling. Don't assert a shelf-fit claim without having actually looked.

## Worked reference — a real scan, dated 2026-09-22

Run during this build, against the same category *Are You Actually Hungry?* actually risked colliding with, per its own Round-1 risk notes. Amazon's own Best Sellers list wasn't reachable this session (503); Goodreads' "fasting" shelf was used as a category-equivalent proxy — noted here as a real limitation, not silently substituted.

**Top titles/subtitles on the shelf, as fetched:**

1. *Autophagy: Simple Techniques to Activate Your Bodies' Hidden Health Mechanism to Promote Longevity, Optimal Cellular Renewal, Detox, and Strength for a Happy Life*
2. *The Complete Guide to Fasting: Heal Your Body Through Intermittent, Alternate-Day, and Extended Fasting*
3. *Fast Like a Girl: A Woman's Guide to Using the Healing Power of Fasting to Burn Fat, Boost Energy, and Balance Hormones*
4. *A Hunger for God*
5. *Fast, Feast, Repeat: The Comprehensive Guide to Delay, Don't Deny® Intermittent Fasting*
6. *The Obesity Code: Unlocking the Secrets of Weight Loss*
7. *Life in the Fasting Lane: The Essential Guide to Making Intermittent Fasting Simple, Sustainable, and Enjoyable*
8. *Fasting: Opening the door to a deeper, more intimate, more powerful relationship with God*
9. *Fasting Can Save Your Life*
10. *Delay, Don't Deny: Living an Intermittent Fasting Lifestyle*
11. *Fast This Way: Burn Fat, Heal Inflammation, and Eat Like the High-Performing Human You Were Meant to Be*

**Dominant pattern:** overwhelmingly outcome-promise-in-subtitle — "burn fat," "boost energy," "balance hormones," "heal your body," "unlocking the secrets of weight loss." A secondary cluster is devotional/faith-framed fasting (*A Hunger for God*, *God's Chosen Fast*). Structurally, most subtitles stack a mechanism ("intermittent," "alternate-day," "extended") directly against a promised outcome.

**Where the real book's candidates actually sat:** *Are You Actually Hungry?* — a plainspoken question, no outcome-promise, no mechanism-naming — is a genuine category mismatch against this shelf's dominant pattern. This confirms, with real data, what Round 1's own risk note predicted informally: *"'Hungry' risks miscategorizing it as a diet/appetite book in an algorithm."* The eventual locked subtitle (*"The Missing Conversation About Detox, Wellness, and Common Sense"*) doesn't chase the shelf's outcome-promise pattern either — it's a deliberate pattern-interrupt, consistent with the book's own honesty-over-hype constraint (see `first-time-development.md`'s "constraints honored"), not an accidental mismatch. Naming this explicitly — chosen risk, not missed risk — is exactly what this step is for.

**What this scan doesn't cover:** Amazon's own live Best Sellers rank wasn't reachable this session; Goodreads shelf order reflects reader-curated shelving, not real-time sales rank, so treat the ordering as directional (what titles exist and what pattern they share), not as a live rank signal. If Amazon's own list becomes reachable in a later session, prefer it and note the switch.
