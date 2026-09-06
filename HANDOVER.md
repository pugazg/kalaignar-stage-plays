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
10. completed English batch reviews `BATCH_01_REVIEW.md`, `BATCH_02_REVIEW.md`, `BATCH_03_REVIEW.md`;
11. complete reviewed Tamil SRUs `scenes/sru-05-stairfall-dream-exit.md`, `scenes/sru-06-domestic-election-argument.md`, and `scenes/sru-07-udayasuriyan-kolam-close.md` for the next batch;
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

Review holds remain authoritative:

- front matter `1, 3, 4, 5` — physical loss/abrasion;
- body `7, 8, 9` — `[paper loss]` gaps;
- scan `35` — one `[unresolved glyph cluster]`;
- scan `36` — two `[unresolved descriptive cluster]` markers.

Do not fill these from context, OCR, another edition, English translation, or lexical expectation.

`STRUCTURAL_SCENE_INVENTORY.md`: **PASS / REVIEWED**. The source has no numbered scenes/acts; seven editorial SRUs preserve source order. Scan-47 `உதயசூரியன் கோலம்` is an internal descriptive/intertitle; scan 48 has no source `முற்றும்`.

`ASSEMBLY_REVIEW.md`: **PASS / REVIEWED**. Tamil source-representation assembly is **7 / 7 COMPLETE / REVIEWED** and closed against translation-driven edits.

## English translation — AUTHORIZED / IN PROGRESS

Translation plan: `works/thiruvalar-desiyampillai/TRANSLATION_PLAN.md`.

Tracker: `works/thiruvalar-desiyampillai/translations/en/README.md`.

Immediate drafting authority: **reviewed Tamil SRUs only**. Do not draft from OCR, PDF text, another edition, web text, general knowledge, or a secondary English witness.

Expected English artifacts: **7** across four batches.

### Batch 01 — PASS / LOCKED

- `translations/en/sru-01-yama-court.md` — reviewed; `[paper loss]` **7 / 7 retained**;
- `translations/en/sru-02-guesthouse.md` — reviewed;
- durable review: `translations/en/BATCH_01_REVIEW.md`.

### Batch 02 — PASS / LOCKED

- `translations/en/sru-03-eman-interview.md` — reviewed;
- repeated `pillai`, `uyarthinai / ahrinai`, `pancha-varnam / pancham`, tax/Congress/election/Five-Year-Plan satire and source-label variation preserved/documented;
- durable review: `translations/en/BATCH_02_REVIEW.md`.

### Batch 03 — PASS / LOCKED

- `translations/en/sru-04-gandhi-journey.md` — **translation-reviewed / passed**;
- durable review: `translations/en/BATCH_03_REVIEW.md`;
- scan-35 `[unresolved glyph cluster]`: **1 / 1 retained**;
- scan-36 `[unresolved descriptive cluster]`: **2 / 2 retained**;
- apparent scan-35 `கொழுப்பேறி`: **not promoted / not resolved**;
- source `போப்பந்தர்`: retained as *Poppanthar*;
- `Harijan Welfare`: retained as source-period terminology;
- source-sensitive *kottaan*, `எங்குவேன்`, `நாகத்திலும்`, and `மகானத்துக்கு ஓர் “ஆயாக் கிழவி”` handled conservatively and documented;
- exact SRU end at the buffalo push before SRU-05: **PASS**;
- secondary-English witness use: **0**;
- blocking issues: **0**.

Current English metrics:

- expected artifacts: **7**;
- present: **4 / 7**;
- reviewed: **4 / 7**;
- completed batches: **3 / 4**;
- secondary-English witness use: **0**;
- final `TRANSLATION_REVIEW.md`: **not started**.

## Exact next activity — English Translation Batch 04

Process only:

- `scenes/sru-05-stairfall-dream-exit.md` → `translations/en/sru-05-stairfall-dream-exit.md`
- `scenes/sru-06-domestic-election-argument.md` → `translations/en/sru-06-domestic-election-argument.md`
- `scenes/sru-07-udayasuriyan-kolam-close.md` → `translations/en/sru-07-udayasuriyan-kolam-close.md`

Requirements:

1. read each complete reviewed Tamil SRU before drafting;
2. draft English only from those SRUs;
3. preserve SRU-05 stair/place-name wordplay and dream-exit structure;
4. preserve SRU-06 domestic colloquial/election/political register and source-form variation;
5. preserve scan-47 `உதயசூரியன் கோலம்` as an internal standalone intertitle inside SRU-07, not a source scene title;
6. do not add `The End` or any equivalent because scan 48 has no source `முற்றும்`;
7. do not use a secondary English witness;
8. compare each complete English artifact against its complete Tamil SRU;
9. set `translation_review: "passed"` only after full fidelity review;
10. create `translations/en/BATCH_04_REVIEW.md` only after all three pass.

After Batch 04 is PASS / LOCKED, the next separate activity is the final **7 / 7 `TRANSLATION_REVIEW.md`** closure gate. Do not perform that final gate in the same step unless the user proceeds again.

# CLOSED WORK SAFEGUARDS

`காகிதப்பூ` remains fully closed: Tamil 41/41, source-representation scenes 23/23, English 23/23, final reviews PASS. `மணிமகுடம்` and closed `கலைஞரின் நான்மணி மாலை` component works remain closed unless explicitly reopened.