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

Positive same-edition reference families now established:

`லை / ளை / ணா / ணை / னா / னை / றா`.

Authoritative historical-glyph corrections that must not be reverted:

- scan 15 `என்றுரே` → **`என்றாரே`** (`றா`);
- scan 15 `தானு` → **`தானா`** (`னா`);
- scan 20 `நன்றுக` → **`நன்றாக`** (`றா`);
- scan 21 `மகனு` → **`மகனா`** (`னா`);
- scan 28 `மால்தானே` → **`மாலைதானே`** (`லை`).

## Current state after scans 1–35

**PAGE LAYER IN PROGRESS.**

- scans registered: **49 / 49**;
- page placeholders: **49 / 49**;
- canonical transcriptions processed: **35 / 49**;
- visually verified pages: **27 / 49** (`2, 6, 10–34`);
- `needs-review`: **8 / 49** (`1, 3, 4, 5, 7, 8, 9, 35`);
- historical-glyph passes complete: **35 / 49**;
- unprocessed: **14 / 49**;
- unresolved source/glyph clusters: **1** (scan 35);
- structural / scene inventory: **pending full source pass**;
- English translation: **not authorized / not started**.

### Completed Batch 7 controls — scans 31–35

- scan 31 / printed p.29 — **VERIFIED**: Gandhi's ornate-prison introduction and first exchange; `உடைதானா` reinforces `னா`; `விலைமதிக்க / மாலையை` reinforce `லை`;
- scan 32 / p.30 — **VERIFIED**: garland-rejection passage; repeated `மாலை` and `நன்றாகப்` checked by established historical identities;
- scan 33 / p.31 — **VERIFIED**: priest/party allegory; `அரசனா / ஆண்டவனா` reinforce `னா`; final `கட்சித் தலைவர்கள் கடவுளை` stays physically open into scan 34;
- scan 34 / p.32 — **VERIFIED**: scan-33 continuation and Gandhi critique; physical `சொல் / வொணா` and source `நாதி / யில்லை` retained;
- scan 35 / p.33 — **NEEDS REVIEW**: page otherwise fully transcribed and 13-family checked, but one short cluster in `கொம்பு மாடெனக் … மட்டும்` remains visually insecure. The apparent reading resembling `கொழுப்பேறி` is not canonical. Final `எங்குவேன்` remains open to scan 36.

Existing damage-driven review holds remain scans `1, 3, 4, 5, 7, 8, 9`. Scan 35 is a distinct unresolved visual/glyph-cluster hold.

Do not begin scene assembly or English translation during this page-layer phase.

## Exact next activity

Process **scans 36–40** source-first, corresponding to printed pages **34–38**.

For each:
1. inspect full native/enlarged source pixels;
2. transcribe only positively supported printed text;
3. preserve speaker/stage/paragraph/page structure;
4. run the full 13-family historical-glyph check;
5. use same-edition comparison only for glyph identity;
6. do not infer scene numbering;
7. do not repair physical loss or unusual source wording from context;
8. mark `verified` only after the complete visual + glyph gate passes;
9. if scans 36–40 contain genuine same-edition evidence for scan 35's unresolved cluster, re-adjudicate scan 35 explicitly rather than silently changing it;
10. synchronize page-map, glyph audit, work README, root README, HANDOVER and NEXT prompt after the batch.

# CLOSED WORK SAFEGUARDS

`காகிதப்பூ` remains fully closed: Tamil 41/41, Tamil source-representation 23/23, English 23/23, final reviews PASS. `மணிமகுடம்` and closed `கலைஞரின் நான்மணி மாலை` component works remain closed unless explicitly reopened for new evidence or a separately authorized phase.