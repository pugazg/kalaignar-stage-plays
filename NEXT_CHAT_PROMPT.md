# Next Chat Prompt — Kalaignar Stage Plays / திருவாளர் தேசீயம்பிள்ளை

Continue directly in `pugazg/kalaignar-stage-plays`, branch `main`, active work `works/thiruvalar-desiyampillai/`.

## LIVE MAIN IS AUTHORITATIVE

Fetch live `main` first. Preserve newer durable state. Do not reopen closed காகிதப்பூ / மணிமகுடம் / நான்மணி மாலை work because an older copied prompt contains a stale checkpoint.

## Mandatory startup

Read before further work:

1. `STAGE_PLAY_PROCESSING_GUIDE.md`
2. `HANDOVER.md`
3. this `NEXT_CHAT_PROMPT.md`
4. `works/thiruvalar-desiyampillai/README.md`
5. `works/thiruvalar-desiyampillai/metadata/source.md`
6. `works/thiruvalar-desiyampillai/indexes/page-map.md`
7. `works/thiruvalar-desiyampillai/HISTORICAL_GLYPH_AUDIT.md`
8. `works/thiruvalar-desiyampillai/PAGE_LAYER_COMPLETION_AUDIT.md`
9. page records `works/thiruvalar-desiyampillai/pages/0007.md` through `0048.md` for structural inventory
10. controlling PDF only when a new page-level visual adjudication is required

The user-supplied `HISTORICAL_TAMIL_GLYPH_TRANSCRIPTION_GUIDE.md` remains mandatory methodology, not a lexical first-pass witness.

## Current source

`TVA_BOK_0064118_திருவாளர்_தேசீயம்பிள்ளை.pdf`

- SHA-256: `b336bbebb326803badecbaa93de4ca4d63d80f68137fe70673b07a884c4910eb`
- size: **58,035,177 bytes**
- scans: **49**
- second edition: **நவம்பர் 1965**
- publisher: **K. R. நாராயணன்**

## Page-layer checkpoint

**SOURCE-PAGE PASS COMPLETE.**

- page records/source processing: **49 / 49**;
- full historical-glyph passes: **49 / 49**;
- visually verified: **40 / 49** (`2, 6, 10–34, 37–49`);
- `needs-review`: **9 / 49** (`1, 3, 4, 5, 7, 8, 9, 35, 36`);
- unprocessed: **0**;
- unresolved visual/source clusters: **3** (scan 35: 1; scan 36: 2);
- structural / scene inventory: **not started — exact next activity**;
- scene assembly: **not started**;
- English translation: **not authorized / not started**.

Completion audit: `works/thiruvalar-desiyampillai/PAGE_LAYER_COMPLETION_AUDIT.md`.

Audit verdict: **coverage PASS but not 49/49 verified**. Scene/structural work may proceed from the visually checked records only if all loss/unresolved markers are carried forward without repair.

## Historical Tamil glyph checkpoint

The 13-family pass is complete for all 49 scans:

`ணா / ணை / ணொ / ணோ / லை / ளை / றா / றொ / றோ / னா / னை / னொ / னோ`.

Positive same-edition reference families:

`லை / ளை / ணா / ணை / னா / னை / றா`.

Authoritative source-pixel decisions — do not revert:

- scan 15 `என்றுரே / தானு` → `என்றாரே / தானா`;
- scan 20 `நன்றுக` → `நன்றாக`;
- scan 21 `மகனு` → `மகனா`;
- scan 28 `மால்தானே` → `மாலைதானே`;
- scan 42 → `பொறாமை`;
- scan 44 → `ஆலை முதலாளி`;
- scan 46 source colloquial **`நம்ப`**, not `நம்ம`;
- scans 46–48 source work/name spelling **`தேசீயம்`**;
- scan 47 source **`போட்டகோலம்`**;
- scan 48 physical **`மலை / யேறும்`**.

## Final source batch — complete

- `0046.md` / p.44 — **verified**;
- `0047.md` / p.45 — **verified**, including centered source-visible heading `உதயசூரியன் கோலம்`;
- `0048.md` / p.46 — **verified**, final dramatic-body page; no source-visible `முற்றும்` marker;
- `0049.md` / back cover — **verified**, separate `அல்லி விழி` advertisement.

## Review holds that must remain explicit

Front matter:
- `1, 3, 4, 5` — physical loss/abrasion.

Dramatic body:
- `7, 8, 9` — physical paper-loss gaps;
- `35` — one unresolved cluster in `கொம்பு மாடெனக் … மட்டும்`;
- `36` — two unresolved clusters in the `ஹரிஜன நலம்` / `சவலைப் பிள்ளை` passage.

Do not reconstruct any of these from context, OCR, lexical expectation, or another edition. Any eventual scene including body holds `7, 8, 9, 35, 36` must preserve explicit loss/unresolved markers and cannot claim all contributing pages are verified.

## Exact next activity — source-visible structural / scene inventory

Do **not** create scene files immediately. First create a durable structural inventory across scans **7–48**.

1. read the page records in source order;
2. identify every source-visible `காட்சி`, number, centered heading, stage/prose transition, or other printed structural marker;
3. do not infer scene numbers from plot/context;
4. determine the source-supported role of scan-47 centered **`உதயசூரியன் கோலம்`**;
5. record defensible page spans / structural units with provenance;
6. explicitly flag units touching scans `7, 8, 9, 35, 36` as containing unresolved/lost source text;
7. create a durable inventory document (recommended `STRUCTURAL_SCENE_INVENTORY.md`);
8. update page/work tracking and handover with the inventory result;
9. only then decide the exact `scenes/*.md` assembly mapping.

Do not begin English translation.

## Closed-work safeguards

`காகிதப்பூ` remains COMPLETE / CLOSED: Tamil 41/41, source-representation scenes 23/23, English 23/23, final reviews PASS. `மணிமகுடம்` and closed `கலைஞரின் நான்மணி மாலை` components remain closed unless explicitly reopened.