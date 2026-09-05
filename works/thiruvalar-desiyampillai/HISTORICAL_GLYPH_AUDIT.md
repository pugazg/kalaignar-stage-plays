# Historical Tamil Glyph Audit — திருவாளர் தேசீயம்பிள்ளை

Status: **IN PROGRESS — 35 / 49 SCANS COMPLETE**

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

## Established same-edition reference set

Positive same-edition evidence currently supports:

`லை / ளை / ணா / ணை / னா / னை / றா`.

Representative anchors:

- `லை`: `கலைஞர்`, `தலைகள்`, `மாலைதானே`, scan-31 `விலைமதிக்க / மாலையை`, scan-32 repeated `மாலை`;
- `ளை`: `பிள்ளை`, `உங்களை`, `விளையும்`;
- `ணா`: `கருணாநிதி`, `கல்யாண`, `ஆகாஷவாணி`, scan-34 physical `சொல் / வொணா`;
- `ணை`: scan-25 `சொரணை`;
- `னா`: `கெட்டிக்காரர்தானா`, `உடையவர்தானா`, `மானால்`, scan-15 `தானா`, scan-21 `மகனா`, scan-31 `உடைதானா`, scan-33 `அரசனா / ஆண்டவனா`;
- `னை`: `அவனை`, `தண்டனை`;
- `றா`: `வண்ணமிருக்கிறார்களே`, `பார்க்கிறார்`, scan-20 `நன்றாக`, scan-15 `என்றாரே`, scan-32 `நன்றாகப்`.

These references are used only for character-identity comparison. They never authorize reconstruction of physically absent text, lexical normalization, or global replacement.

## Completed batches

### Batch 1 — scans 1–5

Full 13-family passes complete. Scan 2 verified; scans 1, 3, 4, 5 remain damage-limited.

### Batch 2 — scans 6–10

Full passes complete. `னை` established from scan-8 `அவனை`; scans 6 and 10 verified; scans 7–9 remain damage-limited.

### Batch 3 — scans 11–15

All five verified. `றா` established from scan-11 and later comparison corrected scan-15 apparent `என்றுரே / தானு` to canonical **`என்றாரே / தானா`**.

### Batch 4 — scans 16–20

All five verified. Scan 20 apparent old-type `நன்றுக` is canonically **`நன்றாக`** after character-identity adjudication. The scan16→17 physical boundary remains unedited at page-record level.

### Batch 5 — scans 21–25

All five verified. `ணை` established from scan-25 `சொரணை`; later Batch-6 comparison corrected scan-21 apparent `மகனு` to canonical **`மகனா`**.

### Batch 6 — scans 26–30

All five verified. Repeated scan-26/27 evidence established `னா`; scan 28 apparent `மால்தானே` was decoded canonically as **`மாலைதானே`**. No damage-limited page was introduced.

### Batch 7 — scans 31–35

Full source-pixel + 13-family passes completed for all five scans.

| Scan | Representative source form(s) | Family evidence | Result |
|---:|---|---|---|
| 31 | `உடைதானா`, `விலைமதிக்க`, `மாலையை`, `தேசீயம் பிள்ளை` | `னா / லை / ளை / றா` | **verified**; Gandhi's ornate-prison introduction and first exchange fully supported |
| 32 | repeated `மாலை`, `நன்றாகப்`, `தேசீயம் பிள்ளை` | `லை / றா / ளை` | **verified**; garland-rejection passage fully supported |
| 33 | `அரசனா`, `ஆண்டவனா`, `சிலைகள் / சிலைப்பற்றுகூடக்` | `னா / லை` | **verified**; priest/party allegory fully supported; final phrase continues to scan 34 |
| 34 | repeated verbal `றா` forms, physical `சொல் / வொணா` | `றா / ணா / ளை` | **verified**; scan-33 continuation and Gandhi critique fully supported |
| 35 | known families across page; one ambiguous non-secure cluster | full 13-family set checked | **needs-review**; one short cluster in `கொம்பு மாடெனக் … மட்டும்` remains unresolved |

### Scan-35 review hold

Scan 35 is not damage-limited in the same sense as the earlier torn pages. Most of the page is clearly readable and the mandatory 13-family inspection is complete. However, one short lexical/glyph cluster in the phrase:

`கொம்பு மாடெனக் … மட்டும் / வளர்த்து ஒன்றிரண்டு முட்டிக்கொண்டு`

remains visually insecure after enlarged inspection. Its ordinary appearance resembles `கொழுப்பேறி`, but that reading is **not** adopted canonically because the pixels do not support it strongly enough. `pages/0035.md` therefore records `[unresolved glyph cluster]` and remains `needs-review` pending same-edition evidence.

The page-ending `எங்குவேன்` remains physically open to scan 36 and must not be completed from context.

## Review/damage boundary through scan 35

`needs-review` pages:

- physical-damage holds: **1, 3, 4, 5, 7, 8, 9**;
- unresolved visual/glyph-cluster hold: **35**.

No other scan through 35 is currently unresolved.

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
- full historical-glyph passes complete: **35 / 49**;
- visually verified pages: **27 / 49** (`2, 6, 10–34`);
- `needs-review`: **8 / 49** (`1, 3, 4, 5, 7, 8, 9, 35`);
- unresolved source/glyph clusters currently recorded: **1** (scan 35);
- unprocessed scans: **14 / 49**.

## Exact next activity

Run the full source-pixel + historical-glyph verification for **scans 36–40** (printed pages **34–38**) while creating their canonical transcriptions. Keep scan 35's unresolved cluster open and use any later same-edition evidence only if it genuinely clarifies that cluster.