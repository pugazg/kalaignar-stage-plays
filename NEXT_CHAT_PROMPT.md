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
9. `works/thiruvalar-desiyampillai/STRUCTURAL_SCENE_INVENTORY.md`
10. relevant page records for each SRU being assembled
11. controlling PDF only if a new page-level visual adjudication is required

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
- unresolved visual/source clusters: **3** (scan 35: 1; scan 36: 2).

Completion audit: `works/thiruvalar-desiyampillai/PAGE_LAYER_COMPLETION_AUDIT.md`.

Audit verdict: **coverage PASS but not 49/49 verified**. Scene/assembly work may proceed only if every loss/unresolved marker is preserved.

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
- scan 46 source colloquial `நம்ப`, not `நம்ம`;
- scans 46–48 source work/name spelling `தேசீயம்`;
- scan 47 source `போட்டகோலம்`;
- scan 48 physical `மலை / யேறும்`.

## Structural / scene inventory checkpoint

`works/thiruvalar-desiyampillai/STRUCTURAL_SCENE_INVENTORY.md` is **PASS / REVIEWED**.

Findings:

- dramatic scans inventoried: **42 / 42** (`7–48`);
- source-visible `காட்சி`, numbered scenes, or acts: **0**;
- editorial source-representation units: **7**;
- shared-page boundaries explicitly anchored on scans **15, 20, 28, 40**;
- scan-47 centered `உதயசூரியன் கோலம்` is an **internal descriptive/intertitle in SRU-07**, not a source scene title;
- scan-48 has no printed `முற்றும்` marker.

The SRU numbers are repository/editorial identifiers only. They must never be described as source scene numbers.

## Review holds that must remain explicit

Front matter:
- `1, 3, 4, 5` — physical loss/abrasion; not part of scenes.

Dramatic body:
- `7, 8, 9` — physical paper-loss gaps;
- `35` — one `[unresolved glyph cluster]` in `கொம்பு மாடெனக் … மட்டும்`;
- `36` — two `[unresolved descriptive cluster]` markers in the `ஹரிஜன நலம்` / `சவலைப் பிள்ளை` passage.

Do not reconstruct any of these from context, OCR, lexical expectation, or another edition.

## Exact next activity — Tamil scene/source-representation assembly

Create these seven files in source order:

1. `works/thiruvalar-desiyampillai/scenes/sru-01-yama-court.md`
2. `works/thiruvalar-desiyampillai/scenes/sru-02-guesthouse.md`
3. `works/thiruvalar-desiyampillai/scenes/sru-03-eman-interview.md`
4. `works/thiruvalar-desiyampillai/scenes/sru-04-gandhi-journey.md`
5. `works/thiruvalar-desiyampillai/scenes/sru-05-stairfall-dream-exit.md`
6. `works/thiruvalar-desiyampillai/scenes/sru-06-domestic-election-argument.md`
7. `works/thiruvalar-desiyampillai/scenes/sru-07-udayasuriyan-kolam-close.md`

Assembly controls:

- assemble only from `pages/0007.md` through `pages/0048.md`;
- use `source_scene_number: null` and an explicit `structural_unit: "SRU-0N"` field;
- do not use `scene: N` in a way that implies source numbering;
- join only proven mechanical page/line breaks;
- do not normalize vocabulary, colloquial speech, speaker labels, punctuation, political slogans, or historical-glyph decisions;
- SRU-01 must preserve every `[paper loss]` marker and set `assembled_from_verified_pages: false`;
- SRU-04 must preserve scan-35 `[unresolved glyph cluster]` and both scan-36 `[unresolved descriptive cluster]` markers and set `assembled_from_verified_pages: false`;
- SRU-02, SRU-03, SRU-05, SRU-06, SRU-07 may set `assembled_from_verified_pages: true` after clean assembly;
- preserve scan-47 `உதயசூரியன் கோலம்` as a standalone internal source line inside SRU-07;
- do not add source `காட்சி` numbers, act divisions, curtain directions, or `முற்றும்`;
- use the exact shared-page anchors from `STRUCTURAL_SCENE_INVENTORY.md` at scans 15, 20, 28 and 40 so no text is duplicated or omitted.

After creating all seven files, perform a **full Tamil assembly review** against the page records. Only after that review passes may the Tamil assembly layer be called complete. Do not begin English translation yet.

## Closed-work safeguards

`காகிதப்பூ` remains COMPLETE / CLOSED: Tamil 41/41, source-representation scenes 23/23, English 23/23, final reviews PASS. `மணிமகுடம்` and closed `கலைஞரின் நான்மணி மாலை` components remain closed unless explicitly reopened.