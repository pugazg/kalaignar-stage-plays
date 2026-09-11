# Kalaignar Stage Plays — Handover

Repository: `pugazg/kalaignar-stage-plays`, branch `main`.

## Startup rule

Always fetch live `main` first and preserve newer durable state.

Permanent authorities:

1. `STAGE_PLAY_PROCESSING_GUIDE.md`;
2. `HISTORICAL_TAMIL_GLYPH_TRANSCRIPTION_GUIDE.md`;
3. `HISTORICAL_TAMIL_GLYPH_GATE.md`;
4. active work workflow `works/nachuk-koppai/BATCH_EXECUTION_WORKFLOW.md`.

# CURRENT CHECKPOINT — நச்சுக்கோப்பை / BATCH 03 H-GATE CHECKPOINT

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
- page records created: **30 / 63**;
- full canonical records: **30 / 63** (scans 1–30);
- partial records in Batch 01: **0**;
- user-supplied first-pass baseline: **ingested for scans 1–10** at `works/nachuk-koppai/first-pass/BATCH_01_USER_TRANSCRIPTION.md`;
- Batch 01 Pass A: **COMPLETE — 10 / 10 initial verification PASS**;
- H-GATE checked: **30 / 63**;
- H-GATE PASS: **5 / 63**;
- H-GATE needs-review: **25 / 63**;
- final verified pages: **5 / 63**;
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

1. proceed to **Batch 04 Pass A — scans 31–40** using the user-supplied transcription as comparison baseline and attached PDF as sole authority;
2. preserve all Batch 01–03 unresolved scans as durable holds and do not re-loop reduced renders;
3. write pages 0031–0040 and ordinary initial verification;
4. commit Batch 04 Pass A before its H-GATE;
5. SHA-256 remains a separate P0 fingerprint hold;
6. do not begin scene assembly or English translation.

## Closed work safeguards

All previously closed works remain closed unless separately authorized or genuinely stronger source evidence appears.
