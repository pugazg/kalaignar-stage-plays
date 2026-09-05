# Historical Tamil Glyph Audit — திருவாளர் தேசீயம்பிள்ளை

Status: **IN PROGRESS — 10 / 49 SCANS COMPLETE**

This work-level audit implements the user-supplied `HISTORICAL_TAMIL_GLYPH_TRANSCRIPTION_GUIDE.md` for the 1965 second-edition scan of **திருவாளர் தேசீயம்பிள்ளை**.

## Authority boundary

- controlling authority: source scan pixels;
- historical-glyph guide: methodology / candidate-family reference only;
- lexical first-pass witness: **none supplied**;
- OCR / language-model expectation / modern spelling: **not authority**.

Core rule:

> **Read character identity, not modern visual resemblance.**

A historical-glyph correction decodes character identity into modern Unicode. It does **not** authorize modernization of the source word.

## Mandatory 13-family check

Every scan, including front matter and advertisements, explicitly considers:

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

### Batch-1 same-edition references

- `லை`: clear in `கலைஞர்`;
- `ளை`: clear in `பிள்ளை`;
- `ணா`: clear in `கருணாநிதி`.

These are character-identity references only. They may not be used to invent text hidden by physical paper loss.

## Batch 2 — scans 6–10

Full-page visual + 13-family passes are complete for scans **6–10**.

| Scan | Representative source form(s) | Family evidence | Result |
|---:|---|---|---|
| 6 | publisher-note close | full set checked | no reform-sensitive correction required; page verified |
| 7 | `பிள்ளை`, `தலையை` | `ளை`, `லை` | identities positively supported; body gaps are physical loss |
| 8 | `தலைமை`, `அவனை` | `லை`, `னை` | `னை` positively established from same-edition source; central gaps are physical loss |
| 9 | `உங்களை` | `ளை` | identity positively supported; lower-right missing ending is physical loss |
| 10 | `தலையை`, `உங்களை` | `லை`, `ளை` | identities positively supported despite later ink mark; page verified |

### Additional same-edition reference established

- `னை`: clear in `அவனை` on scan 8.

The reusable same-edition comparison set now includes at least `லை / ளை / ணா / னை`. These references are used only when the same historical family is genuinely uncertain on later source pixels.

### Batch-2 damage boundary

Unresolved material is damage-driven rather than historical-glyph uncertainty:

- scan 7: irregular paper loss cuts through the opener/title-body region;
- scan 8: broad central paper loss removes portions of several lines;
- scan 9: lower-right paper loss removes the ending of the first repeated `எங்கே ஜனநாயக…` line.

Scans 6 and 10 pass the full visual + historical-glyph gate. The later ink mark on scan 10 does not obscure underlying character identity.

## Mandatory page procedure

For each remaining scan:

1. inspect the whole page first to understand typeface, ink, damage and repeated glyph behaviour;
2. inspect difficult clusters at enlarged/native resolution;
3. check the full 13-family set even if the page seems easy;
4. read the complete glyph cluster, not only a final curl/loop/vowel mark;
5. compare same-edition / same-font occurrences when uncertain;
6. separate character identity from lexical expectation;
7. encode only positively established historical identity in modern Unicode;
8. preserve source spelling, sandhi, grammar, vocabulary, punctuation and period-specific spacing otherwise;
9. if uncertainty remains, use `needs-review`; do not guess;
10. never perform a global replacement.

## Current progress

- scans in work: **49**;
- full historical-glyph passes complete: **10 / 49**;
- scans with documented historical-glyph corrections from an earlier reading: **0** — no lexical first-pass witness exists;
- representative historical-family identities positively recorded: **`லை`, `ளை`, `ணா`, `னை`**;
- unresolved historical-glyph clusters: **0 currently recorded**;
- damage-limited page records: **7** (`1, 3, 4, 5, 7, 8, 9`);
- visually verified pages: **3** (`2, 6, 10`).

## Exact next activity

Run the full source-pixel + historical-glyph verification for **scans 11–15** while creating their canonical transcriptions. Continue to use same-edition references only for character-identity comparison; never for reconstructing physically absent wording.
