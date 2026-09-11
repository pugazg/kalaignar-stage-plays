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
