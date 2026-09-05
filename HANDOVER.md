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
8. `works/thiruvalar-desiyampillai/PAGE_LAYER_COMPLETION_AUDIT.md`;
9. relevant page records for the current structural/assembly task;
10. controlling PDF must be attached/resolved for any new page-level visual adjudication.

The user-supplied `HISTORICAL_TAMIL_GLYPH_TRANSCRIPTION_GUIDE.md` is mandatory methodology, not a lexical first-pass witness.

## Source identity

Controlling PDF: `TVA_BOK_0064118_திருவாளர்_தேசீயம்பிள்ளை.pdf`

- SHA-256: `b336bbebb326803badecbaa93de4ca4d63d80f68137fe70673b07a884c4910eb`;
- size: **58,035,177 bytes**;
- physical scans: **49**;
- source-visible second edition: **நவம்பர் 1965**;
- publisher: **K. R. நாராயணன்**;
- scans 1–6 front matter; scans 7–48 dramatic work; scans 8–48 visibly carry printed pp.6–46; scan 49 back-cover advertisement.

## Historical-glyph verification — mandatory

Every page has now received the full check for:

`ணா / ணை / ணொ / ணோ / லை / ளை / றா / றொ / றோ / னா / னை / னொ / னோ`.

Positive same-edition families:

`லை / ளை / ணா / ணை / னா / னை / றா`.

Authoritative corrections that must not be reverted:

- scan 15 `என்றுரே` → **`என்றாரே`**;
- scan 15 `தானு` → **`தானா`**;
- scan 20 `நன்றுக` → **`நன்றாக`**;
- scan 21 `மகனு` → **`மகனா`**;
- scan 28 `மால்தானே` → **`மாலைதானே`**;
- scan 42 → **`பொறாமை`**;
- scan 44 → **`ஆலை முதலாளி`**.

Final enlarged source rechecks also establish exact source forms:

- scan 46: **`நம்ப`**, `‘உதயசூரியனு’க் / குத்தானே`, **`தேசீயம் பிள்ளை`**;
- scan 47: **`தேசீயம்பிள்ளை / தேசீயம் பிள்ளையின் / போட்டகோலம்`**;
- scan 48: **`தேசீயம் பிள்ளையின்`**, physical **`மலை / யேறும்`**.

## Current page-layer state

**SOURCE-PAGE PASS COMPLETE.**

- scans/page records: **49 / 49**;
- canonical source processing: **49 / 49**;
- historical-glyph passes: **49 / 49**;
- visually verified pages: **40 / 49** (`2, 6, 10–34, 37–49`);
- `needs-review`: **9 / 49** (`1, 3, 4, 5, 7, 8, 9, 35, 36`);
- unprocessed: **0**;
- unresolved visual/source clusters: **3** (scan 35: 1; scan 36: 2);
- structural / scene inventory: **next**;
- scene assembly: **not started**;
- English translation: **not authorized / not started**.

Durable completion audit: `works/thiruvalar-desiyampillai/PAGE_LAYER_COMPLETION_AUDIT.md`.

Audit verdict: **coverage PASS, not 49/49 verified**. Structural/scene work is conditionally authorized from visually checked page records, but unresolved/lost text must remain explicit.

### Review holds that must survive assembly

Front matter only:

- scans `1, 3, 4, 5` — physical loss/abrasion.

Dramatic body:

- scans `7, 8, 9` — physical paper-loss gaps;
- scan `35` — one unresolved source cluster in `கொம்பு மாடெனக் … மட்டும்`;
- scan `36` — two unresolved descriptive clusters in the `ஹரிஜன நலம்` / `சவலைப் பிள்ளை` passage.

Do not use context, OCR, a modern edition, or lexical expectation to fill these gaps. Any derived scene touching scans `7, 8, 9, 35, 36` must preserve the explicit loss/review markers and must not claim `assembled_from_verified_pages: true`.

## Final Batch 10 — scans 46–49

All four are **VERIFIED**.

- scan 46 / p.44 — family/election-organizing argument; source colloquial/name forms rechecked at enlarged resolution;
- scan 47 / p.45 — Desiyampillai/Kamala passage and centered source heading **`உதயசூரியன் கோலம்`**;
- scan 48 / p.46 — final dramatic-body page; **no source-visible `முற்றும்` marker**;
- scan 49 — separate back-cover advertisement for **`அல்லி விழி`**; not dramatic text.

## Exact next activity — structural / scene inventory

Before creating scene files, build a durable source-visible structural inventory across **scans 7–48**.

1. inspect page records in source order;
2. list every source-visible heading, speaker/stage transition and other structural boundary actually printed;
3. do **not** manufacture `காட்சி` numbers or divisions from dramatic context;
4. determine from source evidence how scan-47 centered **`உதயசூரியன் கோலம்`** relates to the surrounding text;
5. record page spans/provenance for any defensible source-representation units;
6. carry the five body review holds (`7, 8, 9, 35, 36`) explicitly;
7. create a durable structural/scene inventory document first;
8. only after that inventory is reviewed should `scenes/*.md` assembly begin.

Do not begin English translation.

# CLOSED WORK SAFEGUARDS

`காகிதப்பூ` remains fully closed: Tamil 41/41, source-representation scenes 23/23, English 23/23, final reviews PASS. `மணிமகுடம்` and closed `கலைஞரின் நான்மணி மாலை` component works remain closed unless explicitly reopened.