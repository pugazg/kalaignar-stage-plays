# Historical Tamil Glyph Audit — திருவாளர் தேசீயம்பிள்ளை

Status: **IN PROGRESS — 30 / 49 SCANS COMPLETE**

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

This is a minimum known reference set, not a claim that every historical Tamil typeface has only these ambiguities.

## Batch 1 — scans 1–5

Full-page visual + 13-family passes complete.

- `லை / ளை / ணா` same-edition identities established from cover/front-matter forms;
- scan 2 verified;
- scans 1, 3, 4, 5 remain `needs-review` because of physical damage, not unresolved glyph identity.

## Batch 2 — scans 6–10

Full-page visual + 13-family passes complete.

- `னை` established from scan-8 `அவனை`;
- scans 6 and 10 verified;
- scans 7, 8, 9 remain damage-limited.

## Batch 3 — scans 11–15

Full-page visual + 13-family passes complete. **All five scans verified.**

- `றா` established from scan-11 `வண்ணமிருக்கிறார்களே`, reinforced by `இருக்கிறாய் / இருக்கிறார் / பார்க்கிறார்`;
- scan-15 `லை` in `தலைகள்` and `ளை` in `விளையும்` positively decoded;
- later Batch-6 same-edition comparison required a post-pass correction on scan 15: apparent ordinary-zoom `என்றுரே / தானு` are historical `றா / னா` identities and are canonically encoded as **`என்றாரே / தானா`**.

## Batch 4 — scans 16–20

Full-page visual + 13-family passes complete. **All five scans verified.**

- scan 16→17 physical boundary `வறுமை வய` / `வில் பொறுக்கப்பட்டவை!` remains unedited at page-record level;
- scan 18 retains source `தூத்துக் குடிச்சாறு`;
- scan 19 preserves physical word splits;
- scan 20 apparent old-type `நன்றுக` was rechecked under the mandatory glyph guide and same-edition `றா` evidence and is canonically **`நன்றாக`**.

### Scan-20 correction rule

The historical-glyph guide explicitly documents this failure mode: an apparent old-type shape such as `நன்றுக` can encode `நன்றாக`. The canonical correction is therefore character-identity decoding, not spelling modernization.

## Batch 5 — scans 21–25

Full-page visual + 13-family passes complete. **All five scans verified.**

- scan 21 interview/wordplay sequence retained;
- scan 22→23 and scan 24→25 physical continuations remain separated in page records;
- scan 25 source `பெறுதவர்களா?` retained without semantic regularization;
- historical `ணை` positively established from scan-25 `சொரணை`;
- later Batch-6 comparison rechecked scan-21 apparent `மகனு` and established the historical `னா` identity; canonical scan-21 form is now **`மகனா`**.

## Batch 6 — scans 26–30

Full-page visual + 13-family passes complete. **All five scans verified. No new damage-limited page was introduced.**

| Scan | Representative source form(s) | Family evidence | Result |
|---:|---|---|---|
| 26 | `கெட்டிக்காரர்தானா`, `உடையவர்தானா`, `தேசீயம் பிள்ளை` | `னா`, `ளை`, `றா` | repeated clear `னா` identity established; final `ஆளைப் பார்த்தே` remains open to scan 27 |
| 27 | opening `மானால்`, `இளைத்துப்`, `இல்லை` | `னா`, `ளை`, `லை` | opening apparent old-type form decoded as `மானால்`; scan26→27 physical boundary preserved |
| 28 | `மாலைதானே`, `தேசீயம் பிள்ளை` | `லை`, `ளை` | apparent `மால்தானே` corrected by historical `லை` identity to `மாலைதானே` |
| 29 | `பைசாக்களை`, `பிள்ளை`, `மாலை`, `மல்லிகை` | `ளை`, `லை` | identities supported; no new family required |
| 30 | repeated `தேசீயம் பிள்ளை` plus full candidate set | `ளை` + full set | Nandan entrance/embrace/fainting page fully verified; no additional glyph correction required |

### `னா` same-edition reference established in Batch 6

Clear repeated evidence on scans 26–27 establishes the historical `னா` family for this edition. That evidence also supports two backward corrections where earlier ordinary-zoom readings had been retained too literally:

- scan 15: `தானு` → **`தானா`**;
- scan 21: `மகனு` → **`மகனா`**.

The scan-15 `என்றுரே` → **`என்றாரே`** correction is the corresponding `றா` identity recheck.

These are all character-identity corrections under the supplied historical-glyph methodology. They are not semantic, grammatical or spelling modernization.

## Current same-edition comparison set

At least the following families now have positive same-edition evidence:

`லை / ளை / ணா / ணை / னா / னை / றா`.

Representative anchors:

- `லை`: `கலைஞர்`, `தலைகள்`, `மாலைதானே`;
- `ளை`: `பிள்ளை`, `உங்களை`, `விளையும்`;
- `ணா`: `கருணாநிதி`, `கல்யாண`, `ஆகாஷவாணி`;
- `ணை`: `சொரணை`;
- `னா`: `கெட்டிக்காரர்தானா`, `உடையவர்தானா`, `மானால்`, with backward confirmation in `தானா / மகனா`;
- `னை`: `அவனை`, `தண்டனை`;
- `றா`: `வண்ணமிருக்கிறார்களே`, `பார்க்கிறார்`, `நன்றாக`, `என்றாரே`.

These references are used only for character-identity comparison. They never authorize reconstruction of physically absent text or global replacement.

## Damage boundary through scan 30

Current `needs-review` pages remain damage-driven:

- scans **1, 3, 4, 5, 7, 8, 9**.

Scans 10–30 add no new damage-limited page record.

## Mandatory page procedure

For each remaining scan:

1. inspect the whole page first for typeface, ink, damage, bleed-through and repeated glyph behaviour;
2. inspect difficult clusters at enlarged/native resolution;
3. check the full 13-family set even when the page appears easy;
4. read the complete glyph cluster rather than a final curl/loop alone;
5. compare same-edition / same-font occurrences when uncertain;
6. separate glyph identity from lexical expectation;
7. encode only positively established historical identity in modern Unicode;
8. preserve source spelling, sandhi, grammar, vocabulary, punctuation and period-specific spacing otherwise;
9. if uncertainty remains, use `needs-review`; do not guess;
10. never perform a global replacement.

## Current progress

- scans in work: **49**;
- full historical-glyph passes complete: **30 / 49**;
- representative positively established families: **`லை`, `ளை`, `ணா`, `ணை`, `னா`, `னை`, `றா`**;
- unresolved historical-glyph clusters: **0 currently recorded**;
- damage-limited page records: **7** (`1, 3, 4, 5, 7, 8, 9`);
- visually verified pages: **23** (`2, 6, 10–30`).

## Exact next activity

Run the full source-pixel + historical-glyph verification for **scans 31–35** (printed pages **29–33**) while creating their canonical transcriptions. Continue to use same-edition references only for character-identity comparison; never for reconstructing physically absent wording.