# Kalaignar Stage Plays — Handover

Repository: `pugazg/kalaignar-stage-plays`, branch `main`.

## Startup rule

Always fetch live `main` first and preserve newer durable state. Permanent workflow: `STAGE_PLAY_PROCESSING_GUIDE.md`.

# ACTIVE WORK — திருவாளர் தேசீயம்பிள்ளை

## Mandatory startup

Read before further work:

1. `STAGE_PLAY_PROCESSING_GUIDE.md`;
2. this `HANDOVER.md`;
3. `NEXT_CHAT_PROMPT.md`;
4. `works/thiruvalar-desiyampillai/README.md`;
5. `works/thiruvalar-desiyampillai/metadata/source.md`;
6. `works/thiruvalar-desiyampillai/indexes/page-map.md`;
7. `works/thiruvalar-desiyampillai/HISTORICAL_GLYPH_AUDIT.md`;
8. `works/thiruvalar-desiyampillai/PAGE_LAYER_COMPLETION_AUDIT.md`;
9. `works/thiruvalar-desiyampillai/STRUCTURAL_SCENE_INVENTORY.md`;
10. relevant page records for the SRU currently being assembled;
11. controlling PDF only when a new page-level visual adjudication is required.

The user-supplied `HISTORICAL_TAMIL_GLYPH_TRANSCRIPTION_GUIDE.md` is mandatory methodology, not a lexical first-pass witness.

## Source identity

Controlling PDF: `TVA_BOK_0064118_திருவாளர்_தேசீயம்பிள்ளை.pdf`

- SHA-256: `b336bbebb326803badecbaa93de4ca4d63d80f68137fe70673b07a884c4910eb`;
- size: **58,035,177 bytes**;
- physical scans: **49**;
- source-visible second edition: **நவம்பர் 1965**;
- publisher: **K. R. நாராயணன்**;
- scans 1–6 front matter; scans 7–48 dramatic work; scans 8–48 visibly carry printed pp.6–46; scan 49 back-cover advertisement.

## Historical-glyph verification — complete

Every page received the full check for:

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

Final enlarged source rechecks preserve exact source forms on scans 46–48, including scan-46 `நம்ப`, scan-47 `போட்டகோலம்`, and scan-48 physical `மலை / யேறும்`.

## Page-layer state

**SOURCE-PAGE PASS COMPLETE.**

- scans/page records: **49 / 49**;
- canonical source processing: **49 / 49**;
- historical-glyph passes: **49 / 49**;
- visually verified pages: **40 / 49** (`2, 6, 10–34, 37–49`);
- `needs-review`: **9 / 49** (`1, 3, 4, 5, 7, 8, 9, 35, 36`);
- unprocessed: **0**;
- unresolved visual/source clusters: **3** (scan 35: 1; scan 36: 2).

Durable completion audit: `works/thiruvalar-desiyampillai/PAGE_LAYER_COMPLETION_AUDIT.md`.

Audit verdict: **coverage PASS, not 49/49 verified**. Structural/assembly work is allowed only if source-loss/review markers remain explicit.

### Review holds that must survive assembly

Front matter only:
- scans `1, 3, 4, 5` — physical loss/abrasion.

Dramatic body:
- scans `7, 8, 9` — physical paper-loss gaps;
- scan `35` — one unresolved cluster in `கொம்பு மாடெனக் … மட்டும்`;
- scan `36` — two unresolved descriptive clusters in the `ஹரிஜன நலம்` / `சவலைப் பிள்ளை` passage.

Do not use context, OCR, a modern edition, or lexical expectation to fill these gaps.

## Structural / scene inventory — COMPLETE / PASS

Durable inventory: `works/thiruvalar-desiyampillai/STRUCTURAL_SCENE_INVENTORY.md`.

Key result:

- dramatic scans inventoried: **42 / 42** (`7–48`);
- source-visible `காட்சி`, numbered scenes, or acts: **0**;
- editorial source-representation units: **7**;
- shared-page boundaries anchored on scans **15, 20, 28, 40**;
- scan-47 centered `உதயசூரியன் கோலம்`: **internal descriptive/intertitle inside SRU-07**, not a source scene title;
- scan-48 close: no printed `முற்றும்` marker.

