# Historical Tamil Glyph Audit — திருவாளர் தேசீயம்பிள்ளை

Status: **IN PROGRESS — 25 / 49 SCANS COMPLETE**

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

This is a minimum reference set, not a claim that every historical Tamil typeface has only these ambiguities.

## Batch 1 — scans 1–5

Full-page visual + 13-family passes complete.

| Scan | Representative source form(s) | Family evidence | Result |
|---:|---|---|---|
| 1 | `கலைஞர்`, `கருணாநிதி`, `பிள்ளை` | `லை`, `ணா`, `ளை` | identities positively supported; damaged artist signature remains separate |
| 2 | donor slip text | full set checked | no reform-sensitive correction required; page verified |
| 3 | `கலைஞர்`, `பிள்ளை` | `லை`, `ளை` | surviving identities supported; author continuation is paper loss |
| 4 | edition/imprint text | full set checked | central loss is physical damage |
| 5 | `கலைஞர்`, `கருணாநிதி`, `பிள்ளை` | `லை`, `ணா`, `ளை` | identities supported; missing prose not reconstructed |

Initial same-edition references: `லை / ளை / ணா`.

## Batch 2 — scans 6–10

Full-page visual + 13-family passes complete.

| Scan | Representative source form(s) | Family evidence | Result |
|---:|---|---|---|
| 6 | publisher-note close | full set checked | page verified |
| 7 | `பிள்ளை`, `தலையை` | `ளை`, `லை` | identities supported; body gaps are physical loss |
| 8 | `தலைமை`, `அவனை` | `லை`, `னை` | `னை` established; central gaps are physical loss |
| 9 | `உங்களை` | `ளை` | identity supported; lower-right loss remains unresolved |
| 10 | `தலையை`, `உங்களை` | `லை`, `ளை` | identities supported despite later ink; page verified |

Additional reference established: `னை` from `அவனை`.

## Batch 3 — scans 11–15

Full-page visual + 13-family passes complete. **All five scans verified.**

| Scan | Representative source form(s) | Family evidence | Result |
|---:|---|---|---|
| 11 | `சொந்தக்காரர்களை`, `வண்ணமிருக்கிறார்களே` | `ளை`, `றா` | `றா` added to same-edition reference set |
| 12 | `தேசீயம்பிள்ளை`, `உன்னை`, `இருக்கிறாய்` | `ளை`, `னை`, `றா` | identities agree with source reference set |
| 13 | `காளைமாட்டு`, `தண்டனை`, `இருக்கிறார்` | `ளை`, `னை`, `றா` | identities positively supported |
| 14 | `தண்டனை`, `பரவாயில்லை` | `னை`, `லை` | source spacing `இரண்டுக்கு முள்ள` retained |
| 15 | `தலைகள்`, `விளையும்`, `பார்க்கிறார்` | `லை`, `ளை`, `றா` | historical `லை` in `தலைகள்` positively decoded |

Additional reference established: `றா` from scan-11 `வண்ணமிருக்கிறார்களே`, reinforced by `இருக்கிறாய் / இருக்கிறார் / பார்க்கிறார்`.

## Batch 4 — scans 16–20

Full-page visual + 13-family passes complete. **All five scans verified. No new damage-limited page was introduced.**

| Scan | Representative source form(s) | Family evidence | Result |
|---:|---|---|---|
| 16 | `தலைகள்`, `கல்யாண` | `லை`, `ணா` | identities positively supported; final open `வறுமை வய` preserved at page boundary |
| 17 | `தலைகுனிந்தவாறு`, `பெண்களேதான்`, `பிள்ளை` | `லை`, `ளை` | identities supported; source-visible opening `வில் பொறுக்கப்பட்டவை!` retained without cross-page repair |
| 18 | `தண்டனை`, `வெளிநாட்டுச்சரக்கு`, `தேசீயம்பிள்ளை` | `னை`, `லை`, `ளை` | identities supported; `தூத்துக் குடிச்சாறு` retained exactly |
| 19 | `ராணுவத்`, `ஆகாஷவாணி`, `பூசினாற்`, `கண்களை` | `ணா`, `றா`, `ளை` | identities supported; physical line splits retained |
| 20 | apparent `நன்றுக` → canonical `நன்றாக`; `ஆகாஷவாணி`, `தேசீயம்பிள்ளை` | `றா`, `ணா`, `ளை` | post-pass guide check establishes the old-type character identity as `றா`; page remains verified |

