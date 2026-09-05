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
5. `works/thiruvalar-desiyampillai/PAGE_LAYER_COMPLETION_AUDIT.md`
6. `works/thiruvalar-desiyampillai/STRUCTURAL_SCENE_INVENTORY.md`
7. `works/thiruvalar-desiyampillai/ASSEMBLY_REVIEW.md`
8. `works/thiruvalar-desiyampillai/TRANSLATION_PLAN.md`
9. `works/thiruvalar-desiyampillai/translations/en/README.md`
10. the complete reviewed Tamil SRU(s) for the current translation batch
11. page records / controlling PDF only if a genuine source adjudication becomes necessary

## Source / Tamil archival checkpoint

Controlling PDF: `TVA_BOK_0064118_திருவாளர்_தேசீயம்பிள்ளை.pdf`.

- SHA-256: `b336bbebb326803badecbaa93de4ca4d63d80f68137fe70673b07a884c4910eb`
- physical scans: **49**
- page records/source processing: **49 / 49 complete**
- historical-glyph passes: **49 / 49 complete**
- visually verified: **40 / 49**
- `needs-review`: **9 / 49** (`1, 3, 4, 5, 7, 8, 9, 35, 36`)
- structural inventory: **PASS / REVIEWED — 7 editorial SRUs**
- Tamil source-representation assembly: **7 / 7 COMPLETE / REVIEWED — PASS**

The Tamil archival layer is closed for current source evidence. Translation choices must never retroactively alter it.

## Structural safeguards

The source contains **no numbered scenes or acts**. SRU labels are repository/editorial identifiers only.

Seven reviewed Tamil SRUs:

1. `scenes/sru-01-yama-court.md`
2. `scenes/sru-02-guesthouse.md`
3. `scenes/sru-03-eman-interview.md`
4. `scenes/sru-04-gandhi-journey.md`
5. `scenes/sru-05-stairfall-dream-exit.md`
6. `scenes/sru-06-domestic-election-argument.md`
7. `scenes/sru-07-udayasuriyan-kolam-close.md`

Source-loss controls that must survive any English translation:

- SRU-01: **7** exact `[paper loss]` markers;
- SRU-04: **1** exact `[unresolved glyph cluster]` marker;
- SRU-04: **2** exact `[unresolved descriptive cluster]` markers;
- scan-47 `உதயசூரியன் கோலம்`: internal descriptive/intertitle in SRU-07, not a source scene title;
- scan 48: no source `முற்றும்`; do not add `The End` or equivalent.

## English translation plan checkpoint

`works/thiruvalar-desiyampillai/TRANSLATION_PLAN.md` is **PLAN READY / REVIEWED**.

`works/thiruvalar-desiyampillai/translations/en/README.md` is the tracker.

Current authorization boundary:

**ENGLISH BODY TRANSLATION NOT YET AUTHORIZED / NOT STARTED.**

Current English metrics:

- expected artifacts: **7**
- present: **0 / 7**
- reviewed: **0 / 7**
- completed batches: **0 / 4**
- secondary-English witness use: **0**

Translation authority, once explicitly authorized:

- draft **only** from the reviewed Tamil SRUs;
- do not draft from OCR, the controlling PDF, another edition, web text, general knowledge or a secondary/published English witness;
- use `secondary_english_witness_used: false` throughout the independent first-pass English layer;
- page records/PDF may be consulted only for genuine source adjudication, not to bypass the Tamil assembly.

Required translation qualities:

- preserve complete SRU structure/order;
- preserve speaker-label variation, narrative prose and stage directions;
- preserve repetitions, satire, political rhetoric, social-reform/rationalist rhetoric and colloquial register;
- preserve proper names and supported ambiguity;
- do not silently modernize, euphemize, normalize or repair source wording;
- keep all loss/unresolved markers at their corresponding positions;
- do not invent source scene numbering or an end marker.

## Planned batches

### Batch 1

- `scenes/sru-01-yama-court.md` → `translations/en/sru-01-yama-court.md`
- `scenes/sru-02-guesthouse.md` → `translations/en/sru-02-guesthouse.md`

Special gate: all **7** SRU-01 `[paper loss]` markers must survive.

### Batch 2

- `scenes/sru-03-eman-interview.md` → `translations/en/sru-03-eman-interview.md`

### Batch 3

- `scenes/sru-04-gandhi-journey.md` → `translations/en/sru-04-gandhi-journey.md`

Special gate: preserve **1 + 2** unresolved markers exactly.

### Batch 4

- `scenes/sru-05-stairfall-dream-exit.md`
- `scenes/sru-06-domestic-election-argument.md`
- `scenes/sru-07-udayasuriyan-kolam-close.md`

Special gate: preserve the internal `உதயசூரியன் கோலம்` intertitle and do not invent `The End`.

Each batch must receive complete Tamil→English fidelity review and a durable `translations/en/BATCH_0N_REVIEW.md` before it is marked PASS / LOCKED. After all 7 artifacts pass, create `translations/en/TRANSLATION_REVIEW.md` for final closure.

## Exact next activity

**Wait for explicit English-translation authorization.**

If the user now says `proceed with next activity`, `continue`, or otherwise explicitly instructs continuation after this checkpoint, treat that as authorization to begin **English Translation Batch 1** under the plan above.

Do not reopen or change the Tamil archival layer while translating.

## Closed-work safeguards

`காகிதப்பூ` remains COMPLETE / CLOSED: Tamil 41/41, source-representation scenes 23/23, English 23/23, final reviews PASS. `மணிமகுடம்` and closed `கலைஞரின் நான்மணி மாலை` components remain closed unless explicitly reopened.
