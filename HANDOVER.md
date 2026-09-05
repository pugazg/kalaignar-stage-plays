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
10. `works/thiruvalar-desiyampillai/ASSEMBLY_REVIEW.md`;
11. all seven `works/thiruvalar-desiyampillai/scenes/sru-*.md` files before any translation planning;
12. controlling PDF only when a new page-level visual adjudication is required.

The user-supplied `HISTORICAL_TAMIL_GLYPH_TRANSCRIPTION_GUIDE.md` is mandatory methodology, not a lexical first-pass witness.

## Source identity

Controlling PDF: `TVA_BOK_0064118_திருவாளர்_தேசீயம்பிள்ளை.pdf`

- SHA-256: `b336bbebb326803badecbaa93de4ca4d63d80f68137fe70673b07a884c4910eb`;
- size: **58,035,177 bytes**;
- physical scans: **49**;
- source-visible second edition: **நவம்பர் 1965**;
- publisher: **K. R. நாராயணன்**;
- scans 1–6 front matter; scans 7–48 dramatic work; scans 8–48 visibly carry printed pp.6–46; scan 49 back-cover advertisement.

## Historical-glyph verification — COMPLETE

Every scan received the full 13-family check:

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

Final enlarged source rechecks preserve exact source forms on scans 46–48, including scan-46 `நம்ப`, scan-46 `தேசீயம் பிள்ளை`, scan-47 `தேசீயம்பிள்ளை / தேசீயம் பிள்ளையின் / போட்டகோலம்`, and scan-48 physical `மலை / யேறும்`.

## Page-layer state — COMPLETE / COVERAGE PASS

- scans/page records: **49 / 49**;
- canonical source processing: **49 / 49**;
- historical-glyph passes: **49 / 49**;
- visually verified pages: **40 / 49** (`2, 6, 10–34, 37–49`);
- `needs-review`: **9 / 49** (`1, 3, 4, 5, 7, 8, 9, 35, 36`);
- unprocessed: **0**;
- unresolved visual/source clusters: **3** (scan 35: 1; scan 36: 2).

Durable completion audit: `works/thiruvalar-desiyampillai/PAGE_LAYER_COMPLETION_AUDIT.md`.

Audit verdict: **coverage PASS, not 49/49 verified**.

### Review holds that remain authoritative

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

The SRU labels are repository/editorial identifiers only — **not source scene numbers**.

## Tamil source-representation assembly — COMPLETE / REVIEWED / PASS

Durable review: `works/thiruvalar-desiyampillai/ASSEMBLY_REVIEW.md`.

Seven files are complete:

1. `scenes/sru-01-yama-court.md`
2. `scenes/sru-02-guesthouse.md`
3. `scenes/sru-03-eman-interview.md`
4. `scenes/sru-04-gandhi-journey.md`
5. `scenes/sru-05-stairfall-dream-exit.md`
6. `scenes/sru-06-domestic-election-argument.md`
7. `scenes/sru-07-udayasuriyan-kolam-close.md`

Assembly review checks:

- SRUs present: **7 / 7**;
- dramatic source scans represented: **42 / 42**;
- shared-page boundaries checked: **4 / 4** (`15, 20, 28, 40`);
- source scene numbers invented: **0**;
- source act numbers invented: **0**;
- scan 49 included in dramatic assembly: **no**;
- invented `முற்றும்`: **no**;
- scan-47 `உதயசூரியன் கோலம்`: preserved internally in SRU-07.

### Review-hold propagation

SRU-01:
- `assembled_from_verified_pages: false`;
- preserves all scan 7–9 `[paper loss]` markers;
- the damaged scan-9 `எங்கே ஜனநாயக[paper loss]` is not repaired from the repeated intact line.

SRU-04:
- `assembled_from_verified_pages: false`;
- preserves scan-35 `[unresolved glyph cluster]`;
- preserves both scan-36 `[unresolved descriptive cluster]` markers;
- apparent `கொழுப்பேறி` is not promoted into canonical text.

SRU-02, SRU-03, SRU-05, SRU-06 and SRU-07:
- assembled from verified contributing source text;
- `assembled_from_verified_pages: true`.

Important source-form controls carried into assembly include `என்றாரே`, `தானா`, `நன்றாக`, `மகனா`, `மாலைதானே`, `பொறாமை`, `ஆலை முதலாளி`, scan-46 `நம்ப`, scan-46 `தேசீயம் பிள்ளை`, scan-47 `தேசீயம்பிள்ளை / தேசீயம் பிள்ளையின்`, and scan-48 `மலையேறும்` from physical `மலை / யேறும்`.

The Tamil archival layer is now **assembly-complete / reviewed for the current source evidence**. The nine underlying page-level `needs-review` records remain source-condition limitations and are not silently upgraded.

## English translation state

**NOT AUTHORIZED / NOT STARTED.**

Do not draft English directly from page OCR, the PDF, another edition, web text, or general knowledge. If English is later authorized, immediate drafting authority must be the reviewed seven Tamil SRUs. Translation must never retroactively alter the Tamil source layer.

## Exact next activity — English translation plan only

Create a durable source-faithful translation plan, but **do not begin translation until the plan is explicitly authorized**.

The plan must specify:

- seven English artifacts mirroring the seven reviewed Tamil SRUs, without inventing numbered source scenes;
- immediate drafting authority: reviewed Tamil `scenes/sru-*.md` only;
- how `[paper loss]`, `[unresolved glyph cluster]`, and `[unresolved descriptive cluster]` are represented in English without guessing;
- preservation of speaker-label variation, narrative prose, stage directions, political satire/rhetoric, colloquial register, repetitions and source ambiguity;
- preservation of `உதயசூரியன் கோலம்` as an internal descriptive/intertitle in the final English SRU;
- no invented `முற்றும்` / “The End” marker;
- review procedure comparing each English artifact back to its complete Tamil SRU;
- translation batch/order proposal and a final full translation-review gate.

# CLOSED WORK SAFEGUARDS

`காகிதப்பூ` remains fully closed: Tamil 41/41, source-representation scenes 23/23, English 23/23, final reviews PASS. `மணிமகுடம்` and closed `கலைஞரின் நான்மணி மாலை` component works remain closed unless explicitly reopened.