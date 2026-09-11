# Kalaignar Stage Plays — Handover

Repository: `pugazg/kalaignar-stage-plays`, branch `main`.

## Startup rule

Always fetch live `main` first and preserve newer durable state.

Permanent authorities:

1. `STAGE_PLAY_PROCESSING_GUIDE.md`;
2. `HISTORICAL_TAMIL_GLYPH_TRANSCRIPTION_GUIDE.md`;
3. `HISTORICAL_TAMIL_GLYPH_GATE.md`;
4. active work workflow `works/nachuk-koppai/BATCH_EXECUTION_WORKFLOW.md`.

# CURRENT CHECKPOINT — நச்சுக்கோப்பை P0 SOURCE INTAKE

Active work: `works/nachuk-koppai/`.

Controlling source: `ACL-TDD_00314_நச்சுக்_கோப்பை.pdf`.

Current durable state:

- physical scans: **63 confirmed**;
- source type: **image-only / no usable parsed text layer**;
- title: **நச்சுக்கோப்பை**;
- author: **மு. கருணாநிதி**;
- publisher: **திராவிடன் பதிப்பகம்**;
- edition: **முதல் பதிப்பு — 1951**;
- visually located numbered scenes: **18**;
- scan 63: **முற்றும்**;
- SHA-256: **PENDING**;
- file size: **PENDING**;
- P0: **PARTIAL / NOT CLOSED**;
- page records: **0 / 63**;
- H-GATE: **0 / 63**;
- scene assembly: **not started**;
- English translation: **not started**.

## Mandatory startup for next source-dependent turn

Read completely:

1. `STAGE_PLAY_PROCESSING_GUIDE.md`;
2. `HISTORICAL_TAMIL_GLYPH_TRANSCRIPTION_GUIDE.md`;
3. `HISTORICAL_TAMIL_GLYPH_GATE.md`;
4. this `HANDOVER.md`;
5. `NEXT_CHAT_PROMPT.md`;
6. `works/nachuk-koppai/README.md`;
7. `works/nachuk-koppai/SOURCE_INTAKE.md`;
8. `works/nachuk-koppai/BATCH_EXECUTION_WORKFLOW.md`;
9. `works/nachuk-koppai/metadata/source.md`;
10. `works/nachuk-koppai/metadata/context.md`;
11. `works/nachuk-koppai/indexes/page-map.md`.

## Exact next activity

1. resolve exact SHA-256 and byte size from the attached controlling PDF;
2. update `metadata/source.md` and `SOURCE_INTAKE.md`;
3. mark P0 **PASS** if no identity conflict appears;
4. process **Batch 01 — scans 1–10** using the two-pass workflow;
5. do not begin scene assembly or English translation.

## Closed work safeguards

`இரத்தக் கண்ணீர்`, `ஒரே முத்தம்`, `திருவாளர் தேசீயம்பிள்ளை`, `காகிதப்பூ`, `சிலப்பதிகாரம் — நாடகக் காப்பியம்`, `பரதாயணம்`, `அனார்கலி`, `சாக்ரடீஸ்`, `சேரன் செங்குட்டுவன்` and `மணிமகுடம்` remain closed unless separately authorized or genuinely stronger source evidence appears.
