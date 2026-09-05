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
- scans 1–6 front matter; scans 7–48 dramatic work; scans 8–48 visibly carry printed pp.6–46; scan 49 back-cover advertisement.

## Historical-glyph verification — mandatory

Every page checks:

`ணா / ணை / ணொ / ணோ / லை / ளை / றா / றொ / றோ / னா / னை / னொ / னோ`.

Permanent rules: scan pixels control; read character identity rather than modern visual resemblance; encode proven identity in modern Unicode only; preserve source wording/punctuation otherwise; no global replacement or context-based modernization; use `needs-review` when evidence remains incomplete.

Positive same-edition reference families:

`லை / ளை / ணா / ணை / னா / னை / றா`.

Authoritative corrections that must not be reverted:

- scan 15 `என்றுரே / தானு` → **`என்றாரே / தானா`**;
- scan 20 `நன்றுக` → **`நன்றாக`**;
- scan 21 `மகனு` → **`மகனா`**;
- scan 28 `மால்தானே` → **`மாலைதானே`**.

## Current state after scans 1–40

**PAGE LAYER IN PROGRESS.**

- scans registered/page placeholders: **49 / 49**;
- canonical transcriptions processed: **40 / 49**;
- visually verified pages: **31 / 49** (`2, 6, 10–34, 37–40`);
- `needs-review`: **9 / 49** (`1, 3, 4, 5, 7, 8, 9, 35, 36`);
- historical-glyph passes complete: **40 / 49**;
- unprocessed: **9 / 49**;
- unresolved visual/source clusters: **3** (scan 35: 1; scan 36: 2);
- structural / scene inventory: **pending full source pass**;
- English translation: **not authorized / not started**.

### Batch 8 controls — scans 36–40

- scan 36 / p.34 — **NEEDS REVIEW**: scan-35 `எங்குவேன்` continues physically into `இப்போது`; `ஹரிஜன நலம்` / `சவலைப் பிள்ளை` passage transcribed; two short descriptive clusters remain visually insecure;
- scan 37 / p.35 — **VERIFIED**: Gandhi rejects the garland and hears of the Srirangam/Ranganathar fire; `மாலையை` historical `லை` decoded; source `ஓடிவந்துவிட்டானும் / போட்டானு?` retained;
- scan 38 / p.36 — **VERIFIED**: Gandhi rejects Desiyampillai and asks Eman to remove him; source `நாகத்திலும்` retained; page closes with buffalo push;
- scan 39 / p.37 — **VERIFIED**: stair/place-name sequence `கோவை / ஆம்பூர் / குடந்தை / மதுரை / உடுமலை`; final `உடுமலைப் படியில்` remains physically open to scan 40;
- scan 40 / p.38 — **VERIFIED**: continuation `கோபிப்படி / பாசிப்படி / விருதுநகர் / திருச்சி / தஞ்சை`; dream ends with source-visible `உதய சூரியன்`; wife appears with morning coffee.

Scans 36–40 do not securely resolve scan 35's existing cluster. Keep scan 35 and scan 36 review holds explicit.

Do not begin scene assembly or English translation during the page-layer phase.

## Exact next activity

Process **scans 41–45** source-first, corresponding to printed pages **39–43**.

For each:
1. inspect full native/enlarged source pixels;
2. transcribe only positively supported printed text;
3. preserve speaker/stage/paragraph/page structure;
4. run the full 13-family historical-glyph check;
5. use same-edition comparison only for glyph identity;
6. do not infer scene numbering or repair wording from context;
7. mark `verified` only after the complete visual + glyph gate passes;
8. use any genuine later evidence to re-adjudicate scans 35–36 only explicitly;
9. synchronize page-map, glyph audit, work/root READMEs, HANDOVER and NEXT prompt after the batch.

# CLOSED WORK SAFEGUARDS

`காகிதப்பூ` remains fully closed: Tamil 41/41, source-representation scenes 23/23, English 23/23, final reviews PASS. `மணிமகுடம்` and closed `கலைஞரின் நான்மணி மாலை` component works remain closed unless explicitly reopened.