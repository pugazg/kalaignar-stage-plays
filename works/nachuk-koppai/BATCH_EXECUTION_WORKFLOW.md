# நச்சுக்கோப்பை — Batch execution workflow

Status: **MANDATORY FOR ACTIVE PAGE BATCHES**

This work follows `STAGE_PLAY_PROCESSING_GUIDE.md`, `HISTORICAL_TAMIL_GLYPH_TRANSCRIPTION_GUIDE.md` and `HISTORICAL_TAMIL_GLYPH_GATE.md`.

## Controlling-source rule

- The exact supplied `ACL-TDD_00314_நச்சுக்_கோப்பை.pdf` is controlling.
- The PDF is not committed to Git.
- OCR / inferred wording / modern spelling / later editions are never controlling.
- Source-visible old glyphs and unusual wording remain unchanged unless the scan itself securely supports a different reading.

## Routine batch size

Default routine page batch: **10 physical scans**.

Do not silently enlarge a batch. The terminal batch may contain fewer than 10 scans.

## Hard two-commit workflow

For each routine batch:

1. **Pass A — whole pages once**
   - inspect each complete source scan;
   - create canonical page records;
   - preserve speaker labels, punctuation, stage directions, ornaments and physical page joins;
   - complete ordinary visual verification;
   - do not repeatedly restart settled transcription because one glyph is difficult.

2. **Durable Pass-A commit**
   - write each completed page as `needs-review`;
   - set `initial_verification: passed`;
   - set `historical_glyph_gate: pending`;
   - synchronize the page map / progress controls.

3. **Pass B — targeted independent H-GATE**
   - check mandatory historical-glyph families and actual candidate loci;
   - check source-sensitive physical joins;
   - do not retranscribe settled prose from scratch.

4. **Crop only genuine uncertainty**
   - create enhancement/crop only if the source reading is genuinely unresolved;
   - stop once the locus is resolved or formally retained as `needs-review`.

5. **Final closure commit**
   - promote clean pages to `verified`;
   - record corrections / holds;
   - create `BATCH_nn_REVIEW.md`;
   - synchronize page map, work README, root README, handover and next-chat prompt.

Short rule:

> **Controlling PDF → Pass A once → durable commit → targeted H-GATE → final commit. No settled-text loop.**


# Word-by-word visual text fidelity phase

Status: **ACTIVE / USER-DIRECTED**

This phase begins after canonical page coverage and H-GATE coverage. It is a fresh, exhaustive source-fidelity pass and supersedes the previously planned immediate 63-page state reconciliation.

## Iteration size

**Exactly 5 physical scans per iteration**, except the final remainder.

Do not enlarge the batch.

## Required method

For each of the five scans:

1. inspect the attached controlling page visually;
2. compare **every visible publication-text token in reading order** against the canonical page record;
3. include headings, speaker labels, stage directions, numerals, Latin-script tokens, punctuation and printed page numbers;
4. mechanical line-wrap joining is permitted only when it does not change token identity;
5. separately verify that library/accession/presentation marks are not silently merged into authorial/publication text;
6. do not use OCR, context, grammar, familiar spelling, TDL, Wikisource or another edition as authority;
7. when the scan clearly proves a mismatch, correct the canonical text and record the exact before → after change;
8. when any word/glyph remains visually uncertain, retain the current reading and mark the fidelity result `needs-review`;
9. do not reopen unrelated older holds outside the current five-page iteration;
10. commit immediately after each five-page fidelity batch.

## Page metadata

Use:

`visual_text_fidelity: "passed"`

or

`visual_text_fidelity: "needs-review"`.

This phase is independent of H-GATE. A page is clean for downstream reconciliation only when its visual-text-fidelity state and historical-glyph/source state are both explicitly known.

Short rule:

> **5 scans → every word visually compared → source-proven corrections only → commit → next 5 scans.**
