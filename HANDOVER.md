# Kalaignar Stage Plays — Handover

Repository: `pugazg/kalaignar-stage-plays`, branch `main`.

## Startup rule

Always fetch live `main` first and preserve newer durable state.

Permanent authorities:

1. `STAGE_PLAY_PROCESSING_GUIDE.md`;
2. `HISTORICAL_TAMIL_GLYPH_TRANSCRIPTION_GUIDE.md`;
3. `HISTORICAL_TAMIL_GLYPH_GATE.md`;
4. active work workflow `works/nachuk-koppai/BATCH_EXECUTION_WORKFLOW.md`.

# CURRENT CHECKPOINT — நச்சுக்கோப்பை / PAGE-LAYER H-GATE COMPLETE / RECONCILIATION NEXT

Active work: `works/nachuk-koppai/`.

Controlling source: `ACL-TDD_00314_நச்சுக்_கோப்பை.pdf`.

Current durable state:

- physical scans: **63 confirmed**;
- file size: **18,459,068 bytes**;
- conversation file id: `file_000000007a78820885b161bf144d9bd9`;
- SHA-256: **PENDING** — sole P0 byte-fingerprint hold;
- source type: **image-only / no usable parsed text layer**;
- provenance: **attached PDF downloaded from Tamil Digital Library; Wikisource carries the same scan/copy**;
- witness rule: **attached PDF only is controlling; TDL/Wikisource are same-copy transport routes, not secondary witnesses**;
- title: **நச்சுக்கோப்பை**;
- author: **மு. கருணாநிதி**;
- publisher: **திராவிடன் பதிப்பகம்**;
- edition: **முதல் பதிப்பு — 1951**;
- preliminary numbered scenes: **18**;
- scan 63: **முற்றும்**;
- page records created: **63 / 63 — COMPLETE**;
- full canonical records: **63 / 63 — COMPLETE**;
- partial records in Batch 01: **0**;
- user-supplied first-pass baseline: **ingested for scans 1–10** at `works/nachuk-koppai/first-pass/BATCH_01_USER_TRANSCRIPTION.md`;
- Batch 01 Pass A: **COMPLETE — 10 / 10 initial verification PASS**;
- H-GATE checked: **63 / 63 — COMPLETE**;
- H-GATE PASS: **6 / 63**;
- H-GATE needs-review: **57 / 63**;
- final verified pages: **6 / 63**;
- Batch 07 Pass A: **COMPLETE — scans 61–63**;
- Batch 07 H-GATE: **CHECKED — 1 PASS / 2 needs-review; scan 63 verified**;
- Batch 06 Pass A: **COMPLETE — scans 51–60**;
- Batch 06 H-GATE: **CHECKED — 0 PASS / 10 needs-review**;
- Batch 05 Pass A: **COMPLETE — scans 41–50**;
- Batch 05 H-GATE: **CHECKED — 0 PASS / 10 needs-review**;
- Batch 04 Pass A: **COMPLETE — scans 31–40**;
- Batch 04 H-GATE: **CHECKED — 0 PASS / 10 needs-review**;
- Batch 03 Pass A: **COMPLETE — scans 21–30**;
- Batch 03 H-GATE: **CHECKED — 0 PASS / 10 needs-review**;
- Batch 02 Pass A: **COMPLETE — scans 11–20**;
- Batch 02 H-GATE: **CHECKED — 1 PASS / 9 needs-review**;
- scene assembly: **not started**;
- English translation: **not started**.

## Batch 01 durable findings

- scans 1–10 were directly inspected from the controlling attachment;
- scan 1 cover transcription is source-secure and ordinary visual verification PASS;
- scans 2–10 have conservative partial records only; no uncertain body wording was guessed;
- dramatic printed pagination: scan 5=p.1, 6=p.2, 7=p.3, 8=p.4, 9=p.5, 10=p.6;
- structural correction: **scan 8 contains the close of Scene 1 and the opening of Scene 2**;
- `BATCH_01_SOURCE_INSPECTION.md` records this partial checkpoint;
- the user has now supplied a first-pass transcription, so the next step is **comparison repair**, not retranscription from scratch.

## Exact next activity

1. perform a **full 63-page page-state reconciliation**;
2. enumerate all **57** hold-bearing pages and classify each hold as genuine unresolved textual/glyph ambiguity vs source-preserved unusual-but-readable wording/formatting;
3. do **not** change Tamil text during reconciliation;
4. decide, under repository policy, whether each hold remains `needs-review` or receives a terminal source-condition disposition;
5. synchronize page map, audit, README, handover and next prompt;
6. only after reconciliation may scene assembly be considered;
7. SHA-256 remains a separate P0 fingerprint hold;
8. do not begin English translation.

## Closed work safeguards

All previously closed works remain closed unless separately authorized or genuinely stronger source evidence appears.
