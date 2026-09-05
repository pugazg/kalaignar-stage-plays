# Kalaignar Stage Plays — Handover

Repository: `pugazg/kalaignar-stage-plays`, branch `main`.

## Startup rule

Always fetch live `main` first and preserve newer durable state. Permanent workflow: `STAGE_PLAY_PROCESSING_GUIDE.md`.

# ACTIVE WORK — திருவாளர் தேசீயம்பிள்ளை

## Mandatory startup

Read before further source-dependent work:

1. `STAGE_PLAY_PROCESSING_GUIDE.md`;
2. this `HANDOVER.md`;
3. `NEXT_CHAT_PROMPT.md`;
4. `works/thiruvalar-desiyampillai/README.md`;
5. `works/thiruvalar-desiyampillai/metadata/source.md`;
6. `works/thiruvalar-desiyampillai/indexes/page-map.md`;
7. `works/thiruvalar-desiyampillai/HISTORICAL_GLYPH_AUDIT.md`;
8. relevant page records for the current batch;
9. controlling PDF must be attached/resolved for page-level visual work.

The user-supplied `HISTORICAL_TAMIL_GLYPH_TRANSCRIPTION_GUIDE.md` is mandatory methodology, not a lexical first-pass witness.

## Source identity

Controlling PDF: `TVA_BOK_0064118_திருவாளர்_தேசீயம்பிள்ளை.pdf`

- SHA-256: `b336bbebb326803badecbaa93de4ca4d63d80f68137fe70673b07a884c4910eb`;
- size: **58,035,177 bytes**;
- physical scans: **49**;
- source-visible second edition: **நவம்பர் 1965**;
- publisher: **K. R. நாராயணன்**;
- title-page address: **131, பிராட்வே சென்னை—1.**;
- printer/imprint: **முத்தமிழ்ச் செல்வி அச்சகம், 1/65, பிராட்வே.**

Registered structure: scans 1–6 front matter; scans 7–48 dramatic work; scans 8–48 visibly carry printed pp.6–46; scan 49 back-cover advertisement. Do not infer a printed page number for scan 7.

## Historical-glyph verification — mandatory

Every page checks:

`ணா / ணை / ணொ / ணோ / லை / ளை / றா / றொ / றோ / னா / னை / னொ / னோ`.

Permanent rules:

- read character identity, not modern visual resemblance;
- scan pixels control;
- encode proven old-glyph identity in modern Unicode only;
- preserve source wording/punctuation otherwise;
- compare same-edition evidence if uncertain;
- no global replacement;
- no context-based modernization;
- physical paper loss cannot be repaired by glyph inference;
- use `needs-review` when source support is incomplete.

Same-edition reference families now established:

- `லை` — `கலைஞர் / தலைகள் / மாலைதானே`;
- `ளை` — `பிள்ளை / உங்களை / விளையும்`;
- `ணா` — `கருணாநிதி / கல்யாண / ஆகாஷவாணி`;
- `ணை` — `சொரணை`;
- `னா` — `கெட்டிக்காரர்தானா / உடையவர்தானா / மானால்`, with backward confirmation in `தானா / மகனா`;
- `னை` — `அவனை / தண்டனை`;
- `றா` — `வண்ணமிருக்கிறார்களே / பார்க்கிறார் / நன்றாக / என்றாரே`.

## Current state after scans 1–30

**PAGE LAYER IN PROGRESS.**

- scans registered: **49 / 49**;
- page placeholders: **49 / 49**;
- canonical transcriptions processed: **30 / 49**;
- visually verified pages: **23 / 49** (`2, 6, 10–30`);
- `needs-review`: **7 / 49** (`1, 3, 4, 5, 7, 8, 9`);
- historical-glyph passes complete: **30 / 49**;
- unprocessed: **19 / 49**;
- structural / scene inventory: **pending full source pass**;
- English translation: **not authorized / not started**.

### Completed Batch 6 controls — scans 26–30

All five are **VERIFIED**.

- scan 26 / printed p.24: `ஐந்தாண்டுத் திட்டம்` interview verified; `னா` established from `கெட்டிக்காரர்தானா / உடையவர்தானா`; final `ஆளைப் பார்த்தே` remains physically open into scan 27;
- scan 27 / p.25: opening old-type form decoded as `மானால்`; scan26→27 physical boundary preserved;
- scan 28 / p.26: Gandhi-request/travel sequence verified; apparent `மால்தானே` decoded as `மாலைதானே` (`லை`); source `என் / னோடு` split retained;
- scan 29 / p.27: flower-shop/spirit narrative verified; physical splits `மந்திரி / கள்`, `படிக்கட்டு / கள்`, `நவரத் / தினங்கள்` preserved;
- scan 30 / p.28: Nandan entrance, embrace and fainting sequence verified; full 13-family pass complete; physical splits retained.

### Backward historical-glyph corrections now authoritative

Batch-6 same-edition evidence required three durable rechecks:

- scan 15 `என்றுரே` → **`என்றாரே`** (`றா`);
- scan 15 `தானு` → **`தானா`** (`னா`);
- scan 21 `மகனு` → **`மகனா`** (`னா`).

Scan 20 remains canonically **`நன்றாக`** after its earlier `றா` recheck. Do not restore superseded apparent-shape readings.

No scan 10–30 text is damage-limited. Existing `needs-review` pages remain scans `1, 3, 4, 5, 7, 8, 9`.

Do not begin scene assembly or English translation during this page-layer phase.

## Exact next activity

Process **scans 31–35** source-first, corresponding to printed pages **29–33**.

For each:
1. inspect full native/enlarged source pixels;
2. transcribe only positively supported printed text;
3. preserve speaker/stage/paragraph/page structure;
4. run the full 13-family historical-glyph check;
5. use same-edition comparison only for glyph identity;
6. do not infer scene numbering;
7. do not repair physical loss or unusual source wording from context;
8. mark `verified` only after the complete visual + glyph gate passes;
9. synchronize page-map, glyph audit, work README, root README, HANDOVER and NEXT prompt after the batch.

# CLOSED WORK SAFEGUARDS

`காகிதப்பூ` remains fully closed: Tamil 41/41, Tamil source-representation 23/23, English 23/23, final reviews PASS. `மணிமகுடம்` and closed `கலைஞரின் நான்மணி மாலை` component works remain closed unless explicitly reopened for new evidence or a separately authorized phase.