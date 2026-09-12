# Kalaignar Stage Plays — Handover

Repository: `pugazg/kalaignar-stage-plays`, branch `main`.

## Startup rule

Always fetch live `main` first and preserve newer durable state.

Permanent authorities:

1. `STAGE_PLAY_PROCESSING_GUIDE.md`;
2. `HISTORICAL_TAMIL_GLYPH_TRANSCRIPTION_GUIDE.md`;
3. `HISTORICAL_TAMIL_GLYPH_GATE.md`;
4. active work workflow `works/nachuk-koppai/BATCH_EXECUTION_WORKFLOW.md`.

# CURRENT CHECKPOINT — நச்சுக்கோப்பை / TAMIL SCENE LAYER CLOSED / ENGLISH TRANSLATION NEXT

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
- page-record files present: **63 / 63**;
- source-aligned records fidelity-confirmed: **63 / 63 — COMPLETE**;
- partial records in Batch 01: **0**;
- user-supplied first-pass baseline: **ingested for scans 1–10** at `works/nachuk-koppai/first-pass/BATCH_01_USER_TRANSCRIPTION.md`;
- Batch 01 Pass A: **COMPLETE — 10 / 10 initial verification PASS**;
- H-GATE checked: **63 / 63 — COMPLETE**;
- H-GATE PASS: **62 / 63**;
- H-GATE needs-review: **1 / 63 — terminal source-condition hold on scan 22**;
- final verified pages: **62 / 63**;
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
- visual text fidelity audit: **ACTIVE — 5 scans per iteration**;
- fidelity coverage: **63 / 63 scans — COMPLETE**;
- fidelity PASS: **62 — scans 1–21, 23–63**;
- fidelity terminal source-condition hold: **1 — scan 22 (two adjacent unidentified source clusters after `சாந்தா`)**;
- fidelity source-proven / user-confirmed correction loci: **281**;
- Fidelity Batch 05: **COMPLETE — 4 PASS / 1 needs-review**;
- Fidelity Batch 06: **COMPLETE — 5 PASS / 0 needs-review**;
- Fidelity Batch 07: **COMPLETE — 4 PASS / 1 needs-review; 24 textual repairs + 5 physical-page realignments**;
- Fidelity Batch 08: **COMPLETE — 5 PASS / 0 needs-review; 28 textual repairs + 5 physical-page realignments**;
- Fidelity Batch 09: **COMPLETE — 5 PASS / 0 needs-review; 27 textual repairs + 5 physical-page realignments**;
- Fidelity Batch 10: **COMPLETE — 5 PASS / 0 needs-review; 26 textual repairs + 5 physical-page realignments**;
- Fidelity Batch 11: **COMPLETE — 5 PASS / 0 needs-review; 29 textual repairs + 5 physical-page realignments**;
- Fidelity Batch 12: **COMPLETE — 5 PASS / 0 needs-review; 35 textual repairs + 5 physical-page realignments**;
- Fidelity Batch 13: **COMPLETE — 3 PASS / 0 needs-review; 10 textual repairs + 3 final physical-page/closure reconciliations**;
- structural finding: **records 31–63 have now been rebuilt/re-anchored source-first; scan 63 is the source-proven combined final dialogue / literary close / imprint page**;
- full page-state reconciliation: **COMPLETE — 63 / 63; 62 verified + 1 terminal source-condition hold**;
- scan 35 user-confirmed source reading: **`சுடகோடி` — VERIFIED**;
- scan 22 user interpretation: likely a song/performance cue, recorded as interpretation only; unidentified marks remain unresolved textually;
- scene assembly: **18 / 18 assembled / reviewed — COMPLETE; 17 clean + Scene 5 carrying inherited scan-22 hold**;
- final scene consistency audit: **PASS / COMPLETE**;
- Tamil scene layer: **CLOSED FOR CURRENT SOURCE EVIDENCE**;
- English translation: **not started — NEXT**.

## Batch 01 durable findings

- scans 1–10 were directly inspected from the controlling attachment;
- scan 1 cover transcription is source-secure and ordinary visual verification PASS;
- scans 2–10 have conservative partial records only; no uncertain body wording was guessed;
- dramatic printed pagination: scan 5=p.1, 6=p.2, 7=p.3, 8=p.4, 9=p.5, 10=p.6;
- structural correction: **scan 8 contains the close of Scene 1 and the opening of Scene 2**;
- `BATCH_01_SOURCE_INSPECTION.md` records this partial checkpoint;
- the user has now supplied a first-pass transcription, so the next step is **comparison repair**, not retranscription from scratch.

## Exact next activity

1. begin the **English translation phase** from the closed Tamil scene layer;
2. first read / follow the repository's existing English-translation conventions from already closed stage-play works before creating new translation artifacts;
3. translate **Scenes 1–5** as the first English batch unless a live repository translation workflow specifies a different batch size;
4. translate from the assembled Tamil scene files, not from OCR or a new source transcription;
5. preserve names, speaker structure, stage directions, rhetorical force and source-sensitive wording without silently smoothing away meaning;
6. Scene 5 must preserve the scan-22 uncertainty explicitly: do not translate or invent the unreadable source clusters; retain the performance-interpretation note separately;
7. create the appropriate English scene files and a durable Batch 01 review/checkpoint;
8. synchronize README / HANDOVER / NEXT_CHAT_PROMPT and commit atomically.

P0 SHA-256 remains a separate pending fingerprint hold and does not block translation from the closed Tamil scene layer.

## Closed work safeguards

All previously closed works remain closed unless separately authorized or genuinely stronger source evidence appears.
