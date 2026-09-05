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

- `லை` — `கலைஞர்`, reinforced by `தலையை / தலைமை / தலைகள் / தலைகுனிந்தவாறு`;
- `ளை` — `பிள்ளை`, reinforced by `உங்களை / காளைமாட்டு / விளையும் / கண்களை`;
- `ணா` — `கருணாநிதி`, reinforced by `கல்யாண / ராணுவத் / ஆகாஷவாணி`;
- `ணை` — scan-25 `சொரணை`;
- `னை` — `அவனை / தண்டனை`;
- `றா` — `வண்ணமிருக்கிறார்களே`, reinforced by `இருக்கிறாய் / இருக்கிறார் / பார்க்கிறார் / பூசினாற்`; scan-20 apparent `நன்றுக` is canonically `நன்றாக` after glyph recheck.

## Current state after scans 1–25

**PAGE LAYER IN PROGRESS.**

- scans registered: **49 / 49**;
- page placeholders: **49 / 49**;
- canonical transcriptions processed: **25 / 49**;
- visually verified pages: **18 / 49** (`2, 6, 10, 11, 12, 13, 14, 15, 16, 17, 18, 19, 20, 21, 22, 23, 24, 25`);
- `needs-review`: **7 / 49** (`1, 3, 4, 5, 7, 8, 9`);
- historical-glyph passes complete: **25 / 49**;
- unprocessed: **24 / 49**;
- structural / scene inventory: **pending full source pass**;
- English translation: **not authorized / not started**.

### Completed Batch 5 controls — scans 21–25

All five are **VERIFIED**.

- scan 21 / printed p.19: `எமன் :` interview continuation; `ஹியூம்`, source `மகனு`, and `கீரிப்பிள்ளை / தென்னம்பிள்ளை / அணில்பிள்ளை` wordplay retained;
- scan 22 / printed p.20: parrot/rationality dialogue verified; source `செத்துவிட்டமா` retained; final `இந்த` remains physically open into scan 23;
- scan 23 / printed p.21: scan-22 continuation and tax dialogue verified; physical splits `பூர் / வோத்திரத்தையும்`, `இந் / நாட்டு`, `சொல் / லும்` preserved;
- scan 24 / printed p.22: tax-on-decaying-goods/corpses/punishment dialogue verified; final `பூலோ` remains open into scan 25;
- scan 25 / printed p.23: scan-24 continuation and election/independents/tax dialogue verified; source `பெறுதவர்களா?` retained; historical `ணை` established from `சொரணை`; physical `அல் / லது` and `வரி / களை` retained.

### Scan-20 glyph correction carried forward

The earlier apparent reading `நன்றுக` is superseded. Under the attached historical-glyph guide and same-edition `றா` evidence, the character identity is **`நன்றாக`**. `pages/0020.md`, page-map, work README, root README, glyph audit, this handover and next-chat prompt must all preserve that corrected canonical form.

No scan 11–25 text is damage-limited. Existing `needs-review` pages remain scans `1, 3, 4, 5, 7, 8, 9`.

Do not begin scene assembly or English translation during this page-layer phase.

## Exact next activity

Process **scans 26–30** source-first, corresponding to printed pages **24–28**.

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