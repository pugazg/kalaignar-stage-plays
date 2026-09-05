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
9. complete reviewed Tamil `works/thiruvalar-desiyampillai/scenes/sru-03-eman-interview.md`
10. page records / controlling PDF only if a genuine source adjudication becomes necessary

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

- SRU-01: **7** exact `[paper loss]` markers;
- SRU-04: **1** `[unresolved glyph cluster]` + **2** `[unresolved descriptive cluster]` markers;
- scan-47 `உதயசூரியன் கோலம்`: internal descriptive/intertitle in SRU-07;
- scan 48: no source `முற்றும்`; do not add `The End` or equivalent.

## English translation checkpoint

`TRANSLATION_PLAN.md`: **AUTHORIZED / IN PROGRESS**.

`translations/en/README.md`: current tracker.

### Batch 01 — PASS / LOCKED

Durable review: `translations/en/BATCH_01_REVIEW.md`.

Completed / fully reviewed:

- `translations/en/sru-01-yama-court.md`
- `translations/en/sru-02-guesthouse.md`

Batch 01 controls passed:

- SRU-01 `[paper loss]`: **7 / 7 retained**;
- full Tamil→English comparison: **2 / 2 artifacts**;
- secondary-English witness use: **0**;
- invented source scene/act numbering: **0**;
- Tamil archival changes caused by translation: **0**.

Current English metrics:

- expected artifacts: **7**
- present: **2 / 7**
- reviewed: **2 / 7**
- completed batches: **1 / 4**
- final `TRANSLATION_REVIEW.md`: **not started**

Translation authority remains strict:

- draft only from the reviewed Tamil SRU for the current batch;
- do not draft from OCR, controlling PDF text, another edition, web text, general knowledge, or any secondary/published English witness;
- use `secondary_english_witness_used: false`;
- page records/PDF may be consulted only for genuine source adjudication, not to bypass Tamil assembly.

## Exact next activity — English Translation Batch 02

Translate and fully review only:

`scenes/sru-03-eman-interview.md` → `translations/en/sru-03-eman-interview.md`

Required controls:

1. read the complete Tamil SRU first;
2. preserve the full Eman/Desiyampillai interview structure and order;
3. preserve speaker-label variation, tax/election/political satire, repetitions, jokes, wordplay, colloquial/source-period forms and proper names;
4. do not invent scene numbering or editorial structure;
5. do not use a secondary English witness;
6. perform a complete Tamil→English fidelity review after drafting;
7. set `status: "translation-reviewed"` and `translation_review: "passed"` only after that review;
8. create `translations/en/BATCH_02_REVIEW.md` and mark Batch 02 PASS / LOCKED only if all checks pass;
9. then update tracker / plan / handover to Batch 03.

Do not begin Batch 03 until Batch 02 has been durably closed and the user proceeds again.

## Closed-work safeguards

`காகிதப்பூ` remains COMPLETE / CLOSED: Tamil 41/41, source-representation scenes 23/23, English 23/23, final reviews PASS. `மணிமகுடம்` and closed `கலைஞரின் நான்மணி மாலை` components remain closed unless explicitly reopened.
