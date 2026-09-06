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
5. `works/thiruvalar-desiyampillai/PAGE_LAYER_COMPLETION_AUDIT.md`;
6. `works/thiruvalar-desiyampillai/STRUCTURAL_SCENE_INVENTORY.md`;
7. `works/thiruvalar-desiyampillai/ASSEMBLY_REVIEW.md`;
8. `works/thiruvalar-desiyampillai/TRANSLATION_PLAN.md`;
9. `works/thiruvalar-desiyampillai/translations/en/README.md`;
10. completed batch reviews `translations/en/BATCH_01_REVIEW.md` and `translations/en/BATCH_02_REVIEW.md`;
11. complete reviewed Tamil `scenes/sru-04-gandhi-journey.md` for the current batch;
12. page records / controlling PDF only when a genuine source adjudication is required.

The user-supplied `HISTORICAL_TAMIL_GLYPH_TRANSCRIPTION_GUIDE.md` remains methodology for the closed Tamil source layer, not an English lexical witness.

## Source identity

Controlling PDF: `TVA_BOK_0064118_திருவாளர்_தேசீயம்பிள்ளை.pdf`

- SHA-256: `b336bbebb326803badecbaa93de4ca4d63d80f68137fe70673b07a884c4910eb`;
- size: **58,035,177 bytes**;
- physical scans: **49**;
- source-visible second edition: **நவம்பர் 1965**;
- publisher: **K. R. நாராயணன்**;
- scans 1–6 front matter; scans 7–48 dramatic work; scan 49 back-cover advertisement.

## Tamil archival layer — CLOSED FOR CURRENT SOURCE EVIDENCE

- source processing: **49 / 49**;
- historical-glyph passes: **49 / 49**;
- visually verified pages: **40 / 49**;
- `needs-review`: **9 / 49** (`1, 3, 4, 5, 7, 8, 9, 35, 36`);
- unresolved visual/source clusters: **3**.

Authoritative glyph/source decisions include scan-15 `என்றாரே / தானா`, scan-20 `நன்றாக`, scan-21 `மகனா`, scan-28 `மாலைதானே`, scan-42 `பொறாமை`, scan-44 `ஆலை முதலாளி`, scan-46 `நம்ப`, scan-47 `போட்டகோலம்`, and scan-48 physical `மலை / யேறும்` → assembled `மலையேறும்`.

Review holds remain authoritative:

- front matter `1, 3, 4, 5` — physical loss/abrasion;
- body `7, 8, 9` — `[paper loss]` gaps;
- scan `35` — one `[unresolved glyph cluster]`;
- scan `36` — two `[unresolved descriptive cluster]` markers.

Do not fill these from context, OCR, another edition, English translation, or lexical expectation.

## Structural / Tamil assembly state — COMPLETE / PASS

`STRUCTURAL_SCENE_INVENTORY.md`: **PASS / REVIEWED**.

- source-visible numbered scenes/acts: **0**;
- editorial SRUs: **7**;
- scan-47 `உதயசூரியன் கோலம்`: internal descriptive/intertitle;
- scan 48: no source `முற்றும்`.

`ASSEMBLY_REVIEW.md`: **PASS / REVIEWED**.

Seven Tamil SRUs are complete and closed against translation-driven edits:

1. `scenes/sru-01-yama-court.md`
2. `scenes/sru-02-guesthouse.md`
3. `scenes/sru-03-eman-interview.md`
4. `scenes/sru-04-gandhi-journey.md`
5. `scenes/sru-05-stairfall-dream-exit.md`
6. `scenes/sru-06-domestic-election-argument.md`
7. `scenes/sru-07-udayasuriyan-kolam-close.md`

## English translation — AUTHORIZED / IN PROGRESS

Translation plan: `works/thiruvalar-desiyampillai/TRANSLATION_PLAN.md`.

Tracker: `works/thiruvalar-desiyampillai/translations/en/README.md`.

Immediate drafting authority: **reviewed Tamil SRUs only**. Do not draft from OCR, PDF text, another edition, web text, general knowledge, or a secondary English witness.

Expected English artifacts: **7** across four batches.

### Batch 01 — PASS / LOCKED

Durable review: `translations/en/BATCH_01_REVIEW.md`.

- `translations/en/sru-01-yama-court.md` — reviewed; all **7 / 7** `[paper loss]` markers retained;
- `translations/en/sru-02-guesthouse.md` — reviewed;
- secondary-English witness use: **0**;
- blocking issues: **0**.

### Batch 02 — PASS / LOCKED

Durable review: `translations/en/BATCH_02_REVIEW.md`.

- `translations/en/sru-03-eman-interview.md` — **translation-reviewed / passed**;
- source labels kept traceable as `Desiyam Pillai :` / `Desi :` / `Yama :`;
- repeated `pillai` sequence preserved with `keeripillai / thennampillai / anilpillai / kilippillai`;
- `uyarthinai / ahrinai` and `pancha-varnam / pancham` retained for wordplay;
- `kudi / soranai` retained rather than overconfidently replaced;
- Kumbakonam reference retained without invented gloss;
- impossible-object tax joke translated literally;
- Five-Year Plan / magician / corruption-disease satire reviewed in full;
- source-supported unusual `ஆளைப் பார்த்தே மானால்` documented, not used to revise Tamil;
- *devangu* retained without uncertain external identification;
- exact end boundary at `மாலைதானே...வாங்கிக் கொள்ளலாம்...` preserved before SRU-04 travel prose;
- secondary-English witness use: **0**;
- blocking issues: **0**.

Current English metrics:

- expected artifacts: **7**;
- present: **3 / 7**;
- reviewed: **3 / 7**;
- completed batches: **2 / 4**;
- secondary-English witness use: **0**;
- final `TRANSLATION_REVIEW.md`: **not started**.

## Exact next activity — English Translation Batch 03

Process only:

`scenes/sru-04-gandhi-journey.md` → `translations/en/sru-04-gandhi-journey.md`

Requirements:

1. read the complete reviewed Tamil SRU;
2. draft English only from that SRU;
3. preserve exactly the scan-35 `[unresolved glyph cluster]` marker;
4. preserve exactly both scan-36 `[unresolved descriptive cluster]` markers;
5. do not infer text around those markers or promote apparent `கொழுப்பேறி` into English;
6. preserve Gandhi/Nandan/Yama/Desiyampillai structure, political satire, historically loaded terms, rhetoric, repetitions and source ambiguity;
7. do not use a secondary English witness;
8. perform a complete Tamil→English fidelity review;
9. set `translation_review: "passed"` only after the review;
10. create `translations/en/BATCH_03_REVIEW.md` and update tracker/plan/handover only after Batch 03 passes.

Do not begin Batch 04 until Batch 03 is durably closed and the user proceeds again.

# CLOSED WORK SAFEGUARDS

`காகிதப்பூ` remains fully closed: Tamil 41/41, source-representation scenes 23/23, English 23/23, final reviews PASS. `மணிமகுடம்` and closed `கலைஞரின் நான்மணி மாலை` component works remain closed unless explicitly reopened.