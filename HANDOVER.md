# Kalaignar Stage Plays — Handover

Repository: `pugazg/kalaignar-stage-plays`, branch `main`.

## Startup rule

Always fetch live `main` first and preserve newer durable state.

Permanent authorities:

1. `STAGE_PLAY_PROCESSING_GUIDE.md`;
2. `HISTORICAL_TAMIL_GLYPH_TRANSCRIPTION_GUIDE.md`;
3. `HISTORICAL_TAMIL_GLYPH_GATE.md`;
4. active work workflow `works/nachuk-koppai/BATCH_EXECUTION_WORKFLOW.md`.

# CURRENT CHECKPOINT — நச்சுக்கோப்பை / BATCH 01 SOURCE INSPECTION

Active work: `works/nachuk-koppai/`.

Controlling source: `ACL-TDD_00314_நச்சுக்_கோப்பை.pdf`.

Current durable state:

- physical scans: **63 confirmed**;
- file size: **18,459,068 bytes**;
- conversation file id: `file_000000007a78820885b161bf144d9bd9`;
- SHA-256: **PENDING** — sole P0 byte-fingerprint hold;
- source type: **image-only / no usable parsed text layer**;
- title: **நச்சுக்கோப்பை**;
- author: **மு. கருணாநிதி**;
- publisher: **திராவிடன் பதிப்பகம்**;
- edition: **முதல் பதிப்பு — 1951**;
- preliminary numbered scenes: **18**;
- scan 63: **முற்றும்**;
- page records created: **10 / 63**;
- full canonical records: **1 / 63** (scan 1);
- partial records: **9 / 63** (scans 2–10);
- Batch 01 Pass A: **IN PROGRESS / NOT COMPLETE**;
- H-GATE: **0 / 63**;
- final verified pages: **0 / 63**;
- scene assembly: **not started**;
- English translation: **not started**.

## Batch 01 durable findings

- scans 1–10 were directly inspected from the controlling attachment;
- scan 1 cover transcription is source-secure and ordinary visual verification PASS;
- scans 2–10 have conservative partial records only; no uncertain body wording was guessed;
- dramatic printed pagination: scan 5=p.1, 6=p.2, 7=p.3, 8=p.4, 9=p.5, 10=p.6;
- structural correction: **scan 8 contains the close of Scene 1 and the opening of Scene 2**;
- `BATCH_01_SOURCE_INSPECTION.md` records this partial checkpoint.

## Exact next activity

1. compute SHA-256 from the exact attached bytes when checksum execution is available;
2. re-read scans **2–10** at full/native resolution and replace placeholders with complete source-faithful text;
3. declare Batch 01 Pass A complete only when all 10 page records are canonical and ordinary visual verification passes;
4. run targeted independent H-GATE for scans 1–10;
5. create `BATCH_01_REVIEW.md` only if the full batch passes;
6. do not begin scene assembly or English translation.

## Closed work safeguards

All previously closed works remain closed unless separately authorized or genuinely stronger source evidence appears.
