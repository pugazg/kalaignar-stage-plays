# Historical Tamil Glyph Audit — திருவாளர் தேசீயம்பிள்ளை

Status: **IN PROGRESS — 5 / 49 SCANS COMPLETE**

This work-level audit implements the user-supplied `HISTORICAL_TAMIL_GLYPH_TRANSCRIPTION_GUIDE.md` for the 1965 second-edition scan of **திருவாளர் தேசீயம்பிள்ளை**.

## Authority boundary

- controlling authority: source scan pixels;
- historical-glyph guide: methodology / candidate-family reference only;
- lexical first-pass witness: **none supplied**;
- OCR / language-model expectation / modern spelling: **not authority**.

The guide's core rule applies throughout:

> **Read character identity, not modern visual resemblance.**

A historical glyph correction decodes character identity into modern Unicode. It does **not** authorize modernization of the source word.

## Mandatory 13-family check

Every scan, including front matter and advertisements, must explicitly consider:

`ணா / ணை / ணொ / ணோ / லை / ளை / றா / றொ / றோ / னா / னை / னொ / னோ`.

This is a minimum reference set, not a claim that these are the only possible historical/edition-specific ambiguities.

## Batch 1 — scans 1–5

Full-page visual + 13-family passes are complete for scans **1–5**.

| Scan | Representative source form(s) | Family evidence | Result |
|---:|---|---|---|
| 1 | `கலைஞர்`, `கருணாநிதி`, `பிள்ளை` | `லை`, `ணா`, `ளை` | identities positively supported at enlarged pixels; no normalization |
| 2 | donor slip text | full set checked | no reform-sensitive correction required |
| 3 | `கலைஞர்`, `பிள்ளை` | `லை`, `ளை` | surviving identities supported; damaged author continuation treated as paper loss |
| 4 | edition/imprint text | full set checked | no reform-sensitive correction required; central loss is physical damage |
| 5 | `கலைஞர்`, `கருணாநிதி`, `பிள்ளை` | `லை`, `ணா`, `ளை` | identities positively supported; missing prose not reconstructed |

### Same-edition comparison established

The first batch provides a useful same-edition reference set:

- `லை`: clear in `கலைஞர்` on scans 1 and 5, with surviving recurrence on scan 3;
- `ளை`: clear in `பிள்ளை` on scans 1 and 5, with recurrence in the title on scan 3;
- `ணா`: clear in `கருணாநிதி` on scans 1 and 5.

These examples may be used later to compare uncertain historical typeforms in the same edition. They may **not** be used to invent letters hidden by actual paper loss.

### Batch-1 damage boundary

The following unresolved material is damage-driven rather than an unresolved historical-glyph identity:

- scan 1: small lower-left printed illustrator/artist signature partly abraded;
- scan 3: author line physically lost after `மு. கருண…`;
- scan 4: central price/matter line largely lost, with only `காசு` surviving clearly;
- scan 5: multiple publisher-note fragments physically lost.

Accordingly, a historical-glyph pass may be complete while the page remains `needs-review`.

## Mandatory page procedure

For each remaining scan:

1. inspect the whole page first to understand typeface, ink, damage and repeated glyph behaviour;
2. inspect difficult clusters at enlarged/native resolution;
3. check the full 13-family set even if the page seems easy;
4. read the complete glyph cluster, not only a final curl/loop/vowel mark;
5. compare same-edition / same-font occurrences when uncertain;
6. separate character identity from lexical expectation;
7. encode only the positively established historical identity in modern Unicode;
8. preserve source spelling, sandhi, grammar, vocabulary, punctuation and period-specific spacing otherwise;
9. if uncertainty remains, use `needs-review`; do not guess;
10. never perform a global replacement.

## Current progress

- scans in work: **49**;
- full historical-glyph passes complete: **5 / 49**;
- scans with documented historical-glyph corrections from an earlier reading: **0** — there was no lexical first-pass witness;
- representative historical-family identities positively recorded: **`லை`, `ளை`, `ணா`**;
- unresolved historical-glyph clusters: **0 currently recorded**;
- damage-limited page records after Batch 1: **4** (`1, 3, 4, 5`);
- pages visually verified after Batch 1: **1** (`2`).

## Exact next activity

Run the full source-pixel + historical-glyph verification for **scans 6–10** while creating their canonical transcriptions. Reuse the same-edition reference forms above only for character-identity comparison; never for reconstructing physically absent wording.
