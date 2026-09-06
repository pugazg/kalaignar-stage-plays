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
8. all four batch reviews `BATCH_01_REVIEW.md` through `BATCH_04_REVIEW.md`
9. all seven reviewed English `translations/en/sru-*.md` artifacts
10. reviewed Tamil SRUs only if needed to verify a specific cross-artifact boundary/control
11. page records / controlling PDF only if a genuine Tamil-source adjudication becomes necessary

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

Authoritative source-condition controls:

- SRU-01 Tamil: **7** `[paper loss]` markers;
- SRU-04 Tamil: **1** `[unresolved glyph cluster]` + **2** `[unresolved descriptive cluster]` markers;
- apparent scan-35 `கொழுப்பேறி` remains non-canonical;
- scan-47 `உதயசூரியன் கோலம்`: internal descriptive/intertitle in SRU-07;
- scan 48: no source `முற்றும்`.

## English translation checkpoint — ALL BATCHES COMPLETE

### Batch 01 — PASS / LOCKED

- `translations/en/sru-01-yama-court.md`
- `translations/en/sru-02-guesthouse.md`
- `translations/en/BATCH_01_REVIEW.md`
- SRU-01 `[paper loss]`: **7 / 7 retained**

### Batch 02 — PASS / LOCKED

- `translations/en/sru-03-eman-interview.md`
- `translations/en/BATCH_02_REVIEW.md`

### Batch 03 — PASS / LOCKED

- `translations/en/sru-04-gandhi-journey.md`
- `translations/en/BATCH_03_REVIEW.md`
- `[unresolved glyph cluster]`: **1 / 1 retained**
- `[unresolved descriptive cluster]`: **2 / 2 retained**

### Batch 04 — PASS / LOCKED

- `translations/en/sru-05-stairfall-dream-exit.md`
- `translations/en/sru-06-domestic-election-argument.md`
- `translations/en/sru-07-udayasuriyan-kolam-close.md`
- `translations/en/BATCH_04_REVIEW.md`

Batch-04 controls passed:

- SRU-05 place-name / `படி` wordplay preserved/documented;
- SRU-05 source person-shift retained/documented;
- SRU-06 domestic colloquial/election/language-politics register preserved;
- source `நம்ப` handled contextually without changing Tamil;
- SRU-07 `உதயசூரியன் கோலம்` preserved internally as `Rising Sun Kolam`;
- invented source scene/act numbering: **0**;
- invented `The End`: **0**;
- secondary-English witness use: **0**.

Current English metrics:

- expected artifacts: **7**
- present: **7 / 7**
- individually reviewed: **7 / 7**
- completed batches: **4 / 4**
- batch reviews: **4 / 4 PASS / LOCKED**
- secondary-English witness use: **0**
- final `TRANSLATION_REVIEW.md`: **pending / not yet created**

## Exact next activity — final 7 / 7 translation closure review

Create:

`works/thiruvalar-desiyampillai/translations/en/TRANSLATION_REVIEW.md`

Perform the final cross-artifact review of all seven English SRUs and all four batch reviews.

Required checks:

1. English artifacts present: **7 / 7**;
2. all seven use `status: "translation-reviewed"` and `translation_review: "passed"`;
3. all seven use `secondary_english_witness_used: false`;
4. batch reviews PASS / LOCKED: **4 / 4**;
5. English SRU order/boundaries mirror the reviewed Tamil layer;
6. source scene/act numbering invented: **0**;
7. SRU-01 `[paper loss]`: **7 / 7 retained**;
8. SRU-04 `[unresolved glyph cluster]`: **1 / 1 retained**;
9. SRU-04 `[unresolved descriptive cluster]`: **2 / 2 retained**;
10. apparent scan-35 `கொழுப்பேறி` remains unresolved / absent as resolved English wording;
11. `Rising Sun Kolam` remains an internal intertitle in SRU-07;
12. invented `The End` / curtain cue: **0**;
13. scan 49 advertising absent from dramatic English layer;
14. Tamil archival files changed because of translation choices: **0**.

If and only if all checks pass, mark the independent first-pass English layer **COMPLETE / CLOSED**, synchronize tracker / plan / work README / root README / `HANDOVER.md` / this prompt, and record the final live `main` SHA.

Do not start any secondary-English-witness comparison or reopen the nine Tamil source review holds unless separately authorized.

## Closed-work safeguards

`காகிதப்பூ` remains COMPLETE / CLOSED: Tamil 41/41, source-representation scenes 23/23, English 23/23, final reviews PASS. `மணிமகுடம்` and closed `கலைஞரின் நான்மணி மாலை` components remain closed unless explicitly reopened.
