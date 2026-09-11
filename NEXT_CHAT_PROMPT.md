# Next Chat Prompt — Kalaignar Stage Plays / நச்சுக்கோப்பை P0 closure + Batch 01 scans 1–10

Continue directly in `pugazg/kalaignar-stage-plays`, branch `main`, active work:

`works/nachuk-koppai/`

## LIVE MAIN IS AUTHORITATIVE

Fetch live `main` first and preserve newer durable state.

## Controlling source

`ACL-TDD_00314_நச்சுக்_கோப்பை.pdf`

Confirmed visual intake:

- physical scans: **63**;
- image-only;
- source title: **நச்சுக்கோப்பை**;
- author: **மு. கருணாநிதி**;
- publisher: **திராவிடன் பதிப்பகம்**;
- edition: **முதல் பதிப்பு — 1951**;
- preliminary numbered-scene inventory: **18**;
- scan 63: **முற்றும்**.

P0 remains **PARTIAL** only because exact SHA-256 and byte size are still pending.

## Mandatory startup

Read:

1. `STAGE_PLAY_PROCESSING_GUIDE.md`;
2. `HISTORICAL_TAMIL_GLYPH_TRANSCRIPTION_GUIDE.md`;
3. `HISTORICAL_TAMIL_GLYPH_GATE.md`;
4. root `HANDOVER.md`;
5. this prompt;
6. `works/nachuk-koppai/README.md`;
7. `works/nachuk-koppai/SOURCE_INTAKE.md`;
8. `works/nachuk-koppai/BATCH_EXECUTION_WORKFLOW.md`;
9. `works/nachuk-koppai/metadata/source.md`;
10. `works/nachuk-koppai/metadata/context.md`;
11. `works/nachuk-koppai/indexes/page-map.md`.

## Exact next activity

First compute the exact SHA-256 and byte size of the attached PDF and close P0 if they match this source identity.

Then process **Batch 01 — physical scans 1–10**:

- Pass A whole-page read once;
- create canonical page records `pages/0001.md` through `pages/0010.md`;
- ordinary visual verification;
- durable Pass-A commit with H-GATE pending;
- targeted independent H-GATE;
- create `BATCH_01_REVIEW.md`;
- update page map / work README / root README / handover / prompt;
- final closure commit if the entire batch passes.

Do not silently modernize Tamil. Do not use OCR, later editions or context to repair source pixels. Do not begin scene assembly or English translation yet.
