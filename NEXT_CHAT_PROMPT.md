# Next Chat Prompt — Kalaignar Stage Plays / திருவாளர் தேசீயம்பிள்ளை

Continue directly in `pugazg/kalaignar-stage-plays`, branch `main`, active work `works/thiruvalar-desiyampillai/`.

## LIVE MAIN IS AUTHORITATIVE

Fetch live `main` first. Preserve newer durable state. Do not reopen closed காகிதப்பூ / மணிமகுடம் / நான்மணி மாலை work because an older copied prompt contains a stale checkpoint.

## Mandatory startup

Read before source-dependent work:

1. `STAGE_PLAY_PROCESSING_GUIDE.md`
2. `HANDOVER.md`
3. this `NEXT_CHAT_PROMPT.md`
4. `works/thiruvalar-desiyampillai/README.md`
5. `works/thiruvalar-desiyampillai/metadata/source.md`
6. `works/thiruvalar-desiyampillai/indexes/page-map.md`
7. `works/thiruvalar-desiyampillai/HISTORICAL_GLYPH_AUDIT.md`
8. relevant page records for the current batch
9. the controlling PDF must be attached/resolved before page-level visual work

The user-supplied `HISTORICAL_TAMIL_GLYPH_TRANSCRIPTION_GUIDE.md` is mandatory methodology, not a lexical first-pass witness.

## Current source

`TVA_BOK_0064118_திருவாளர்_தேசீயம்பிள்ளை.pdf`

- SHA-256: `b336bbebb326803badecbaa93de4ca4d63d80f68137fe70673b07a884c4910eb`
- size: **58,035,177 bytes**
- scans: **49**
- second edition: **நவம்பர் 1965**
- publisher: **K. R. நாராயணன்**

## Historical Tamil glyph rule

Every scan must check:

`ணா / ணை / ணொ / ணோ / லை / ளை / றா / றொ / றோ / னா / னை / னொ / னோ`.

Positive same-edition reference families:

`லை / ளை / ணா / ணை / னா / னை / றா`.

Authoritative corrections — never restore superseded apparent-shape readings:

- scan 15 `என்றுரே / தானு` → **`என்றாரே / தானா`**;
- scan 20 `நன்றுக` → **`நன்றாக`**;
- scan 21 `மகனு` → **`மகனா`**;
- scan 28 `மால்தானே` → **`மாலைதானே`**.

Use same-edition references only for character identity. Do not reconstruct physical loss or regularize source wording.

## Completed scans 1–40

- Batch 1, scans 1–5: scan 2 verified; 1, 3, 4, 5 `needs-review`.
- Batch 2, scans 6–10: 6 and 10 verified; 7, 8, 9 `needs-review`.
- Batches 3–6, scans 11–30: all verified.
- Batch 7, scans 31–35: 31–34 verified; scan 35 `needs-review` for one unresolved cluster in `கொம்பு மாடெனக் … மட்டும்`.
- Batch 8, scans 36–40:
  - `0036.md` / p.34 — **needs-review**; full pass complete; two short descriptive clusters in the `ஹரிஜன நலம்` / `சவலைப் பிள்ளை` passage remain unresolved; opening physically continues scan-35 `எங்குவேன்`;
  - `0037.md` / p.35 — **verified**; Gandhi rejects the garland; Srirangam/Ranganathar-fire report; `மாலையை` historical `லை`; source `ஓடிவந்துவிட்டானும் / போட்டானு?` retained;
  - `0038.md` / p.36 — **verified**; Gandhi asks Eman to remove Desiyampillai; source `நாகத்திலும்` retained; buffalo-push close;
  - `0039.md` / p.37 — **verified**; stair/place-name sequence `கோவை / ஆம்பூர் / குடந்தை / மதுரை / உடுமலை`; final `உடுமலைப் படியில்` continues physically;
  - `0040.md` / p.38 — **verified**; `கோபிப்படி / பாசிப்படி / விருதுநகர் / திருச்சி / தஞ்சை`; dream ends with `உதய சூரியன்`; wife enters with morning coffee.

Scans 36–40 do not securely resolve scan 35's review cluster.

Current metrics:

- canonical page transcriptions processed: **40 / 49**;
- visually verified: **31 / 49** (`2, 6, 10–34, 37–40`);
- `needs-review`: **9 / 49** (`1, 3, 4, 5, 7, 8, 9, 35, 36`);
- historical-glyph passes: **40 / 49**;
- unprocessed: **9 / 49**;
- unresolved visual/source clusters: **3** (scan 35: 1; scan 36: 2);
- English translation: **not authorized / not started**.

## Exact next activity — scans 41–45

Process scans **41, 42, 43, 44, 45** in order. They correspond to printed pages **39–43**.

For each page:

1. inspect complete source pixels and enlarge difficult regions;
2. transcribe only positively supported printed text;
3. preserve exact speaker labels, punctuation, stage/prose structure and physical page boundaries;
4. keep damage/handwriting/library marks separate;
5. complete the full 13-family historical-glyph check;
6. use same-edition comparison for glyph identity only;
7. do not infer missing wording, modern spelling or scene numbers;
8. mark `verified` only when the full visual + glyph gate passes, otherwise `needs-review`;
9. if genuine later evidence resolves scans 35 or 36, re-open those records explicitly and document the adjudication;
10. update page-map, glyph audit, work/root READMEs, HANDOVER and this prompt after the batch.

Do not begin scene assembly or English translation yet.

## Closed-work safeguards

`காகிதப்பூ` remains COMPLETE / CLOSED: Tamil 41/41, source-representation scenes 23/23, English 23/23, final reviews PASS. `மணிமகுடம்` and closed `கலைஞரின் நான்மணி மாலை` components remain closed unless explicitly reopened.