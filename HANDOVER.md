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

User-supplied catalog metadata and description remain contextual only; source pixels control transcription.

## Registered physical structure

- scan 1: colour front cover;
- scan 2: pasted donor/library slip, verified as `பேராசிரியர். தி.வ. மெய்கண்டார் அவர்களின் / அன்பளிப்பு`;
- scan 3: title page;
- scan 4: edition/imprint page;
- scans 5–6: publisher note `வணக்கம்.`;
- scans 7–48: dramatic work;
- scans 8–48 visibly carry printed pages **6–46**;
- scan 49: back-cover advertisement.

Do not infer a printed page number for scan 7 merely from sequence.

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

Same-edition reference forms currently established:

- `லை` — `கலைஞர்`, reinforced by `தலையை / தலைமை / தலைகள்`;
- `ளை` — `பிள்ளை`, reinforced by `உங்களை / காளைமாட்டு / விளையும்`;
- `ணா` — `கருணாநிதி`;
- `னை` — `அவனை / தண்டனை`;
- `றா` — `வண்ணமிருக்கிறார்களே`, reinforced by `இருக்கிறாய் / இருக்கிறார் / பார்க்கிறார்`.

## Current state after scans 1–15

**PAGE LAYER IN PROGRESS.**

- scans registered: **49 / 49**;
- page placeholders: **49 / 49**;
- canonical transcriptions processed: **15 / 49**;
- visually verified pages: **8 / 49** (`2, 6, 10, 11, 12, 13, 14, 15`);
- `needs-review`: **7 / 49** (`1, 3, 4, 5, 7, 8, 9`);
- historical-glyph passes complete: **15 / 49**;
- unprocessed: **34 / 49**;
- structural / scene inventory: **pending full source pass**;
- English translation: **not authorized / not started**.

### Completed Batch 3 controls — scans 11–15

All five are **VERIFIED**.

- scan 11 / printed p.9: full economic/death-export debate verified; new same-edition `றா` reference established from `வண்ணமிருக்கிறார்களே`;
- scan 12 / printed p.10: stage direction and `கதர் உருவம்` / `தேசீயம் பிள்ளை` speaker structure preserved; final utterance remains open into scan 13;
- scan 13 / printed p.11: physical continuation retained without inventing a speaker label; `அய்யன்மீர்`, `ஓகோ`, `படுபாதாளச் சிறையில்` remain source-faithful;
- scan 14 / printed p.12: `இரண்டுக்கு முள்ள` retained exactly rather than regularized; final `எமன்:` utterance remains open after source dash;
- scan 15 / printed p.13: scan-14 continuation, stage direction and `ஸ்ரீ மயானம்` prose verified; historical `லை` in `தலைகள்` decoded; final `அதன்படி` remains open to scan 16.

No scan 11–15 text is damage-limited. Existing `needs-review` pages remain scans `1, 3, 4, 5, 7, 8, 9`.

Do not begin scene assembly or English translation during this page-layer phase.

## Exact next activity

Process **scans 16–20** source-first, corresponding to printed pages **14–18**.

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