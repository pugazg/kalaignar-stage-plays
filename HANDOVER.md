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
- scan 28 `மால்தானே` → **`மாலைதானே`**;
- scan 42 first-line old-type form → **`பொறாமை`** (`றா`);
- scan 44 page-ending old-type form → **`ஆலை முதலாளி`** (`லை`).

## Current state after scans 1–45

**PAGE LAYER IN PROGRESS.**

- scans registered/page placeholders: **49 / 49**;
- canonical transcriptions processed: **45 / 49**;
- visually verified pages: **36 / 49** (`2, 6, 10–34, 37–45`);
- `needs-review`: **9 / 49** (`1, 3, 4, 5, 7, 8, 9, 35, 36`);
- historical-glyph passes complete: **45 / 49**;
- unprocessed: **4 / 49**;
- unresolved visual/source clusters: **3** (scan 35: 1; scan 36: 2);
- structural / scene inventory: **pending full source pass**;
- English translation: **not authorized / not started**.

### Batch 9 controls — scans 41–45

All five are **VERIFIED**.

- scan 41 / p.39 — post-dream domestic scene and election-result shock; `மாறியிருக்கிறது / அருந்தினார் / கூறினாள்` historical identities checked; physical splits retained;
- scan 42 / p.40 — cost-of-living/tax argument; first-line apparent old-type form canonically `பொறாமை`; `அரையணா` checked; source `தீட்டி` retained; later ink near source-visible trailing `ஆள—` does not remove supported text;
- scan 43 / p.41 — governor-expense/election-politics dialogue; source colloquialisms and `கல்யாணங் காட்சிக்கு` retained; later ink does not remove recoverable text;
- scan 44 / p.42 — `தமிழ் வாழ்க` / obscenity-law argument; page-ending `ஆலை முதலாளி` decoded by historical `லை`; final `நிலப்பிரபு` remains physically open to scan 45;
- scan 45 / p.43 — scan-44 continuation `ஜமீன்தார்`, election-spending and `உதயசூரியன்` dialogue; colloquial register and physical splits retained.

Scans 41–45 do **not** genuinely resolve scans 35–36. Keep those three unresolved clusters explicit.

Do not begin scene assembly or English translation during the page-layer phase.

## Exact next activity — final source batch

Process **scans 46–49** source-first.

- scans 46–48 correspond to printed pages **44–46**;
- scan 48 is the source-visible final dramatic-body page;
- scan 49 is the back-cover advertisement for `அல்லி விழி` and must be treated as back matter, not dramatic text.

For each:
1. inspect full native/enlarged source pixels;
2. transcribe only positively supported printed text;
3. preserve speaker/stage/paragraph/page structure;
4. run the full 13-family historical-glyph check;
5. use same-edition comparison only for glyph identity;
6. do not infer scene numbering or repair wording from context;
7. mark `verified` only after the complete visual + glyph gate passes;
8. re-adjudicate scans 35–36 only if genuine same-edition evidence appears, documenting it explicitly;
9. synchronize page-map, glyph audit, work/root READMEs, HANDOVER and NEXT prompt;
10. after scans 46–49 are processed, perform a **page-layer completion audit** before authorizing scene assembly.

# CLOSED WORK SAFEGUARDS

`காகிதப்பூ` remains fully closed: Tamil 41/41, source-representation scenes 23/23, English 23/23, final reviews PASS. `மணிமகுடம்` and closed `கலைஞரின் நான்மணி மாலை` component works remain closed unless explicitly reopened.