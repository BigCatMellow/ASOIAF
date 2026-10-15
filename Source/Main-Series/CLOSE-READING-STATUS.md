# Five-book close-reading tracker

- Record role: `RESEARCH / COVERAGE RECEIPT`
- Status: `IN PROGRESS — FIRST PASS`
- Source of truth for chapter labels: [chapter index](../../research/chapter-index.md)
- Source file: [original five-book EPUB](A%20Game%20of%20Thrones%205-Book%20Bundle.epub), SHA-256 `cf12ce6d586a9b2717b6cefe373515d454f805b9b6193cde544c8abf028e61b8`
- Coverage checked: 2026-10-15

## Why this pass exists

The project has a strong selective [canon baseline](../../research/canon-baseline.md), [POV decision files](../../research/characters/README.md), and a [theory library](../../research/theories/README.md), but no complete chapter-by-chapter source review. This pass builds **one reliable chapter note at a time**, capturing the obvious causal spine **and** subtle textual signals that might become meaningful only later. It must not substitute a fan theory for an actual event or stop after extracting favorite clues.

## Verified corpus structure

The EPUB was opened locally on 2026-10-15. Its five title sections, navigation entries and paragraph text were extracted **temporarily for inspection** (not committed or copied to the public repository). The SHA-256 matches [SOURCES.md](../../SOURCES.md).

| Book | Narrative chapters including prologue/epilogue | New first-pass chapter notes | Still lacking new sequential first-pass notes |
|---|---:|---:|---:|
| [AGOT](01-A-Game-of-Thrones/NOTES.md) | 73 | 7 (Prologue, 1–6) | 66 |
| [ACOK](02-A-Clash-of-Kings/NOTES.md) | 70 | 1 (Prologue) | 69 |
| [ASOS](03-A-Storm-of-Swords/NOTES.md) | 82 | 1 (Prologue) | 81 |
| [AFFC](04-A-Feast-for-Crows/NOTES.md) | 46 | 1 (Prologue) | 45 |
| [ADWD](05-A-Dance-with-Dragons/NOTES.md) | 73 | 1 (Prologue) | 72 |
| **TOTAL** | **344** | **11** | **333** |

**Important:** The eleven files are *first-pass* source-grounded interpretive notes, **not certification that every line has undergone an independent microdetail audit**. Some cross-book chapters received focused checks in earlier work; those checks are not counted as completed sequential chapter notes. The earlier 45 short-fragment quote matches were a distinct narrow verification, not 45 extra reviewed chapters.

The source contains approximately 1,751,065 whitespace-delimited words by the local paragraph extractor; this is a processing count, not a claim of completed reading. AFFC's additional TOC 'Chapter 46' is a non-narrative author afterword and is deliberately excluded from the 46 narrative units.

## Reading order and proof of completion

1. **Read and locate:** confirm the complete EPUB chapter, POV, and chapter boundaries, including split HTML fragments.
2. **Plot first:** record the chapter's beginning/end, major decisions, changes of circumstance and consequences. Do not hide obvious story pillars.
3. **Knowledge:** separate **VERIFIED on-page**, **CHARACTER CLAIM**, **INFERRED**, **THEORY**, **UNKNOWN**. An on-page utterance proves someone uttered words, not that their account is true.
4. **Minor clue sweep:** catalog exact objects, colors, animals, symptoms, altered names, family claims, songs, dreams, reports, letters, absences, geography, timings, travel, magic, and contradictions worth testing. Record significance without assuming intention.
5. **Agency and continuity:** note who knows what and when, feasible choices, timing/communication constraints and named affected actors.
6. **Rival readings:** supply an ordinary non-mysterious interpretation and a disconfirming test for every consequential theory.
7. **Link, don't copy:** chapter files live at `<book>/chapters/`; the [cross-book clue queue](../../research/source-clue-index.md) links signals; canonical character/theory files retain ownership of evolving conclusions.
8. **Check:** confirm GitHub file exists, links resolve, locator agrees with [chapter index](../../research/chapter-index.md), source statement matches a scene, and status correctly describes scope. Independent challenge remains necessary before a theory is adopted.

## Current first-pass files

- **AGOT:** [Prologue](01-A-Game-of-Thrones/chapters/00-prologue.md) · [1 Bran](01-A-Game-of-Thrones/chapters/01-bran.md) · [2 Catelyn](01-A-Game-of-Thrones/chapters/02-catelyn.md) · [3 Daenerys](01-A-Game-of-Thrones/chapters/03-daenerys.md) · [4 Eddard](01-A-Game-of-Thrones/chapters/04-eddard.md) · [5 Jon](01-A-Game-of-Thrones/chapters/05-jon.md) · [6 Catelyn](01-A-Game-of-Thrones/chapters/06-catelyn.md)
- **ACOK:** [Prologue / Cressen](02-A-Clash-of-Kings/chapters/00-prologue.md)
- **ASOS:** [Prologue / Chett](03-A-Storm-of-Swords/chapters/00-prologue.md)
- **AFFC:** [Prologue / Pate](04-A-Feast-for-Crows/chapters/00-prologue.md)
- **ADWD:** [Prologue / Varamyr](05-A-Dance-with-Dragons/chapters/00-prologue.md)

## Next in-scope sequential task

Resume at `AGOT 7 (Arya)` without skipping basic plot. Continue through AGOT in publication order, while using cross-book checks only when they directly test a live clue or a contradiction. Recheck the four later prologues in full microdetail after the sequence reaches each respective book. Do not imply that 333 untouched chapters have been read.

## Review boundary

Reading notes, hypotheses and in-repository research updates are authorized. Final creative fates, official-status claims, large source quotations and distributing additional book copies are not. This pass does not commit EPUB text or book-derived long quotations.
