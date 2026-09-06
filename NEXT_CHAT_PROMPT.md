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
10. `works/thiruvalar-desiyampillai/translations/en/BATCH_03_REVIEW.md`
11. complete reviewed Tamil `scenes/sru-05-stairfall-dream-exit.md`
12. complete reviewed Tamil `scenes/sru-06-domestic-election-argument.md`
13. complete reviewed Tamil `scenes/sru-07-udayasuriyan-kolam-close.md`
14. page records / controlling PDF only if a genuine source adjudication becomes necessary

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

Authoritative source-loss controls:

- SRU-01: **7** `[paper loss]` markers — preserved/reviewed in Batch 01;
- SRU-04: **1** `[unresolved glyph cluster]` + **2** `[unresolved descriptive cluster]` — preserved/reviewed in Batch 03;
- apparent scan-35 `கொழுப்பேறி` remains non-canonical;
- scan-47 `உதயசூரியன் கோலம்`: internal descriptive/intertitle in SRU-07;
- scan 48: no source `முற்றும்`; do not add `The End` or equivalent.

## English translation checkpoint

`TRANSLATION_PLAN.md`: **AUTHORIZED / IN PROGRESS**.

### Batch 01 — PASS / LOCKED

- `translations/en/sru-01-yama-court.md`
- `translations/en/sru-02-guesthouse.md`
- review: `translations/en/BATCH_01_REVIEW.md`
- `[paper loss]`: **7 / 7 retained**

### Batch 02 — PASS / LOCKED

- `translations/en/sru-03-eman-interview.md`
- review: `translations/en/BATCH_02_REVIEW.md`
- repeated `pillai`, `uyarthinai / ahrinai`, `pancha-varnam / pancham`, tax/Congress/election/Five-Year-Plan satire preserved/documented

### Batch 03 — PASS / LOCKED

- `translations/en/sru-04-gandhi-journey.md`
- review: `translations/en/BATCH_03_REVIEW.md`
- `[unresolved glyph cluster]`: **1 / 1 retained**
- `[unresolved descriptive cluster]`: **2 / 2 retained**
- apparent `கொழுப்பேறி`: not resolved in English
- `போப்பந்தர்`: retained as *Poppanthar*
- `Harijan Welfare`: retained as source-period terminology
- secondary-English witness use: **0**
- Tamil archival changes caused by translation: **0**

Current English metrics:

- expected artifacts: **7**
- present: **4 / 7**
- reviewed: **4 / 7**
- completed batches: **3 / 4**
- final `TRANSLATION_REVIEW.md`: **not started**

Translation authority remains strict:

- draft only from the reviewed Tamil SRUs for the current batch;
- do not draft from OCR, controlling PDF text, another edition, web text, general knowledge, or any secondary/published English witness;
- use `secondary_english_witness_used: false`;
- page records/PDF may be consulted only for genuine source adjudication, not to bypass Tamil assembly.

## Exact next activity — English Translation Batch 04

Translate and fully review only:

- `scenes/sru-05-stairfall-dream-exit.md` → `translations/en/sru-05-stairfall-dream-exit.md`
- `scenes/sru-06-domestic-election-argument.md` → `translations/en/sru-06-domestic-election-argument.md`
- `scenes/sru-07-udayasuriyan-kolam-close.md` → `translations/en/sru-07-udayasuriyan-kolam-close.md`

Required controls:

1. read all three complete reviewed Tamil SRUs first;
2. preserve the complete SRU order and boundaries;
3. preserve SRU-05 stair/place-name wordplay and the wake-from-dream transition;
4. preserve SRU-06 domestic colloquial register, election/political satire, source-form variation and repetitions;
5. preserve source scan-47 `உதயசூரியன் கோலம்` as a standalone **internal intertitle** within SRU-07, not a source scene heading;
6. preserve the final source close exactly in structural terms and do **not** add `The End`, `End`, `(Curtain)`, or equivalent;
7. do not invent scene or act numbering;
8. do not use a secondary English witness;
9. perform complete Tamil→English fidelity review for all three artifacts;
10. set `status: "translation-reviewed"` and `translation_review: "passed"` only after review;
11. create `translations/en/BATCH_04_REVIEW.md` and mark Batch 04 PASS / LOCKED only if all checks pass;
12. update tracker / plan / work/root README / handover after Batch 04 closure.

After Batch 04 is durably closed, stop. The next separate activity is the final **7 / 7 `translations/en/TRANSLATION_REVIEW.md`** gate; do not perform it until the user proceeds again.

## Closed-work safeguards

`காகிதப்பூ` remains COMPLETE / CLOSED: Tamil 41/41, source-representation scenes 23/23, English 23/23, final reviews PASS. `மணிமகுடம்` and closed `கலைஞரின் நான்மணி மாலை` components remain closed unless explicitly reopened.