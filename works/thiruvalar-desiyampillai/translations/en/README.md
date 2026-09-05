# திருவாளர் தேசீயம்பிள்ளை — English translation

Status: **AUTHORIZED / IN PROGRESS — BATCH 01 PASS / LOCKED; 2 / 7 SRUs TRANSLATED AND REVIEWED**

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
- present: **2 / 7**;
- reviewed: **2 / 7**;
- translation batches complete: **1 / 4**;
- final translation review: **not started**;
- secondary-English witness used: **no**.

## Batch 01 — PASS / LOCKED

Durable review: `BATCH_01_REVIEW.md` — **PASS / LOCKED**.

Completed artifacts:

- `sru-01-yama-court.md` — **translation-reviewed / passed**; all **7 / 7** `[paper loss]` markers retained;
- `sru-02-guesthouse.md` — **translation-reviewed / passed**.

Batch 01 review confirms complete Tamil→English comparison for both SRUs, source-order/boundary fidelity, no invented scene numbering, no secondary-English witness, and no translation-driven change to the Tamil layer.

## Source-loss / unresolved-marker controls

Mandatory controls across the English phase:

- SRU-01 preserves all **7** exact `[paper loss]` markers — **complete / reviewed**;
- SRU-04 must preserve the exact scan-35 `[unresolved glyph cluster]` marker;
- SRU-04 must preserve both exact scan-36 `[unresolved descriptive cluster]` markers;
- no missing wording may be reconstructed from context, grammar, repetition, another edition or an English witness.

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
- **Batch 2:** SRU-03 — **NEXT**
- **Batch 3:** SRU-04
- **Batch 4:** SRU-05 + SRU-06 + SRU-07

## Exact next activity

Translate and fully review **Batch 02** from reviewed Tamil `../../scenes/sru-03-eman-interview.md` only:

- `../../scenes/sru-03-eman-interview.md` → `sru-03-eman-interview.md`

Then create `BATCH_02_REVIEW.md`, update this tracker, and only then proceed to Batch 03.