The seven SRUs are editorial repository units only — **not source scene numbers**:

1. **SRU-01 — Yama court / Desiyampillai entrance** — scans 7–15 first portion; contains review holds 7–9.
2. **SRU-02 — Guesthouse / military-commandant hospitality** — scan 15 after adjournment through scan 20 before interview announcement.
3. **SRU-03 — Eman–Desiyampillai interview** — scan 20 interview announcement through first portion of scan 28.
4. **SRU-04 — Journey, Nandan and Gandhi / `சொர்க்கச் சிறை`** — scan 28 travel prose through scan 38; contains review holds 35–36.
5. **SRU-05 — Stair-fall and dream exit** — scans 39–40 before wife's entrance.
6. **SRU-06 — Waking domestic election argument** — scan 40 wife's entrance through scan 46.
7. **SRU-07 — Front yard, Kamala, `உதயசூரியன் கோலம்`, close** — scans 47–48.

### Shared-page controls

- scan 15: SRU-01 ends at the parenthetical court adjournment; SRU-02 starts `எமதர்ம ராஜனின் மாளிகையிலுள்ள விருந்து விடுதியில்...`;
- scan 20: SRU-02 ends after the commandant leaves; SRU-03 starts `எமன், தேசீயம்பிள்ளை பேட்டி துவங்குகிறது.`;
- scan 28: SRU-03 ends after `தேசீ : மாலைதானே...வாங்கிக் கொள்ளலாம்...`; SRU-04 starts `இருவரும் எழுந்து காந்தியைக் காணப் பயணம் படுகிறார்கள்.`;
- scan 40: SRU-05 ends after the wake-from-dream prose through `சுற்றும் முற்றும் பார்த்தார்.`; SRU-06 starts `அவரது மனைவி காலைக் காப்பியுடன் எதிரே வந்து நின்றாள்.`.

## Exact next activity — Tamil source-representation assembly

Create exactly these seven descriptive files in source order:

1. `works/thiruvalar-desiyampillai/scenes/sru-01-yama-court.md`
2. `works/thiruvalar-desiyampillai/scenes/sru-02-guesthouse.md`
3. `works/thiruvalar-desiyampillai/scenes/sru-03-eman-interview.md`
4. `works/thiruvalar-desiyampillai/scenes/sru-04-gandhi-journey.md`
5. `works/thiruvalar-desiyampillai/scenes/sru-05-stairfall-dream-exit.md`
6. `works/thiruvalar-desiyampillai/scenes/sru-06-domestic-election-argument.md`
7. `works/thiruvalar-desiyampillai/scenes/sru-07-udayasuriyan-kolam-close.md`

Assembly rules:

- assemble only from `pages/0007.md`–`0048.md`;
- scan 49 is back matter and must not enter scenes;
- front matter 1–6 remains outside scene assembly;
- use `source_scene_number: null`; do not imply the SRU sequence is source numbering;
- preserve all source wording, speaker labels, parentheticals, prose, punctuation and unusual forms;
- join only mechanical page/line breaks that are positively continuous;
- SRU-01 must preserve every `[paper loss]` marker and use `assembled_from_verified_pages: false`;
- SRU-04 must preserve scan-35 `[unresolved glyph cluster]` and both scan-36 `[unresolved descriptive cluster]` markers and use `assembled_from_verified_pages: false`;
- SRU-02, 03, 05, 06, 07 may use `assembled_from_verified_pages: true` after clean assembly;
- preserve scan-47 `உதயசூரியன் கோலம்` as a standalone internal source line within SRU-07;
- do not add `காட்சி`, numbered scenes, curtain directions, or `முற்றும்`.

After all seven SRUs are assembled, create a durable full Tamil assembly review and compare every unit back to the contributing page records before any English translation.

# CLOSED WORK SAFEGUARDS

`காகிதப்பூ` remains fully closed: Tamil 41/41, source-representation scenes 23/23, English 23/23, final reviews PASS. `மணிமகுடம்` and closed `கலைஞரின் நான்மணி மாலை` component works remain closed unless explicitly reopened.