### Scan-20 post-pass correction

The earlier ordinary-zoom reading `நன்றுக` was **not** preserved as lexical source wording. The attached historical-glyph guide explicitly gives this failure mode: an apparent old-type form such as `நன்றுக` can encode the character identity `நன்றாக`. Enlarged scan review plus same-edition `றா` evidence therefore supports canonical Unicode `நன்றாக`.

This is a character-identity decoding correction, not modernization of spelling or grammar.

### Batch-4 source-form / boundary safeguards

- scan 16 ends physically with `வறுமை வய`; scan 17 begins source-visibly `வில் பொறுக்கப்பட்டவை!`; page records preserve both physical witnesses and do not silently rewrite the cross-page wording;
- scan 18 retains `தூத்துக் குடிச்சாறு`;
- scan 19 preserves physical splits such as `கொந் / தளித்து`;
- scan 20 retains physical `ஆணை / யிட்டான்` while its old-type `றா` identity is correctly encoded in `நன்றாக`;
- no global historical-glyph replacement was performed.

## Batch 5 — scans 21–25

Full-page visual + 13-family passes complete. **All five scans verified. No new damage-limited page was introduced.**

| Scan | Representative source form(s) | Family evidence | Result |
|---:|---|---|---|
| 21 | `கீரிப்பிள்ளை`, `தென்னம்பிள்ளை`, `அணில்பிள்ளை` | `ளை`, candidate `ணை` checked | interview/wordplay sequence verified; source `மகனு` retained |
| 22 | `பிள்ளை`, `செத்துவிட்டமா` | `ளை`, `லை` | identities supported; final `இந்த` remains open to scan 23 |
| 23 | tax-dialogue forms, `நாட்டில்`, `பாரம்பரிய` | `றா / லை` and full set checked | physical splits `பூர் / வோத்திரத்தையும்`, `இந் / நாட்டு`, `சொல் / லும்` retained |
| 24 | punishment/tax dialogue | `னை` and full set checked | final physical `பூலோ` remains open to scan 25 |
| 25 | `சொரணை`, final `களை` | `ணை`, `ளை` | historical `ணை` positively established; source `பெறுதவர்களா?` retained without regularization |

### Additional same-edition reference established in Batch 5

- `ணை`: clear in scan-25 `சொரணை`.

The reusable same-edition comparison set now includes at least:

`லை / ளை / ணா / ணை / னை / றா`.

These references are used only for character-identity comparison. They do not authorize lexical modernization or reconstruction of absent text.

### Batch-5 boundary / source-form safeguards

- scan 20's interview continues on scan 21 without editorial restructuring;
- scan 22 ends with `இந்த`, and scan 23 begins its physical continuation; no silent page-record joining;
- scan 24 ends with `பூலோ`, and scan 25 begins `கத்தில்`; no silent page-record joining;
- scan 25 retains source `பெறுதவர்களா?` despite semantic expectation;
- physical splits such as scan-25 `அல் / லது` and `வரி / களை` remain represented;
- no global historical-glyph replacement was performed.

## Damage boundary through scan 25

Current `needs-review` pages remain damage-driven rather than unresolved historical-glyph identities:

- scans **1, 3, 4, 5, 7, 8, 9**.

Scans 11–25 add no new damage-limited page record.

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
- full historical-glyph passes complete: **25 / 49**;
- representative historical-family identities positively recorded: **`லை`, `ளை`, `ணா`, `ணை`, `னை`, `றா`**;
- unresolved historical-glyph clusters: **0 currently recorded**;
- damage-limited page records: **7** (`1, 3, 4, 5, 7, 8, 9`);
- visually verified pages: **18** (`2, 6, 10, 11, 12, 13, 14, 15, 16, 17, 18, 19, 20, 21, 22, 23, 24, 25`).

## Exact next activity

Run the full source-pixel + historical-glyph verification for **scans 26–30** (printed pages **24–28**) while creating their canonical transcriptions. Continue to use same-edition references only for character-identity comparison; never for reconstructing physically absent wording.