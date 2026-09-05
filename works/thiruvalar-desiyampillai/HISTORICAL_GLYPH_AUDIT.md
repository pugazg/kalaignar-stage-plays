# Historical Tamil Glyph Audit — திருவாளர் தேசீயம்பிள்ளை

Status: **IN PROGRESS — 15 / 49 SCANS COMPLETE**

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

### Additional same-edition reference established in Batch 2

- `னை`: clear in `அவனை` on scan 8.

## Batch 3 — scans 11–15

Full-page visual + 13-family passes are complete for scans **11–15**. All five scans pass the complete visual gate; no paper loss removes literary text in this batch.

| Scan | Representative source form(s) | Family evidence | Result |
|---:|---|---|---|
| 11 | `சொந்தக்காரர்களை`, `வண்ணமிருக்கிறார்களே` | `ளை`, `றா` | both identities positively supported; `றா` added to same-edition reference set |
| 12 | `தேசீயம்பிள்ளை`, `உன்னை`, `இருக்கிறாய்` | `ளை`, `னை`, `றா` | identities agree with established same-edition forms; page verified |
| 13 | `காளைமாட்டு`, `தண்டனை`, `இருக்கிறார்` | `ளை`, `னை`, `றா` | identities positively supported; unusual source wording retained |
| 14 | `தண்டனை`, `பரவாயில்லை` | `னை`, `லை` | identities positively supported; source spacing `இரண்டுக்கு முள்ள` not normalized |
| 15 | `தலைகள்`, `விளையும்`, `பார்க்கிறார்` | `லை`, `ளை`, `றா` | historical `லை` in `தலைகள்` positively decoded; page verified |

### Additional same-edition reference established in Batch 3

- `றா`: clear in scan-11 `வண்ணமிருக்கிறார்களே`, reinforced by later `இருக்கிறாய் / இருக்கிறார் / பார்க்கிறார்` forms.

The reusable same-edition comparison set now includes at least:

`லை / ளை / ணா / னை / றா`.

These references are used only when the same historical family is genuinely uncertain on later source pixels. They do not authorize lexical modernization or reconstruction.

### Batch-3 source-form safeguards

The following forms were retained exactly because scan pixels support them and semantic expectation is not an editing authority:

- scan 13: `அய்யன்மீர்`, `ஓகோ`, `படுபாதாளச் சிறையில்`;
- scan 14: `இரண்டுக்கு முள்ள`;
- scan 15: `என்றுரே`, `தானு`.

No global historical-glyph replacement was performed.

## Damage boundary through scan 15

Current `needs-review` pages remain damage-driven rather than unresolved historical-glyph identities:

- scans 1, 3, 4, 5, 7, 8 and 9.

Scans 11–15 add no new damage-limited page record.

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
- full historical-glyph passes complete: **15 / 49**;
- scans with documented historical-glyph corrections from an earlier lexical reading: **0** — no lexical first-pass witness exists;
- representative historical-family identities positively recorded: **`லை`, `ளை`, `ணா`, `னை`, `றா`**;
- unresolved historical-glyph clusters: **0 currently recorded**;
- damage-limited page records: **7** (`1, 3, 4, 5, 7, 8, 9`);
- visually verified pages: **8** (`2, 6, 10, 11, 12, 13, 14, 15`).

## Exact next activity

Run the full source-pixel + historical-glyph verification for **scans 16–20** (printed pages **14–18**) while creating their canonical transcriptions. Continue to use same-edition references only for character-identity comparison; never for reconstructing physically absent wording.