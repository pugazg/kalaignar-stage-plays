# திருவாளர் தேசீயம்பிள்ளை — English translation

Status: **AUTHORIZED / IN PROGRESS — BATCHES 01–03 PASS / LOCKED; 4 / 7 SRUs TRANSLATED AND REVIEWED**

This directory is the independent source-faithful English translation layer for the seven reviewed Tamil source-representation units (SRUs) of **திருவாளர் தேசீயம்பிள்ளை**.

Translation plan: `../../TRANSLATION_PLAN.md`.

Tamil assembly review: `../../ASSEMBLY_REVIEW.md` — **PASS / REVIEWED**.

## Translation authority

Immediate drafting authority is the reviewed Tamil SRU layer under `../../scenes/` only.

Do not draft from OCR, the controlling PDF, another edition, web text, general knowledge, summaries or a secondary/published English witness. Page records/PDF may be consulted only for a genuine source adjudication and must not bypass the closed Tamil assembly.

Translation choices must not modify the Tamil archival layer.

## Expected English artifacts

The source has no numbered scenes or acts. English filenames mirror the seven editorial SRUs without claiming source scene numbering:

1. `sru-01-yama-court.md`
2. `sru-02-guesthouse.md`
3. `sru-03-eman-interview.md`
4. `sru-04-gandhi-journey.md`
5. `sru-05-stairfall-dream-exit.md`
6. `sru-06-domestic-election-argument.md`
7. `sru-07-udayasuriyan-kolam-close.md`

Current artifact status:

- expected: **7**;
- present: **4 / 7**;
- reviewed: **4 / 7**;
- translation batches complete: **3 / 4**;
- final translation review: **not started**;
- secondary-English witness used: **no**.

## Batch 01 — PASS / LOCKED

Durable review: `BATCH_01_REVIEW.md` — **PASS / LOCKED**.

Completed artifacts:

- `sru-01-yama-court.md` — **translation-reviewed / passed**; all **7 / 7** `[paper loss]` markers retained;
- `sru-02-guesthouse.md` — **translation-reviewed / passed**.

## Batch 02 — PASS / LOCKED

Durable review: `BATCH_02_REVIEW.md` — **PASS / LOCKED**.

Completed artifact:

- `sru-03-eman-interview.md` — **translation-reviewed / passed**.

Batch 02 preserves the repeated `pillai` sequence, `uyarthinai / ahrinai`, `pancha-varnam / pancham`, tax/Congress/election/Five-Year-Plan satire, source-label variation and the exact SRU boundary without secondary-English contamination.

## Batch 03 — PASS / LOCKED

Durable review: `BATCH_03_REVIEW.md` — **PASS / LOCKED**.

Completed artifact:

- `sru-04-gandhi-journey.md` — **translation-reviewed / passed**.

Batch 03 controls:

- scan-35 `[unresolved glyph cluster]`: **1 / 1 retained**;
- scan-36 `[unresolved descriptive cluster]`: **2 / 2 retained**;
- apparent scan-35 `கொழுப்பேறி`: **not promoted / not translated as resolved**;
- Nandan / Gandhi / `சொர்க்கச் சிறை` structure: **PASS**;
- priest/idol/Congress, military/assassination, possession, `Harijan Welfare`, and Srirangam/Ranganatha satire: **PASS**;
- source `போப்பந்தர்` retained as *Poppanthar*;
- source-sensitive `கோட்டான்`, `எங்குவேன்`, `நாகத்திலும்`, and `மகானத்துக்கு ஓர் “ஆயாக் கிழவி”` handled conservatively and documented;
- secondary-English witness use: **0**;
- Tamil archival changes caused by translation: **0**.

## Source-loss / unresolved-marker controls

- SRU-01 `[paper loss]`: **7 / 7 retained / reviewed**;
- SRU-04 `[unresolved glyph cluster]`: **1 / 1 retained / reviewed**;
- SRU-04 `[unresolved descriptive cluster]`: **2 / 2 retained / reviewed**;
- no missing wording reconstructed from context, grammar, repetition, another edition or an English witness.

## Structural safeguards

- SRU identifiers are editorial repository identifiers, not source scene numbers.
- Do not add `Scene 1`, `Scene 2`, act numbering or invented curtain directions.
- Scan-47 `உதயசூரியன் கோலம்` remains an internal descriptive/intertitle in the final SRU; its English rendering must stay internal rather than becoming a source scene title.
- Scan 48 has no printed `முற்றும்`; do not add `The End` or equivalent.
- Scan 49 back-cover advertising is outside the dramatic English layer.

## Translation review gate

Every English SRU must be compared in full against its complete reviewed Tamil SRU before it can use:

```yaml
status: "translation-reviewed"
translation_review: "passed"
secondary_english_witness_used: false
```

Each completed batch must have a durable `BATCH_0N_REVIEW.md` record. After all seven artifacts pass, create `TRANSLATION_REVIEW.md` for the final 7/7 review gate.

## Translation batches

- **Batch 1:** SRU-01 + SRU-02 — **PASS / LOCKED**
- **Batch 2:** SRU-03 — **PASS / LOCKED**
- **Batch 3:** SRU-04 — **PASS / LOCKED**
- **Batch 4:** SRU-05 + SRU-06 + SRU-07 — **NEXT**

## Exact next activity

Translate and fully review **Batch 04** from these reviewed Tamil SRUs only:

- `../../scenes/sru-05-stairfall-dream-exit.md` → `sru-05-stairfall-dream-exit.md`
- `../../scenes/sru-06-domestic-election-argument.md` → `sru-06-domestic-election-argument.md`
- `../../scenes/sru-07-udayasuriyan-kolam-close.md` → `sru-07-udayasuriyan-kolam-close.md`

Special gates:

- preserve the stair/place-name wordplay in SRU-05;
- preserve the domestic colloquial/election/political register in SRU-06;
- preserve `உதயசூரியன் கோலம்` as an internal intertitle in SRU-07, not a source scene heading;
- do not add `The End` or equivalent at the close;
- use no secondary English witness.

After all three artifacts receive complete Tamil→English review, create `BATCH_04_REVIEW.md`. Only after Batch 04 is PASS / LOCKED should final `TRANSLATION_REVIEW.md` be created.