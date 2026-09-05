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
11. `works/thiruvalar-desiyampillai/TRANSLATION_PLAN.md`;
12. `works/thiruvalar-desiyampillai/translations/en/README.md`;
13. the Tamil SRU(s) for the current translation batch;
14. controlling PDF/page records only if a genuine source adjudication is required.

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

Review holds remain authoritative:

- front matter `1, 3, 4, 5` — physical loss/abrasion;
- body `7, 8, 9` — physical paper-loss gaps;
- scan `35` — one unresolved cluster in `கொம்பு மாடெனக் … மட்டும்`;
- scan `36` — two unresolved descriptive clusters in the `ஹரிஜன நலம்` / `சவலைப் பிள்ளை` passage.

Do not fill these from context, OCR, another edition or lexical expectation.

## Structural / scene inventory — COMPLETE / PASS

Durable inventory: `works/thiruvalar-desiyampillai/STRUCTURAL_SCENE_INVENTORY.md`.

- dramatic scans inventoried: **42 / 42** (`7–48`);
- source-visible `காட்சி`, numbered scenes or acts: **0**;
- editorial SRUs: **7**;
- shared-page boundaries anchored on scans **15, 20, 28, 40**;
- scan-47 centered `உதயசூரியன் கோலம்`: internal descriptive/intertitle inside SRU-07;
- scan-48 close: no printed `முற்றும்`.

The SRU labels are repository/editorial identifiers only, not source scene numbers.

## Tamil source-representation assembly — COMPLETE / REVIEWED / PASS

Durable review: `works/thiruvalar-desiyampillai/ASSEMBLY_REVIEW.md`.

Seven Tamil SRUs are complete:

1. `scenes/sru-01-yama-court.md`
2. `scenes/sru-02-guesthouse.md`
3. `scenes/sru-03-eman-interview.md`
4. `scenes/sru-04-gandhi-journey.md`
5. `scenes/sru-05-stairfall-dream-exit.md`
6. `scenes/sru-06-domestic-election-argument.md`
7. `scenes/sru-07-udayasuriyan-kolam-close.md`

Review-hold propagation:

- **SRU-01:** `assembled_from_verified_pages: false`; all seven scan 7–9 `[paper loss]` markers retained.
- **SRU-04:** `assembled_from_verified_pages: false`; scan-35 `[unresolved glyph cluster]` and both scan-36 `[unresolved descriptive cluster]` markers retained; apparent `கொழுப்பேறி` remains non-canonical.
- **SRU-02 / 03 / 05 / 06 / 07:** verified-source assembly.

The Tamil archival layer is **assembly-complete / reviewed for current source evidence** and must not be changed by translation choices.

## English translation plan — READY / REVIEWED

Durable plan: `works/thiruvalar-desiyampillai/TRANSLATION_PLAN.md`.

Tracker: `works/thiruvalar-desiyampillai/translations/en/README.md`.

**Translation body is NOT YET AUTHORIZED / NOT STARTED.**

Plan controls:

- immediate drafting authority: reviewed Tamil `scenes/sru-*.md` only;
- no OCR/PDF/another edition/web/general-knowledge/secondary-English drafting;
- expected English artifacts: **7**, with filenames mirroring the Tamil SRUs;
- source has no numbered scenes/acts; English must not invent them;
- SRU-01 must preserve all **7** exact `[paper loss]` markers;
- SRU-04 must preserve **1** exact `[unresolved glyph cluster]` and **2** exact `[unresolved descriptive cluster]` markers;
- no missing wording may be inferred around those markers;
- preserve speaker-label variation, narrative prose, stage directions, repetitions, satire, political rhetoric, colloquial register, proper names and supported ambiguity;
- scan-47 `உதயசூரியன் கோலம்` remains an internal descriptive/intertitle in the final English SRU;
- scan 48 has no source `முற்றும்`; do not add `The End` or equivalent;
- all first-pass English artifacts must use `secondary_english_witness_used: false`;
- each artifact requires complete Tamil→English fidelity review before `translation_review: passed`;
- each batch requires a durable `BATCH_0N_REVIEW.md`;
- final closure requires `translations/en/TRANSLATION_REVIEW.md`.

Proposed batches:

1. **Batch 1:** SRU-01 + SRU-02
2. **Batch 2:** SRU-03
3. **Batch 3:** SRU-04
4. **Batch 4:** SRU-05 + SRU-06 + SRU-07

Current English metrics:

- expected artifacts: **7**;
- present: **0 / 7**;
- reviewed: **0 / 7**;
- completed batches: **0 / 4**;
- secondary-English witness use: **0**;
- Tamil archival layer modified by translation: **no**.

## Exact next activity — requires explicit authorization

Do not create English SRU body files until the user explicitly authorizes translation.

After authorization, process **English Translation Batch 1**:

- `scenes/sru-01-yama-court.md` → `translations/en/sru-01-yama-court.md`
- `scenes/sru-02-guesthouse.md` → `translations/en/sru-02-guesthouse.md`

Translate only from the complete reviewed Tamil SRUs, perform full Tamil→English fidelity review for both, preserve all seven SRU-01 `[paper loss]` markers, and create `translations/en/BATCH_01_REVIEW.md` before calling the batch PASS / LOCKED.

# CLOSED WORK SAFEGUARDS

`காகிதப்பூ` remains fully closed: Tamil 41/41, source-representation scenes 23/23, English 23/23, final reviews PASS. `மணிமகுடம்` and closed `கலைஞரின் நான்மணி மாலை` component works remain closed unless explicitly reopened.
