# Sources, provenance and evidence handling

- Record role: `REFERENCE`
- Primary information class: `FACT / KNOWLEDGE`
- Status: `ACTIVE`
- Lifecycle: `ACTIVE`
- Authority: Canon evidence hierarchy for this project; does not certify any fan theory.
- Canonical owner: this file
- Related: [chapter index](research/chapter-index.md), [baseline](research/canon-baseline.md), [roadmap](ROADMAP.md)
- Last source check: 2026-10-14

## Primary source: uploaded EPUB (local, private)

- File: `A Game of Thrones 5-Book Bundle.epub` (provided in the originating conversation).
- SHA-256: `cf12ce6d586a9b2717b6cefe373515d454f805b9b6193cde544c8abf028e61b8`.
- Contains: *A Game of Thrones* (AGOT), *A Clash of Kings* (ACOK), *A Storm of Swords* (ASOS), *A Feast for Crows* (AFFC), and *A Dance with Dragons* (ADWD).
- Chapter labels in [index](research/chapter-index.md) follow this EPUB's navigation. No stable printed page numbers; different editions paginate differently.
- Counts including prologues/epilogues: AGOT 73; ACOK 70; ASOS 82; AFFC **46 narrative units, plus an additional author afterword mislabeled 'Chapter 46' in the bundle's TOC**; ADWD 73. Total = 344 narrative units. AFFC narrative = prologue + chapters 1–45. 
- AFFC and ADWD overlap in time: explicitly reconcile before drafting inter-POV scenes.
- **Live repository change (2026-10-14):** The owner uploaded `Source/A Game of Thrones 5-Book Bundle.epub`, `Source/Fire & Blood.epub`, and `Source/The World of Ice & Fire.epub` in GitHub commit [`a201915`](https://github.com/BigCatMellow/ASOIAF/commit/a20191532bfd1cd8e3c2acc529167e19329c5163). This repository is PUBLIC. These binary files were not added by this research workflow. The latter two books are **not** part of the five-novel evidence baseline; they may be evaluated as separate sources later.\n- **Rights/visibility review required:** Publicly tracked commercial ebooks may create copyright/distribution risks. An `.gitignore` entry does **not** unpublish files already committed, and deletion of working-tree copies alone will not erase Git history. Do not upload further copies or extracted chapters. Confirm redistribution permission or move/remove from public history using an owner-approved path. Keep repo research files to concise paraphrase, chapter references, and original materials.

## Evidence tier and epistemic labels

**Tier A:** Narrated events/dialogue in uploaded novels. `VERIFIED` means the *text depicts* something, not that a narrator's opinion or a letter is true.

**Tier B:** Licensed, attributable supplementary writings when provided or independently verified: future Martin remarks, Dunk and Egg, *Fire & Blood*, *World of Ice & Fire*, TWOW samples. Maintain separate source listing; do not silently mix into five-book baseline.

**Tier C:** Community theories, show deviations, adaptations, conjectural outcomes. Record as `THEORY`, with disconfirmers.

**Labels:**
- `VERIFIED`: directly shown in a scene.
- `CHARACTER CLAIM`: attributed report, prophecy, rumor, assertion (may be false).
- `INFERRED`: textual interpretation with articulated reasoning.
- `THEORY`: speculative scenario or external proposed explanation.
- `UNKNOWN`: unestablished or insufficient evidence.

## Locator conventions and auditing

- Use `AGOT 70 (Jon)`, `ASOS 63 (Davos)`, `ADWD 69 (Jon)`.
- Named POV headings can vary; **chapter number is the EPUB-local locator**. Citation must include title abbreviation + number.
- For disputed claims, record immediate source and contradictory locator where known. Prefer concise paraphrase.
- Do not rely only on a secondary overview for a strong plot assertion. Every adoption requires a source path and a counterargument.

## Current limits

The uploaded EPUB was structurally indexed and selected late chapters read closely; **there has not been a line-by-line review of all 344 narrative chapters**. Other volumes and unpublished text have not been imported. Early character sheets are selective analyses, not exhaustive narrative histories.
