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
10. completed batch review(s), currently `translations/en/BATCH_01_REVIEW.md`;
11. the complete reviewed Tamil SRU for the current translation batch;
12. page records / controlling PDF only when a genuine source adjudication is required.

The user-supplied `HISTORICAL_TAMIL_GLYPH_TRANSCRIPTION_GUIDE.md` remains mandatory methodology for the closed Tamil source layer, not a lexical English witness.

## Source identity

Controlling PDF: `TVA_BOK_0064118_திருவாளர்_தேசீயம்பிள்ளை.pdf`

- SHA-256: `b336bbebb326803badecbaa93de4ca4d63d80f68137fe70673b07a884c4910eb`;
- size: **58,035,177 bytes**;
- physical scans: **49**;
- source-visible second edition: **நவம்பர் 1965**;
- publisher: **K. R. நாராயணன்**;
- scans 1–6 front matter; scans 7–48 dramatic work; scan 49 back-cover advertisement.

## Tamil archival layer — CLOSED FOR CURRENT SOURCE EVIDENCE

Page/source state:

- source processing: **49 / 49**;
- historical-glyph passes: **49 / 49**;
- visually verified pages: **40 / 49**;
- `needs-review`: **9 / 49** (`1, 3, 4, 5, 7, 8, 9, 35, 36`);
- unresolved visual/source clusters: **3**.

Authoritative glyph/source decisions that must not be reverted include:

- scan 15 `என்றுரே / தானு` → `என்றாரே / தானா`;
- scan 20 `நன்றுக` → `நன்றாக`;
- scan 21 `மகனு` → `மகனா`;
- scan 28 `மால்தானே` → `மாலைதானே`;
- scan 42 `பொறாமை`;
- scan 44 `ஆலை முதலாளி`;
- scan 46 colloquial `நம்ப`;
- scan 47 `போட்டகோலம்`;
- scan 48 physical `மலை / யேறும்` → assembled `மலையேறும்`.

Review holds remain authoritative:

- front matter `1, 3, 4, 5` — physical loss/abrasion;
- body `7, 8, 9` — physical `[paper loss]` gaps;
- scan `35` — one `[unresolved glyph cluster]`;
- scan `36` — two `[unresolved descriptive cluster]` markers.

Do not fill these from context, OCR, another edition, English translation, or lexical expectation.

## Structural / Tamil assembly state — COMPLETE / PASS

`STRUCTURAL_SCENE_INVENTORY.md`: **PASS / REVIEWED**.

- source-visible numbered scenes/acts: **0**;
- editorial SRUs: **7**;
- scan-47 `உதயசூரியன் கோலம்`: internal descriptive/intertitle, not a source scene title;
- scan 48: no source `முற்றும்`.

`ASSEMBLY_REVIEW.md`: **PASS / REVIEWED**.

Seven Tamil SRUs are complete:

1. `scenes/sru-01-yama-court.md`
2. `scenes/sru-02-guesthouse.md`
3. `scenes/sru-03-eman-interview.md`
4. `scenes/sru-04-gandhi-journey.md`
5. `scenes/sru-05-stairfall-dream-exit.md`
6. `scenes/sru-06-domestic-election-argument.md`
7. `scenes/sru-07-udayasuriyan-kolam-close.md`

The Tamil layer must not be changed because of English translation choices.

## English translation — AUTHORIZED / IN PROGRESS

Translation plan: `works/thiruvalar-desiyampillai/TRANSLATION_PLAN.md`.

Tracker: `works/thiruvalar-desiyampillai/translations/en/README.md`.

Immediate drafting authority: **reviewed Tamil SRUs only**. Do not draft from OCR, PDF text, another edition, web text, general knowledge, or a secondary English witness.

Expected English artifacts: **7** across four batches.

### Batch 01 — PASS / LOCKED

Durable review: `works/thiruvalar-desiyampillai/translations/en/BATCH_01_REVIEW.md`.

Completed and fully reviewed:

- `translations/en/sru-01-yama-court.md`;
- `translations/en/sru-02-guesthouse.md`.

Batch 01 controls:

- SRU-01 `[paper loss]` markers preserved: **7 / 7**;
- source speaker-label variation kept traceable;
- no source scene/act numbering invented;
- no secondary-English witness used;
- Tamil archival files modified by translation: **0**;
- blocking translation issues: **0**.

Important Batch-01 source-sensitive English decisions include:

- `Thiruvalar` retained as title/honorific;
- `Desiyam Pillai` / `Desiyampillai` source-form distinction kept traceable;
- `OneRepresentative:` versus `One Representative:` preserves source label spacing variation;
- *padai* / *bhasha*, `kedu`, `darshan`, `Udhagai Mandalam`, *Oppari*, *kollisatti*, Vadivazhagi-Vaikkarisi retained where smoothing would erase source register/wordplay;
- Kallakudi / Thoothukudi / Salem / Valparai beverage sequence kept as source wordplay rather than expanded from outside history.

Current English metrics:

- expected artifacts: **7**;
- present: **2 / 7**;
- reviewed: **2 / 7**;
- completed batches: **1 / 4**;
- secondary-English witness use: **0**;
- final `TRANSLATION_REVIEW.md`: **not started**.

## Exact next activity — English Translation Batch 02

Process only:

`scenes/sru-03-eman-interview.md` → `translations/en/sru-03-eman-interview.md`

Requirements:

1. read the complete reviewed Tamil SRU;
2. draft English only from that SRU;
3. preserve speaker-label variation, tax/political satire, repetitions, wordplay, colloquial/source-period forms and structural order;
4. do not use a secondary English witness;
5. compare the complete English artifact back to the complete Tamil SRU;
6. set `translation_review: "passed"` only after full fidelity review;
7. create `translations/en/BATCH_02_REVIEW.md`;
8. update translation tracker / plan / handover only after Batch 02 passes.

Do not begin Batch 03 in the same step unless separately instructed after Batch 02 closure.

# CLOSED WORK SAFEGUARDS

`காகிதப்பூ` remains fully closed: Tamil 41/41, source-representation scenes 23/23, English 23/23, final reviews PASS. `மணிமகுடம்` and closed `கலைஞரின் நான்மணி மாலை` component works remain closed unless explicitly reopened.
