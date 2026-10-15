# Passage-fragment verification receipt — 2026-10-14

- Record role: `RESEARCH / VERIFICATION`
- Primary information class: `FACT / KNOWLEDGE`
- Status: `PASS FOR LISTED TESTS; NOT A COMPLETE CASE REVIEW`
- Lifecycle: `ACTIVE`
- Parent: [theory library](README.md)
- Source: user-supplied `A Game of Thrones 5-Book Bundle.epub`, SHA-256 `cf12ce6d586a9b2717b6cefe373515d454f805b9b6193cde544c8abf028e61b8` as listed in [SOURCES.md](../../SOURCES.md)

## Method

Parsed the EPUB's `toc.ncx` chapter locators and **all split HTML fragments within each chapter**, normalized spacing and curly/straight apostrophes, and matched selected short quoted text **inside the specified book/chapter**. Internal local script verification; source text was not committed. The exact presence of a phrase was tested, **not whether its interpretation is correct**.

## Result

- **32/32** short fragments from the first batch of detailed theory cases matched their cited chapters.
- **4/4** additional excerpts from the Doran, Big Walder, and Oldtown alchemist research passed.
- **Combined: 36/36 matched**. Zero mismatches in the tested set.

## Representative tested anchors

| Fragment topic | Exact EPUB chapter |
| --- | --- |
| Septon Utt's reputation and death | ACOK 64; ASOS 39 |
| Unexplained Harrenhal boy | ACOK 47 |
| Ironborn sea/sky theology | ACOK 11; AFFC 1, 19 |
| Aegon and a cloth dragon | ACOK 48; ADWD 11, 24 |
| Stark / Manderly remembrance | ASOS 20; ADWD 29, 46 |
| Southron ambitions | ADWD 41 |
| Sarella/Alleras linguistic, background and scholarly clues | AFFC Prologue, 2, 21, 45 |
| Quiet Isle gravedigger | AFFC 31 |
| Renly's Margaery plan | ACOK 31 |
| Valonqar prophecy and Cersei's assumption | AFFC 36, 39 |
| Three-Eyed Crow uncertainty | ASOS 56; ADWD 13 |
| Lady Hornwood / Theon torture parallels | ADWD 19, 29, 41 |
| Jon's parentage breadcrumbs | AGOT 4, 58; ACOK 48 |
| Jojen/Bran paste imagery | ADWD 34 |
| Yronwood blood-debt reason | AFFC 21 |
| Big Walder's separation from Ramsay and bloody arrival | ADWD 32, 51 |
| Oldtown alchemist's offer | AFFC Prologue |

## Limits, critical caveats

- Some details in case files are **paraphrases**, not quoted fragments. Those require broader contextual reading and independent challenge.
- A matched quote often belongs to **dialogue by a character with imperfect information**. That never proves the theory.
- No exhaustive audit of all 344 narrative chapters is implied.
- Supplementary books and TWOW preview chapters are **not** covered.
- The provenance and completeness of all historical Reddit theory posts has **not** been independently verified; inaccessible/deleted originals remain marked.

## Follow-up

Expand source context around quoted paragraphs, audit candidate theories against disconfirmers, and run another check on each new batch. Correct claims in-place; preserve changelog when a popular theory's textual support is weaker than claimed.

## Additional four-family check — 2026-10-14

Selected brief fragments were matched by normalized exact string in their named EPUB chapters using the local five-book source, not scraped secondary quotations:

- AFFC 40: Doran's plans overthrown by circumstances.
- ADWD 60: Quentyn accepts personal responsibility for the mission.
- ADWD 68: Quentyn fears burning.
- ASOS 45: Robb requests witness seals.
- AFFC 45: Marwyn's dragon-extinction allegation.
- ADWD 37: Dustin's “grey rats” reference.
- ASOS 33: Craster's sons as named by an old wife.
- AGOT 24: Last Hero seeks the children.
- ASOS 18: dragonglass described in Sam's Other encounter.

**Result: 9/9 targeted textual checks matched.** The previous **36/36** receipt is unchanged; 45 total checks are recorded across the two passes, although this is not a comprehensive independent line-by-line review and does not prove the interpretations.
