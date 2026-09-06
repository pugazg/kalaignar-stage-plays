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
5. `works/thiruvalar-desiyampillai/ASSEMBLY_REVIEW.md`
6. `works/thiruvalar-desiyampillai/TRANSLATION_PLAN.md`
7. `works/thiruvalar-desiyampillai/translations/en/README.md`
8. `works/thiruvalar-desiyampillai/translations/en/BATCH_01_REVIEW.md`
9. `works/thiruvalar-desiyampillai/translations/en/BATCH_02_REVIEW.md`
10. complete reviewed Tamil `works/thiruvalar-desiyampillai/scenes/sru-04-gandhi-journey.md`
11. page records / controlling PDF only if a genuine source adjudication becomes necessary

## Tamil archival checkpoint

Controlling PDF: `TVA_BOK_0064118_திருவாளர்_தேசீயம்பிள்ளை.pdf`.

- SHA-256: `b336bbebb326803badecbaa93de4ca4d63d80f68137fe70673b07a884c4910eb`
- physical scans: **49**
- page/source processing: **49 / 49 complete**
- historical-glyph passes: **49 / 49 complete**
- visually verified: **40 / 49**
- `needs-review`: **9 / 49** (`1, 3, 4, 5, 7, 8, 9, 35, 36`)
- structural inventory: **PASS / REVIEWED — 7 editorial SRUs**
- Tamil source-representation assembly: **7 / 7 COMPLETE / REVIEWED — PASS**

The Tamil archival layer is closed for current source evidence. Translation choices must never retroactively alter it.

Source-loss controls that remain authoritative:

- SRU-01: **7** exact `[paper loss]` markers — already preserved in English Batch 01;
- SRU-04: **1** exact `[unresolved glyph cluster]` marker;
- SRU-04: **2** exact `[unresolved descriptive cluster]` markers;
- apparent scan-35 `கொழுப்பேறி` remains non-canonical and must not be translated as resolved;
- scan-47 `உதயசூரியன் கோலம்`: internal descriptive/intertitle in SRU-07;
- scan 48: no source `முற்றும்`; do not add `The End` or equivalent.

## English translation checkpoint

`TRANSLATION_PLAN.md`: **AUTHORIZED / IN PROGRESS**.

`translations/en/README.md`: current tracker.

### Batch 01 — PASS / LOCKED

- `translations/en/sru-01-yama-court.md`
- `translations/en/sru-02-guesthouse.md`
- durable review: `translations/en/BATCH_01_REVIEW.md`
- SRU-01 `[paper loss]`: **7 / 7 retained**

### Batch 02 — PASS / LOCKED

- `translations/en/sru-03-eman-interview.md`
- durable review: `translations/en/BATCH_02_REVIEW.md`

Batch 02 controls passed:

- complete Tamil→English comparison: **1 / 1 artifact**;
- speaker-label variation kept traceable (`Desiyam Pillai :` / `Desi :` / `Yama :`);
- repeated `pillai` wordplay preserved/documented;
- `uyarthinai / ahrinai` and `pancha-varnam / pancham` retained for wordplay;
- tax / Congress / election / Five-Year-Plan satire: **PASS**;
- secondary-English witness use: **0**;
- invented source scene/act numbering: **0**;
- Tamil archival changes caused by translation: **0**.

Current English metrics:

- expected artifacts: **7**
- present: **3 / 7**
- reviewed: **3 / 7**
- completed batches: **2 / 4**
- final `TRANSLATION_REVIEW.md`: **not started**

Translation authority remains strict:

- draft only from the reviewed Tamil SRU for the current batch;
- do not draft from OCR, controlling PDF text, another edition, web text, general knowledge, or any secondary/published English witness;
- use `secondary_english_witness_used: false`;
- page records/PDF may be consulted only for genuine source adjudication, not to bypass Tamil assembly.

## Exact next activity — English Translation Batch 03

Translate and fully review only:

`scenes/sru-04-gandhi-journey.md` → `translations/en/sru-04-gandhi-journey.md`

Required controls:

1. read the complete reviewed Tamil SRU first;
2. preserve the full journey / Nandan / Gandhi / `சொர்க்கச் சிறை` structure and order;
3. preserve exactly **1** `[unresolved glyph cluster]` at the scan-35 location;
4. preserve exactly **2** `[unresolved descriptive cluster]` markers at the scan-36 locations;
5. do not infer or translate the apparent non-canonical `கொழுப்பேறி` reading;
6. preserve political satire, historical terminology, repetitions, colloquial/source-period forms, proper names and supported ambiguity;
7. do not invent scene numbering or editorial structure;
8. do not use a secondary English witness;
9. perform a complete Tamil→English fidelity review after drafting;
10. set `status: "translation-reviewed"` and `translation_review: "passed"` only after review;
11. create `translations/en/BATCH_03_REVIEW.md` and mark Batch 03 PASS / LOCKED only if all checks pass;
12. then update tracker / plan / handover to Batch 04.

Do not begin Batch 04 until Batch 03 has been durably closed and the user proceeds again.

## Closed-work safeguards

`காகிதப்பூ` remains COMPLETE / CLOSED: Tamil 41/41, source-representation scenes 23/23, English 23/23, final reviews PASS. `மணிமகுடம்` and closed `கலைஞரின் நான்மணி மாலை` components remain closed unless explicitly reopened.